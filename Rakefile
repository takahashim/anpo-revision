require 'rake/clean'
require 'open-uri'
require 'fileutils'

LAW_URLS = %w(
http://law.e-gov.go.jp/htmldata/S29/S29HO165.html
http://law.e-gov.go.jp/htmldata/H04/H04HO079.html
http://law.e-gov.go.jp/htmldata/H11/H11HO060.html
http://law.e-gov.go.jp/htmldata/H12/H12HO145.html
http://law.e-gov.go.jp/htmldata/H15/H15HO079.html
http://law.e-gov.go.jp/htmldata/H16/H16HO113.html
http://law.e-gov.go.jp/htmldata/H16/H16HO114.html
http://law.e-gov.go.jp/htmldata/H16/H16HO116.html
http://law.e-gov.go.jp/htmldata/H16/H16HO117.html
http://law.e-gov.go.jp/htmldata/S61/S61HO071.html
)

SRCS = FileList["data/*.html"]
MDS  = SRCS.ext('md')

CLEAN.include(MDS)

task :all => MDS

rule ".md" => ".html" do |t|
  sh "nkf -w #{t.source} | pandoc  -f html -t markdown_strict+pipe_tables > #{t.name}"
end

task :download_files do
  FileUtils.mkdir_p("data")
  LAW_URLS.each do |url|
    filename = File.basename(url)
    File.open(File.join("data",filename), "w") do |wf|
      open(url) do |rf|
        str = rf.read
        wf.write(str)
      end
    end
  end
end
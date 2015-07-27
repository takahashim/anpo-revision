# 安全保障法制に関する法律改正に関する資料

2015年5月に閣議決定され、同年国会に提出された「我が国及び国際社会の平和及び安全の確保に資するための自衛隊法等の一部を改正する法律案」と「国際平和共同対処事態に際して我が国が実施する諸外国の軍隊等に対する協力支援活動等に関する法律案」の改正内容についての資料です。

## 現行の法律

自衛隊法
[data/S29HO165.md](data/S29HO165.md)

国際連合平和維持活動等に対する協力に関する法律
[data/H04HO079.md](data/H04HO079.md)

周辺事態に際して我が国の平和及び安全を確保するための措置に関する法律
[data/H11HO060.md](data/H11HO060.md)

周辺事態に際して実施する船舶検査活動に関する法律
[data/H12HO145.md](data/H12HO145.md)

武力攻撃事態等における我が国の平和と独立並びに国及び国民の安全の確保に関する法律
[data/H15HO079.md](data/H15HO079.md)

武力攻撃事態等におけるアメリカ合衆国の軍隊の行動に伴い我が国が実施する措置に関する法律
[data/H16HO113.md](data/H16HO113.md)

武力攻撃事態等における特定公共施設等の利用に関する法律
[data/H16HO114.md](data/H16HO114.md)

武力攻撃事態における外国軍用品等の海上輸送の規制に関する法律
[data/H16HO116.md](data/H16HO116.md)

武力攻撃事態における捕虜等の取扱いに関する法律
[data/H16HO117.md](data/H16HO117.md)

国家安全保障会議設置法
[data/S61HO071.md](data/S61HO071.md)

## 改正後の法律


### 上記ページの作成方法について

e-Govの法令データ提供システム(http://law.e-gov.go.jp/ )より取得したHTMLを元に、NKFとPandocを使ってMarkdownに変換しています。

主な作業は以下のようになります。

```
$ wget http://law.e-gov.go.jp/htmldata/S29/S29HO165.html
$ nkf -w S29HO165.html | pandoc  -f html -t markdown_strict+pipe_tables > S29HO165.md
```

### 問題点（課題）

* 表が正しく変換できていない(Pandocの問題)



## 参考

平和安全法制等の整備について
http://www.cas.go.jp/jp/gaiyou/jimu/housei_seibi.html

「平和安全法制」の概要  我が国及び国際社会の平和及び安全のための切れ目のない体制の整備(内閣官房 内閣府 外務省 防衛省)
http://www.cas.go.jp/jp/gaiyou/jimu/pdf/gaiyou-heiwaanzenhousei.pdf

## 現行の法律のソース

自衛隊法
http://law.e-gov.go.jp/htmldata/S29/S29HO165.html

国際連合平和維持活動等に対する協力に関する法律
http://law.e-gov.go.jp/htmldata/H04/H04HO079.html

周辺事態に際して我が国の平和及び安全を確保するための措置に関する法律
http://law.e-gov.go.jp/htmldata/H11/H11HO060.html

周辺事態に際して実施する船舶検査活動に関する法律
http://law.e-gov.go.jp/htmldata/H12/H12HO145.html

武力攻撃事態等における我が国の平和と独立並びに国及び国民の安全の確保に関する法律
http://law.e-gov.go.jp/htmldata/H15/H15HO079.html

武力攻撃事態等におけるアメリカ合衆国の軍隊の行動に伴い我が国が実施する措置に関する法律
http://law.e-gov.go.jp/htmldata/H16/H16HO113.html

武力攻撃事態等における特定公共施設等の利用に関する法律
http://law.e-gov.go.jp/htmldata/H16/H16HO114.html

武力攻撃事態における外国軍用品等の海上輸送の規制に関する法律
http://law.e-gov.go.jp/htmldata/H16/H16HO116.html

武力攻撃事態における捕虜等の取扱いに関する法律
http://law.e-gov.go.jp/htmldata/H16/H16HO117.html

国家安全保障会議設置法
http://law.e-gov.go.jp/htmldata/S61/S61HO071.html

## 新規追加される法律

国際平和共同対処事態に際して我が国が実施する諸外国の軍隊等に対する協力支援活動等に関する法律(国際平和支援法)

案文(PDF)
http://www.cas.go.jp/jp/gaiyou/jimu/pdf/anbun-kokusaiheiwasienhou.pdf

参照条文(PDF)
http://www.cas.go.jp/jp/gaiyou/jimu/pdf/sanshoujoubun-kokusaiheiwasienhou.pdf

要綱(PDF)
http://www.cas.go.jp/jp/gaiyou/jimu/pdf/youkou-kokusaiheiwasienhou.pdf

## Project Owner

Masayoshi Takahashi (twitter: @takahashim)

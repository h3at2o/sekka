# 雪華（sekka）

- IMEがなくても十分な収録字数「4000字」
- 頭で覚えやすい「漢字の主要構成パーツ」による分類
- 手で覚えやすい「左2連＋右1打/2連」の同時打鍵
- 送り仮名に無理なくつながる「カナ配列 薙刀式」に特化した配置
- 記憶負担を軽減「異体字同置」
- 頻出熟語は省打鍵「くずし字入力*」

＊ 現在、ライセンスの問題がない、偏りのない熟語頻度表が見つかっていない

## 目的
IMEがなくてもLinuxで日本語を打てるようにすること

## 導入に必要なもの
- Linux環境
- KMonad 4.2以上

## 実装上の問題点
- WindowsではWinComposeの設定が多過ぎるためか動作しない
- GnomeではIMEのインフラであるibusが「.XComposeが大き過ぎる」とエラーを吐く

## 参照資料
- 漢字系統樹表2800解字 善如寺俊彦 著
- 漢字字形史字典 教育漢字対応版 落合淳思 著
- 漢字出現頻度数調査（4）令和4年2月 文化庁国語課
- Wiki-40B/ja by Google Research
- 900連接調査 by 大岡俊彦
- 青蛙亭漢語塾 https://www.seiwatei.net/index.htm
- 漢字情報一覧（文字化け注意） https://www2q.biglobe.ne.jp/~bonichi/kj.HTM
- Unicode Character Database https://www.unicode.org/Public/UCD/latest/ucd/
- JISX0213 InfoCenter https://www.jca.apc.org/~earthian/aozora/0213.html
- JIS X 0213のコード対応表 https://x0213.org/codetable/
- 漢字辞典オンライン https://kanji.jitenon.jp/
- コトバンク https://kotobank.jp/

This software includes the work that is distributed in the [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0).

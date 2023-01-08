# 電気学会全国大会講演論文のLaTeXテンプレート（非公式）

電気学会全国大会の講演論文を生成するLaTeXテンプレートです。
電気学会が公開する[Wordのテンプレート](https://www.gakkai-web.net/gakkai/iee/smp/guide/template.html)および[サンプル](https://gakkai-web.net/iee/ippan/template/iee_sample.doc)をできるだけ再現するように作りました。

原稿の出力は、upLaTeX+BXjsclsでのみ確かめました。
他の環境では、もしかしたらエラーやレイアウトの崩れが起こるかもしれません。

注：このテンプレートはあくまで個人的な利用のために作成したものです。
利用は個人の責任でお願いします。
このテンプレートを利用したことによる原稿却下などの不利益には責任を負いません。

## 既知の問題など

- 節の最初の字下げを手動でおこなう必要がある。
- 調整はしたものの、mm単位のずれがまだ各所に残っている。（そもそもフォントサイズや余白幅の数値はサンプル記載の値に合わせておらず、出力結果の見た目が同じになるように調整している）
- 著者名と所属の英語表記がTimesフォントになっている（サンプルではMS明朝）。
- 図表の余白をサンプルに合うように姑息にいじっているのでなんとかしたい。

## 特に参考にした資料

- [LaTeX の箇条書の番号を全角文字で(Kodama's tips page)](http://www.math.kobe-u.ac.jp/HOME/kodama/tips-latex-enumz.html)
- [創作メモ LaTeX: 図表のキャプションの日本語・英語併記](http://nabew.blog113.fc2.com/blog-entry-18.html)
- [How to change the name of the bibliography](https://latex.org/forum/viewtopic.php?t=28709)

# 自作校務支援ソフト
* [採点斬り2021](https://github.com/phys-ken/saitenGiri2021)
  * デジタル採点支援のフリーソフト
  * ダウンロードの方法や使い方は、[解説動画](https://www.youtube.com/watch?v=zhaWaxFah2g)をご覧ください。
  * 拡張機能として、出力画像にマルバツの記号をつける、[marubatu.exe](https://phys-ken.github.io/saitenGiri2021-marubatu/)も公開しています。
  <iframe width="560" height="315" src="https://www.youtube.com/embed/zhaWaxFah2g" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

* [Google Classroomで個別配信するソフト](https://qiita.com/phys-ken/items/269a118df0bc0c895ad4)
  * リンク先の記事にある通り、Google Classroomで個別配信をしてくれます。割と便利だと思う。
  * Google App Scriptで生徒情報を書き出すコードは結構頑張って書きました。用意されているいくつかの関数はそのまま使えると思います。

* [マークシート採点システム](https://drive.google.com/drive/folders/106lB3aDrM7yY0l4laEngrddTJC2fYUjC?usp=sharing)
  * 神奈川県総合教育センターが配布する、マークシート採点のフリーソフト【[markscan](https://www.pen-kanagawa.ed.jp/edu-ctr/kenkyu/marksheet.html)】に対応した、Excel VBAを使用したExcelファイルです。
  * markscanは現在公式サイトからのダウンロードはできませんが、ダウンロード用のミラーサイトが複数あるので、ぜひ**「markscan ダウンロード」**などで検索してみてください。

* [markscan_bw.exe](https://phys-ken.github.io/image_thresholding_for_markscan/)
  * スキャナーでスキャンしたグレースケールのマークシートを、白黒の画像に分けます。
    * markscanというソフトでは、内部処理で二値化をしています。しかし、その様子をプレビューで見ることができません。レイアウトの読み込みがうまくいかないときは、二値化の際に右側のシンボルがうまく読み込めていないことが多いので、このソフトで事前に分けておくのはいかがでしょうか。　  

* [ウラオモテヤマネコ](https://phys-ken.github.io/uraomoteYamaneko/)
  * 両面スキャンした画像を、表裏ごとにフォルダ分けします

* [授業支援パワポアドイン](https://phys-ken.github.io/pptxAddIn_ForSchool/)
  * 授業準備で使えそうな機能を、アドインとしてまとめました。***4分割資料の一括作成*** 、***BIZ UDゴシックへの一括変換***などが可能です。

* [PDF2PPTX](https://github.com/phys-ken/pdf2pptx_win_mac)
  * PDFを一枚ずつ画像に変換し、パワーポイントに貼り付けます。推薦書の記入などで使えます。

* [silent_cutter](https://github.com/phys-ken/silent_cutter) (python,ffmpegが必要です)
  * 動画の無音部分を切り取って、結合します。授業動画の作成を助けます。


* markdownを利用した教材作成の効率化<[発表資料](https://www2.hamajima.co.jp/~tenjin/ypc/217/20210725markdown.pdf)>
  * [docx_pptx2md](https://github.com/phys-ken/docx_pptx2md) (pythonが必要です)
    * すでに作成したワードやパワーポイントの資料を、markdownに変換します。
  * [md2exam](https://github.com/phys-ken/md2exam) (pythonとpandocが必要です)
    * マークダウンの階層構造を分析して、試験問題のテンプレートをワードで作成します。選択肢を自動でソートし、マークシート式の際に使える解答番号の自動振りも行えます。

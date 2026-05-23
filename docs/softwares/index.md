# ソフトウェア

教育現場での作業効率化を目的とした自作ソフトウェアを公開しています。

!!! warning "利用上の注意"
    すべて趣味で作成したソフトウェアです。ミスがないよう注意していますが、**自己責任**でご利用ください。

## 採点・評価支援

### 採点斬り2021
**デジタル採点支援のフリーソフト**

[GitHubリポジトリ](https://github.com/phys-ken/saitenGiri2021){ .md-button }
[使い方動画](https://www.youtube.com/watch?v=zhaWaxFah2g){ .md-button .md-button--primary }

- **機能**: デジタル採点の効率化
- **拡張機能**: [マルバツ記号追加ツール](https://phys-ken.github.io/saitenGiri2021-marubatu/)

<div style="position: relative; width: 33%; height: 0; padding-bottom: 18.75%; max-width: 300px;">
  <iframe src="https://www.youtube.com/embed/zhaWaxFah2g" 
          style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" 
          frameborder="0" allowfullscreen>
  </iframe>
</div>

### マークシート採点システム
**Excel VBA版マークシート採点支援**

[ダウンロード](https://drive.google.com/drive/folders/106lB3aDrM7yY0l4laEngrddTJC2fYUjC?usp=sharing){ .md-button }

- **対応ソフト**: [markscan](https://www.pen-kanagawa.ed.jp/edu-ctr/kenkyu/marksheet.html) (神奈川県総合教育センター配布)
- **プラットフォーム**: Excel VBA
- **備考**: markscanは公式配布終了のため、「markscan ダウンロード」で検索してミラーサイトを利用してください

### markscan_bw.exe
**マークシート画像の二値化処理**

[ダウンロード](https://phys-ken.github.io/image_thresholding_for_markscan/){ .md-button }

- **機能**: グレースケールのマークシート画像を白黒二値化
- **用途**: markscanでの読み込み精度向上

## Google Classroom連携

### 個別配信システム
**Google Classroomでの個別資料配信**

[詳細記事](https://qiita.com/phys-ken/items/269a118df0bc0c895ad4){ .md-button }

- **プラットフォーム**: Google Apps Script
- **機能**: 生徒個別の資料配信自動化
- **特徴**: 生徒情報の効率的な書き出し機能

## 文書・ファイル処理

### ウラオモテヤマネコ
**両面スキャン画像の自動仕分け**

[ダウンロード](https://phys-ken.github.io/uraomoteYamaneko/){ .md-button }

- **機能**: 両面スキャンした画像を表裏ごとにフォルダ分け
- **用途**: 大量の文書スキャン後の整理作業効率化

### PDF2PPTX
**PDF→PowerPoint変換ツール**

[GitHubリポジトリ](https://github.com/phys-ken/pdf2pptx_win_mac){ .md-button }

- **機能**: PDFを1ページずつ画像に変換してPowerPointに挿入
- **対応OS**: Windows・Mac
- **用途**: 推薦書記入、資料作成

## 授業支援

### 座席ルーレット
**ランダム座席替え・グループ分けWebアプリ**

[座席シャッフルを使う](https://phys-ken.github.io/Seat_Roulette/layout_custom.html){ .md-button .md-button--primary }
[グループ分けを使う](https://phys-ken.github.io/Seat_Roulette/group_roulette.html){ .md-button }
[GitHubリポジトリ](https://github.com/phys-ken/Seat_Roulette){ .md-button }

- **機能**: 教室の座席配置をランダム化・グループ分け
- **特徴**: 黒板投影に最適化したシンプルなUI、インストール不要
- **座席シャッフル**: 最大180席（行・列数を自由に設定）、結果をExcelでダウンロード
- **グループ分け**: 最大200人・30グループ対応、PDF出力（生徒ビュー・班ごとビュー・円卓ビューの3種）
- **技術**: Vanilla JavaScript、SheetJS (Excel出力)、jsPDF (PDF出力)

### PowerPointアドイン
**授業準備効率化アドイン**

[ダウンロード](https://phys-ken.github.io/pptxAddIn_ForSchool/){ .md-button }

- **主要機能**:
    - 4分割資料の一括作成
    - BIZ UDゴシックへの一括フォント変換
- **用途**: 授業資料の標準化・効率化

### silent_cutter
**動画編集支援ツール** 

[GitHubリポジトリ](https://github.com/phys-ken/silent_cutter){ .md-button }

- **機能**: 動画の無音部分を自動検出・削除・結合
- **要件**: Python, FFmpeg
- **用途**: 授業動画の編集効率化

## 教材作成支援

### 波の重ね合わせ 設問作成ソフト
**物理教員向けの波形設問（PDF/DOCX/ZIP）自動生成ツール**

[ブラウザで今すぐ使う](https://phys-ken.github.io/nami_gousei_software/){ .md-button .md-button--primary }
[GitHubリポジトリ](https://github.com/phys-ken/nami_gousei_software){ .md-button }

- **機能**: グリッドをクリック・ドラッグして波形を手描きし、問題・解答・解説をワンクリックで出力
- **設問タイプ**: y-xグラフ・数値解答・y-tグラフ・合成波・反射波など7種類
- **出力形式**: 問題PDF・解答PDF・DOCX（Word編集可）・ZIP一括（PDF＋DOCX＋全画像）
- **特徴**: インストール不要・ブラウザだけで動作、白黒印刷用スタイル対応
- **技術**: Vanilla JavaScript、REST API（Node.js）でAIエージェント連携も可能

| 設問タイプ | 内容 |
|------|------|
| Type 1 | 指定時刻の y-x グラフ |
| Type 3 | 指定地点の y-t グラフ（選択肢対応） |
| Type 4 | 重ね合わせ波・指定時刻（選択肢対応） |
| Type 6 | 反射波・指定時刻（選択肢対応） |

### Markdown教材作成システム
**文書作成ワークフローの効率化**

[発表資料](https://www2.hamajima.co.jp/~tenjin/ypc/217/20210725markdown.pdf){ .md-button }

#### docx_pptx2md
[GitHubリポジトリ](https://github.com/phys-ken/docx_pptx2md){ .md-button }

- **機能**: Word・PowerPointファイルをMarkdown形式に変換
- **要件**: Python

#### md2exam  
[GitHubリポジトリ](https://github.com/phys-ken/md2exam){ .md-button }

- **機能**: Markdownから試験問題テンプレートを自動生成
- **特徴**: 選択肢の自動ソート、解答番号の自動振り分け
- **要件**: Python, Pandoc

## 開発Tips

### VBA Tips
**プリンター設定の自動化**

[Gistで確認](https://gist.github.com/phys-ken/23ef7fcce39e1eb5a8ba2ee27795b2e1){ .md-button }

- **内容**: VBAでアクティブプリンターを設定するコード例

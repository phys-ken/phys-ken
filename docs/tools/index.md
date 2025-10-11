# ツール

物理教育で使用できるインタラクティブなWebアプリケーションを開発・公開しています。

## 実験・測定ツール

### Web Serial API 物理実験ツール
**ブラウザでリアルタイム測定**

[:material-web: アプリを開く](https://phys-ken.github.io/webserial_app){ .md-button .md-button--primary }

![データ取得の様子](../fig/graph.gif)

- **機能**: Web Serial APIを使用したリアルタイムデータ取得・グラフ化
- **対応**: Chromebook対応
- **用途**: 生徒実験での測定・記録

### 音量感応LEDシステム
**音に反応する明度制御**

[:material-web: デモを見る](https://phys-ken.github.io/volume_led2/README.html){ .md-button }

![音量で変化するLED](../fig/resAnime.gif)

- **機能**: 音量に応じたLED明度制御
- **技術**: Web Audio API活用
- **教育効果**: 音波の可視化

### 超音波距離センサー
**M5Stack使用の測距システム**

[:material-github: GitHubで詳細](https://github.com/phys-ken/M5Stack_SonicDist){ .md-button }

![距離測定の様子](../fig/processing.gif)

- **ハードウェア**: M5Stack
- **機能**: 超音波による距離測定とデータ記録
- **用途**: 物体の運動測定

## 物理シミュレーション

### 電気回路可視化ツール
**電位の高低をインタラクティブに表示**

[:material-web: シミュレーション](https://phys-ken.github.io/Circuit_App/){ .md-button .md-button--primary }

![電圧の可視化](https://phys-ken.github.io/Circuit_App/fig/Cir.gif)

- **機能**: 回路の電位差を色とアニメーションで表現
- **教育効果**: 抽象的な電位概念の具体化

### 定常波形成アニメーション
**波の重ね合わせ可視化**

[:material-web: アニメーション](https://phys-ken.github.io/Resonance_Mov/Slide.html){ .md-button }

![定常波の形成](https://phys-ken.github.io/Resonance_Mov/export/string/out5.gif)

- **機能**: 進行波と反射波の重ね合わせによる定常波形成過程
- **教育効果**: 波の干渉現象の理解促進

### 幾何光学シミュレーション
**レンズの光線追跡**

[:material-web: シミュレーション](https://phys-ken.github.io/Optics/README.html){ .md-button }

![光学シミュレーション](../fig/lens.JPG)

- **機能**: レンズによる光線の屈折・集光の可視化
- **用途**: 幾何光学の理解支援

## 開発中プロジェクト

### 弾性エネルギーシミュレーション
**ばね系のエネルギー保存**

[:material-web: プレビュー版](https://phys-ken.github.io/spring_energy_system/){ .md-button }

!!! info "開発状況"
    現在開発中です。停止ボタンの実装を予定しています。

- **機能**: ばねの弾性エネルギーと運動エネルギーの変換可視化
- **計画**: インタラクティブな操作機能の追加

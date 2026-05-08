# 教材・ツール

物理の授業で使えるWebアプリケーションを作って公開しています。

!!! note "利用について"
    すべて趣味で作ったものです。授業で使っていただいても構いませんが、**自己責任**でお願いします。

## 実験・測定ツール

実際の測定やデータ取得に使えるツールです。

### シンプル低周波発振器
**物理実験・音響実験用のブラウザ発振器**

[発振器を使う](https://phys-ken.github.io/simple_audio_app/teisyuha_buturikiso.html){ .md-button .md-button--primary }
[GitHubリポジトリ](https://github.com/phys-ken/simple_audio_app){ .md-button }

- **周波数範囲**: 1Hz〜20000Hz（0.1Hz単位で設定可能）
- **操作**: 各桁のボタンで周波数を調整、スライダーで大まかな調整
- **特徴**: インストール不要、レスポンシブ対応（スマートフォン・タブレット・PCで動作）
- **用途**: 音の物理実験（共鳴・うなりなど）での発振源に

### Web Serial API 物理実験ツール

**ブラウザでリアルタイム測定**

[アプリを使う](https://phys-ken.github.io/webserial_app){ .md-button .md-button--primary }

![データ取得の様子](../fig/graph.gif)

Chromebookでセンサーからのデータをリアルタイムでグラフ化できます。生徒実験での測定・記録に便利です。

### 音量感応LEDシステム

**音に反応するLED制御**

[デモを見る](https://phys-ken.github.io/volume_led2/README.html){ .md-button }

![音量で変化するLED](../fig/resAnime.gif)

マイクで拾った音量に応じてLEDの明るさが変わります。音波を目で見ることができます。

### 超音波距離センサー

**M5Stackを使った距離測定**

[詳細を見る](https://github.com/phys-ken/M5Stack_SonicDist){ .md-button }

![距離測定の様子](../fig/processing.gif)

M5Stackと超音波センサーで距離を測定し、データを記録できます。物体の運動の測定に使えます。

## シミュレーション

物理現象を視覚的に理解できるシミュレーションです。

### 電気回路の電位可視化

**回路の電位をアニメーションで表示**

[シミュレーション](https://phys-ken.github.io/Circuit_App/){ .md-button .md-button--primary }

![電圧の可視化](https://phys-ken.github.io/Circuit_App/fig/Cir.gif)

回路内の電位の高低を色とアニメーションで表現します。抽象的な電位の概念を具体的に理解できます。

### 定常波の形成アニメーション

**波の重ね合わせを可視化**

[アニメーション](https://phys-ken.github.io/Resonance_Mov/Slide.html){ .md-button }

![定常波の形成](https://phys-ken.github.io/Resonance_Mov/export/string/out5.gif)

進行波と反射波が重なって定常波ができる様子をアニメーションで見ることができます。

### 幾何光学シミュレーション

**レンズの光線をシミュレーション**

[シミュレーション](https://phys-ken.github.io/Optics/README.html){ .md-button }

![光学シミュレーション](../fig/lens.JPG)

レンズを通る光線の屈折や集光の様子を可視化します。幾何光学の理解に役立ちます。

## 開発中のもの

### ばねのエネルギーシミュレーション

**弾性エネルギーと運動エネルギーの変換**

[プレビュー版](https://phys-ken.github.io/spring_energy_system/){ .md-button }

!!! info "開発状況"
    まだ作成中です。停止ボタンなどを追加予定です。

ばねの弾性エネルギーと物体の運動エネルギーが変換される様子を見ることができます。

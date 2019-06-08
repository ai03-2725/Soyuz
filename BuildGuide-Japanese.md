# Soyuz ビルドガイド

### 部品

* 1x PCB（上下のプレートとメインPCBのセット）
* 1x Pro MicroやElite-C等のマイコンボード（ピンアウトが同じなら使えます）
* 4x M2スペーサー、12～14mm
* 8x M2ネジ
* 20x 1N4148ダイオード
* 17-20x Cherry MX互換スイッチ（数はレイアウトによる）
* 0-3x Cherry MX互換PCBスタビライザー（数はレイアウトによる）
* 1x 6x6mmリセットボタン
* 4x ゴム足
* キーキャップ
* USBケーブル  

### 組み立て方

1. PCBをメインPCBとプレート二枚に分解します。
2. ダイオードをPCBへ半田付けします。
3. Pro Micro用のヘッダーとリセットボタンをPCBへ半田付けします。
4. 必要な場合、スタビライザーをPCBに配置します。
5. 四隅のスイッチをスイッチプレートに設置し、PCBと合体させます。
6. スイッチを半田付けします。
7. Pro Microをヘッダーへ半田付けします。
8. この段階で、半田付けにミスがないことを確認し、ファームウエアを書き込みます。
9. スペーサーをスイッチプレートの四隅にネジ止めします。
10. 下プレートをネジ止めします。
11. ゴム足を付けます。
12. キーキャップを載せて完成です。  

### ファームウエアの作成

初心者向け：
* [QMK Configurator](https://config.qmk.fm/#/ai03/soyuz/LAYOUT_ortho_5x4)を使用

玄人向け：
* [ソースからコンパイル](https://github.com/qmk/qmk_firmware/tree/master/keyboards/ai03/soyuz)

### ファームウエアの書き込み

[QMK Toolbox](https://github.com/qmk/qmk_toolbox/releases)を使用することをお勧めします。

### 組み立てビデオ

SpaceCat Design:  
[![Video by SpaceCat Design](http://img.youtube.com/vi/LFRCjzilOcM/0.jpg)](https://www.youtube.com/watch?v=LFRCjzilOcM)
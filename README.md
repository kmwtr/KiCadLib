# KiCadLib
Kicad library designed for ChinchillaSystems

## Memo

### シンボルライブラリーとフットプリントライブラリーの構造

#### シンボルライブラリー

* *.lib
  * EESchema-LIBRARY
  * シンボルライブラリ－。**この一つのファイルの中に複数のシンボルが含まれる。**
* *.dcm
  * EESchema-DOCLIB
  * シンボルライブラリーの関連ドキュメント。説明やURL等が記述されている。

#### フットプリントライブラリー

* *.pretty フォルダ
  * フットプリントライブラリー。**フォルダ。この中に個別のフットプリントファイルが格納されている。**
* *.kicad_mod
  * フットプリントファイル。個別のフットプリント。

シンボルライブラリーはファイル、フットプリントライブラリーはフォルダで管理されている…。

### 注意

KiCad をアップデートすると Program Files\KiCad 内のライブラリは初期化される？

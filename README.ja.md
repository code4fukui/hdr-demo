# HDR DEMO by WebGPU (rgba16float + Float16Array)

このデモはWebGPUを使ってHDRの描画を実現するサンプルです。Float16Arrayをそのままテクスチャにアップロードし、シェーダーでtextureLoadを使って読み出しています。

## デモ
[HDR DEMO by WebGPU](https://fukuno.jig.jp/3927)

## 機能
- WebGPUを使ったHDRデモ
- キャンバスサイズ自動調整
- HDR階調の動きを表現
- エクスポージャーとMaxStopsの調整可能

## 必要環境
- WebGPUに対応したブラウザ
- Float16Arrayをサポートしているブラウザ

## 使い方
ブラウザでデモページを開くと、WebGPUとFloat16Arrayのサポート状況を確認し、対応していれば動作します。
エクスポージャーとMaxStopsのスライダーで調整できます。

## ライセンス
このプロジェクトはMITライセンスで提供されています。
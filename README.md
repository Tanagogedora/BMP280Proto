# BMP280Proto
# BMP280 Sensor Extension for micro:bit  
# micro:bit 用 BMP280 センサー拡張機能
> ⚠️ **この拡張機能は現在ベータ版です。動作確認中の機能が含まれます。ご使用の際はご注意ください。**

This extension allows the micro:bit to communicate with a BMP280 digital pressure and temperature sensor via I2C.  
You can measure atmospheric pressure and temperature.  
Sensor values are based on the official BMP280 datasheet.

この拡張機能は、BMP280 デジタル気圧・気温センサーを micro:bit の MakeCode 上で利用するためのものです。  
気圧と気温の測定が可能です。センサー仕様は BMP280 のデータシートに基づいています。

> 🔗 **Demo Page:**デモページを見る: [https://tanagogedora.github.io/BMP280Proto/](https://tanagogedora.github.io/BMP280Proto/)

---
## 📦 How to Use / 使い方
### As a MakeCode Extension
1. Open [https://makecode.microbit.org/](https://makecode.microbit.org/)
1. Create a new project
1. Click the gear icon (⚙) → "Extensions"
1. Paste the following URL to add the extension  
   `https://github.com/tanagogedora/BMP280Proto`   

---

### MakeCode 拡張機能としての使用方法

1. MakeCode [https://makecode.microbit.org/](https://makecode.microbit.org/)を開く
1. 「新しいプロジェクト」をクリック
1. 画面右上のギアボタン（⚙）をクリックし、「拡張機能」を選択 
1. 下記の URL を検索または貼り付けてインポート    
   `https://github.com/tanagogedora/BMP280Proto` 

### 🖼 Example Blocks / ブロック例

![BMP280 ブロック](https://github.com/Tanagogedora/bmp280betaVrJP/blob/main/BMP280block.png?raw=true)

---

### ✏️ To modify the extension source code in MakeCode:

1. Open [https://makecode.microbit.org/](https://makecode.microbit.org/)
1. Click "Import" → "Import URL"
1. Paste this URL
`https://github.com/tanagogedora/BMP280Proto`  

---

### ✏️ MakeCode 上で編集

1. MakeCode [https://makecode.microbit.org/](https://makecode.microbit.org/) を開く
1. 「読み込む」→「URLから読み込む…」を選択
1. 以下の URL を貼り付けてインポート :  
   `https://github.com/tanagogedora/BMP280Proto`

---

## 🧪 Sensor Specification (Based on Datasheet) / 測定仕様（参考：データシートより）


| Measurement(測定対象) | Range(範囲) | Accuracy(精度) | Resolution(分解能) |
|-----------|------------------|-------------------|--------------------|
| Pressure(気圧) | 300 ～ 1100 hPa | ±1.0 ～ 1.7 hPa | ±0.16 Pa |
| Temperature(気温) | -40 ～ +85 ℃ | ±0.5 ～ 1.0 ℃ | ±0.01 ℃ |

※ 上記の値は BMP280 の公式データシートに基づく参考値です。

## 📝 Acknowledgement

This extension is based on the BME280 TypeScript implementation originally developed by the microbit/micropython Chinese community (2018).  
However, due to differences in initialization and control flow, this version has been re-implemented specifically for the BMP280 sensor.  
We adapted and extended it for use in Japanese educational contexts, adding Japanese block support and improved decimal precision for science experiments.

Original Source: http://www.micropython.org.cn

## 📝 謝辞・ベースとなった実装について

本拡張機能は、microbit/micropython 中国コミュニティ（2018年）による BME280 TypeScript 実装をもとに開発しています。  
ただし、BME280 向け実装とは初期化方法や制御仕様が異なるため、本拡張機能は BMP280 専用として新たに移植・再構築されたものです。  
日本の教育現場での利用を想定し、ブロックの日本語対応や小数点精度での測定機能も追加しています。

元コード提供元（参考）：http://www.micropython.org.cn


## 📝 ライセンス

© 2025 Tanagotti  
Based on BME280 code by the microbit/micropython Chinese community (2018)  
Original Source: http://www.micropython.org.cn  
（元コード：microbit/micropython 中国コミュニティによる BME280 実装）
  
---

## 🔍 メタデータ（MakeCode レンダリング用）

```html
<script src="https://makecode.com/gh-pages-embed.js"></script>
<script>
makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");
</script>


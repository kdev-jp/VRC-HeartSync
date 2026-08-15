# VRC HeartSync

![「VRC HeartSync」の紹介画像。上部にModular Avatarのロゴがあり、中央に黄色い大きな数字で000と表示され、下部に「心拍数表示ギミック VRC HeartSync」と書かれている](https://github.com/kdev-jp/VRC-HeartSync/blob/d93d4cd7c223a6979ea224859aefc9c877467939/docs-assets/images/VRC-HeartSync_1.png)

![VRC HeartSyncの使用例。水色の背景にVRChatの女性アバターが写っている。](https://github.com/kdev-jp/VRC-HeartSync/blob/d93d4cd7c223a6979ea224859aefc9c877467939/docs-assets/images/VRC-HeartSync_2.png)

スマートウォッチなどから取得した心拍数を、アバター上にリアルタイムで表示できるギミックです。

心拍データの取得には、Pulsoid（API）および VRCOSC（いずれも無料）またはPulsoid OSCの設定が必要です。

動作確認は行っていませんが、Bluetooth Low Energy 接続でも問題なく動作すると思われます。

Modular Avatar に対応しているため、プレハブ を配置して位置を調整するだけで簡単に導入できます。<br>
デフォルトでは「顔」に表示されますが、他の位置に移動させたい場合も簡単な設定で変更可能です。

また、色の変更にも対応しています。

詳しくは、導入方法をご覧ください。

The English product description is provided after the Japanese version below.

## 対応デバイス
Pulsoid APIおよびPulsoid Cloudで接続する場合<br>
Apple Watch、Pixel Watch、Galaxy Watch、Fitbit、Garminなどで利用可能です。<br>
※ご利用環境によっては動作しない場合があります。

対応デバイスの詳細は、Pulsoid公式サイトをご確認ください。<br>
https://blog.pulsoid.net/monitors

Bluetooth Low Energyで接続する場合<br>
Bluetooth Low Energyに対応したスマートウォッチや心拍計が必要です。

## 導入方法
導入方法については、以下のサイトをご覧ください。

OSCの設定方法<br>
Pulsoid OSCまたはVRCOSCのいずれかをご利用ください。

【有料】Pulsoid OSC<br>
https://k-dev.notion.site/VRC-HeartSync-Pulsoid-OSC-298645d6d70d804ab7c8eeb6e4c408dc

提供：Pulsoid<br>
VRC HeartSyncの開発・動作検証のため、PulsoidよりBROプランの無償提供を受けています。<br>
Pulsoid OSCについて<br>
VRChatのチャットボックスへの心拍数表示機能や、Discordとの連携機能などがあります。<br>
https://pulsoid.net/products/osc

【無料】VRCOSC<br>
https://k-dev.notion.site/VRC-HeartSync-VRCOSC-298645d6d70d8010a584ca7f0e439c1b


<br>
アバターへのギミック導入方法<br>
https://k-dev.notion.site/VRC-HeartSync-3bb645d6d70d808ba722f4d1b0628200

## 利用規約
[ライセンスファイル](LICENSE.md)をご覧ください。

## 注意事項
本データの利用により生じた損害やトラブルについて、当方は一切責任を負いません。自己責任でご利用ください。

Android(Quest)およびiOSは非対応です。

VRChatやPulsoid、VRCOSCの仕様変更により、正常に動作しなくなる場合があります。

アバターは付属しません。

VRCOSCのパラメーター名や「Normalised Parameter」の数値を変更すると、正常に動作しない可能性があります。

## クレジット
Simple Counter Shader<br>
https://www.patreon.com/posts/62864361

VRCOSC<br>
https://github.com/VolcanicArts/VRCOSC

サメっ子オリジナル3Dモデル「rurune」-ルルネ- ©Paryi<br>
https://booth.pm/ja/items/5957830

## Product Description
The English version of this product description was created using machine translation.

This is a gimmick that allows you to display your heart rate, obtained from a smartwatch or similar device, on your avatar in real time.

To obtain heart rate data, you need to configure Pulsoid (API) and VRCOSC (both free) or Pulsoid OSC

Although operation has not been confirmed with Bluetooth Low Energy (BLE) connections, it is expected to work without any issues in theory.

Since this product supports Modular Avatar, you can easily install it by placing the prefab and adjusting its position.<br>
By default, the heart rate is displayed on the Face, but you can easily change the position through simple settings.

Color customization is also supported.

For more details, please refer to the Setup Guide.

## Supported Devices
When using Pulsoid API or Pulsoid Cloud:<br>
Compatible with devices such as Apple Watch, Pixel Watch, Galaxy Watch, Fitbit, Garmin, and more.<br>
Please note that proper operation cannot be guaranteed in all environments.<br>
For a detailed list of supported devices,

please refer to the official Pulsoid website:<br>
https://blog.pulsoid.net/monitors


When connecting via Bluetooth Low Energy (BLE):<br>
A smartwatch or heart rate monitor that supports Bluetooth Low Energy is required.

## Setup Guides
We apologize for the inconvenience, but in some environments, the documentation site may not display correctly.<br>
If this occurs, please try viewing it in a different browser.

The following page provides the setup guide in English.

OSC Setup<br>
Please use either Pulsoid OSC or VRCOSC.

【Paid】Pulsoid OSC<br>
https://k-dev.notion.site/VRC-HeartSync-Setup-Guide-Pulsoid-OSC-Installation-and-Configuration-3bb645d6d70d8015b056d6e194a6f139

Provided by: Pulsoid<br>
Pulsoid provides the BRO plan free of charge for the development and testing of VRC HeartSync.<br>
About Pulsoid OSC<br>
Pulsoid OSC includes features such as displaying heart rate in the VRChat chatbox and integrating with Discord.<br>
https://pulsoid.net/products/osc

【Free】VRCOSC<br>
https://k-dev.notion.site/VRC-HeartSync-Setup-Guide-VRCOSC-Installation-and-Configuration-29b645d6d70d803ebf67c240a5d55401


<br>
How to Install the Gimmick on Your Avatar<br>
https://k-dev.notion.site/VRC-HeartSync-Setup-Guide-Avatar-Gimmick-Installation-3bb645d6d70d80c1a324e8d53fa6a46e

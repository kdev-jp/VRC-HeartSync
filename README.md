# VRC HeartSync

![VRC HeartSyncの画像](https://github.com/kdev-jp/VRC-HeartSync/blob/d93d4cd7c223a6979ea224859aefc9c877467939/docs-assets/images/VRC-HeartSync_1.png)

![VRC HeartSyncの使用例](https://github.com/kdev-jp/VRC-HeartSync/blob/d93d4cd7c223a6979ea224859aefc9c877467939/docs-assets/images/VRC-HeartSync_2.png)

スマートウォッチなどから取得した心拍数を、VRChatのアバター上にリアルタイムで表示できるギミックです。

心拍データの取得には、Pulsoid および VRCOSC（いずれも無料）の設定が必要です。

動作確認は行っていませんが、Bluetooth Low Energy 接続でも問題なく動作すると思われます。

Modular Avatar に対応しているため、プレハブ を配置して位置を調整するだけで簡単に導入できます。
デフォルトでは「Chest（胸）」に表示されますが、他の位置に移動させたい場合も簡単な設定で変更可能です。

また、色の変更にも対応しています。

詳しい導入方法は Wiki をご覧ください。

不具合やご不明点がありましたら、GitHub Issuesからお気軽にご連絡ください。

## 対応デバイス
Pulsoidで接続する場合<br>
Apple Watch、Pixel Watch、Galaxy Watch、Fitbit、Garminなどで利用可能です。<br>
※ご利用環境によっては動作しない場合があります。

対応デバイスの詳細は、Pulsoid公式サイトをご確認ください。<br>
https://blog.pulsoid.net/monitors

Bluetooth Low Energyで接続する場合<br>
Bluetooth Low Energyに対応したスマートウォッチや心拍計が必要です。

## 導入方法・ドキュメント
一部の環境において、ドキュメントサイトが正しく表示されない場合がございます。<br>
その場合、お手数をおかけいたしますが、別のブラウザでの閲覧をお試しください。

導入方法については、以下のサイトをご覧ください。

Pulsoidのトークンの取得方法が変更されたため、導入方法を更新しました(2026年7月24日)

導入方法<br>
https://k-dev.notion.site/VRC-HeartSync-298645d6d70d8010a584ca7f0e439c1b

Setup Guide(English)<br>
https://k-dev.notion.site/VRC-HeartSync-Setup-Guide-29b645d6d70d803ebf67c240a5d55401

ドキュメント<br>
https://k-dev.notion.site/VRC-HeartSync-Document-29a645d6d70d80408cdcff49b5c81401

## 利用規約
本データをダウンロードする際は、以下の利用規約に同意したものとみなします。

日本語版と他言語版との内容に差異が生じた場合は、日本語版の利用規約が優先されます。

本規約は、あしやまひろこ氏が作成したVN3ライセンス（ https://www.vn3.org/ ）のテンプレートを使用しています。

利用規約（JP）<br>
https://www.dropbox.com/scl/fi/fvx1lldzsao83uyzetubs/VRCHeartSync_license_ja.pdf?rlkey=g7cm8el5k9wvtcbdxc43d4oik&st=xbd634d0&dl=0

Terms of Use（EN）<br>
https://www.dropbox.com/scl/fi/0ocqqpjo4ccrzyifzhxdj/VRCHeartSync_license_en.pdf?rlkey=ali0gpjntr86dz3e0y2m4ke79&st=0rwbq8iy&dl=0

Terms of Use（ZH）<br>
https://www.dropbox.com/scl/fi/hotq1a5jau7mf9j9aam44/VRCHeartSync_license_zh.pdf?rlkey=iotclpczx8oibsn73pykcik8o&st=mohmbjye&dl=0

Terms of Use（KO）<br>
https://www.dropbox.com/scl/fi/4zu2y9svpj579wqkkmbmz/VRCHeartSync_license_ko.pdf?rlkey=5v1hv9o4x1vmlbe69ple9tts3&st=znjq6rst&dl=0

## 注意事項
本データの利用により生じた損害やトラブルについて、当方は一切責任を負いません。自己責任でご利用ください。

Android(Quest)およびiOSは非対応です。

VRChat や Pulsoid、VRCOSC の仕様変更により、正常に動作しなくなる場合があります。

アバターは付属しません。

VRCOSCのパラメーター名や「Normalised Parameter」の数値を変更すると、正常に動作しない可能性があります。

## クレジット
Simple Counter Shader<br>
https://www.patreon.com/posts/62864361

VRCOSC<br>
https://github.com/VolcanicArts/VRCOSC

サメっ子オリジナル3Dモデル「rurune」-ルルネ- ©Paryi<br>
https://booth.pm/ja/items/5957830

## アップデート履歴
2025-10-29 Ver.1.0.0 リリース

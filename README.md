 # iPhone Phone Web

ブラウザ上で動く **iPhone風電話アプリ** です。  
番号入力・発信ボタン・自動音声Bot応答など、iPhoneの電話アプリの基本操作を再現しています。

## 主な機能
- iPhone風のUIデザイン
- 画面中央の番号入力フィールド
- 3x4の数字キー + 発信ボタン
- 発信すると自動音声Botが応答（Web Speech API使用）
- （オプション）OpenAI TTS APIで音声を生成可能

## 使い方
1. このリポジトリをクローンまたはZIPダウンロード
2. `index.html` をブラウザで開く
3. 数字キーで番号を入力し、「📞 Call」を押すとBotが応答

## 技術
- HTML / CSS / JavaScript
- Web Speech API（ブラウザでの音声再生）
- Node.js + OpenAI TTS API（拡張用）

## ライセンス
MIT License

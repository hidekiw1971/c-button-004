# compornent（共通部品）

## イメージ画像

- xxx

## 概要

- button 要素の配下に a タグを設置すると、w3c html チェッカーでエラーになります。
- button 要素をやめて、div にすればエラーはなくなります。

## 仕様

- スマホファースト
- rem 記述
- ルートフォントを vw で設定していることから PC サイズのレイアウトをタブレットで表示させることが出来ます（rem で書いた場合のみ）。
- xxx

## 注意事項

- Element button must not appear as a descendant?
- button 要素は、（a）要素の子孫として表示しなければいけません。
- https://tinyurl.com/ybyvujf3

## 使い方

- 「copy start」から「copy end」をコピペ。
- css: src -> module -> xxx をコピペ。

## w3c html チェック結果

- https://validator.w3.org/nu/

## w3c css チェック結果

- https://jigsaw.w3.org/css-validator/

## portfolio url:

- https://c-0034.wtb.cfbx.jp/

## 参考にしたサイト

- CSS：ボタンホバー時に背景がスライドしたり領域を覆うアニメーションサンプル 10
- https://www.nxworld.net/10-css-hover-fill-animation.html
- Element button must not appear as a descendant?
- button 要素は、（a）要素の子孫として表示しなければいけません。
- https://tinyurl.com/ybyvujf3

## 更新履歴

- 2022/3/25 初版 作成完了(button 要素ではエラーになるので、div に切替て完成)

## 環境・使い方

- ダウンロードしたフォルダを開く。
- ターミナルを開き、 npm i とコマンドを入力する。
- node_modules と package-lock.json が生成されるのを確認する。
- 「 npx gulp 」とコマンドを入力すると動き出します。

## 備考

# compornent（共通部品）

## イメージ画像
<img width="396" alt="image" src="https://user-images.githubusercontent.com/99580997/160091780-7876fff2-76cd-4988-91b0-0369ecfbd6d9.png">
<img width="776" alt="image" src="https://user-images.githubusercontent.com/99580997/160091847-fa6656f0-972d-45eb-a310-d75e4853eaa4.png">
<img width="1233" alt="image" src="https://user-images.githubusercontent.com/99580997/160091914-bf0e696f-337b-4b40-96b9-995c3c02349e.png">


## 概要

- button 要素の配下に a タグを設置すると、w3c html チェッカーでエラーになります。→　git resetで戻せます。
- button 要素をやめて、div にすればエラーはなくなります。→ git resetで戻せます。

## 仕様

- スマホファースト
- rem 記述
- ルートフォントを vw で設定していることから PC サイズのレイアウトをタブレットで表示させることが出来ます（rem で書いた場合のみ）。
- xxx

## 注意事項

- Element button must not appear as a descendant?
- button 要素は、（a）要素の子孫として表示しなければいけません。
- https://tinyurl.com/ybyvujf3
- これはこの状態で作成完了とします。w3c htmlエラーtaiousitamonoha`c-button-005`でonclickを使用して実装してます。

## 使い方

- 「copy start」から「copy end」をコピペ。
- css: src -> module -> xxx をコピペ。

## w3c html チェック結果

- https://validator.w3.org/nu/
- <img width="892" alt="image" src="https://user-images.githubusercontent.com/99580997/160092708-abb81d0c-6e56-4c19-9edc-cf77f233ca69.png">


## w3c css チェック結果

- https://jigsaw.w3.org/css-validator/
- <img width="1810" alt="image" src="https://user-images.githubusercontent.com/99580997/160092780-c24fc0a0-a21b-421a-be0e-cedb9b71d552.png">


## portfolio url:

- https://c-0034.wtb.cfbx.jp/

## 参考にしたサイト

- CSS：ボタンホバー時に背景がスライドしたり領域を覆うアニメーションサンプル 10
- https://www.nxworld.net/10-css-hover-fill-animation.html
- Element button must not appear as a descendant?
- button 要素は、（a）要素の子孫として表示しなければいけません。
- https://tinyurl.com/ybyvujf3

## 更新履歴

- 2022/3/25 button 要素を a タグの子要素として作成したが、エラー解除せず。
- 2022/3/25 初版 作成完了(button 要素ではエラーになるので、div に切替て完成)

## 環境・使い方

- ダウンロードしたフォルダを開く。
- ターミナルを開き、 npm i とコマンドを入力する。
- node_modules と package-lock.json が生成されるのを確認する。
- 「 npx gulp 」とコマンドを入力すると動き出します。

## 備考

# Counter Vanilla

## このプロジェクトに関して
Reduxの簡単なサンプルです。  
Reactは使っていません。

## 実装
以下のプロジェクトを参考にしました。  
https://github.com/reactjs/redux/tree/master/examples/counter-vanilla

以下のReduxオブジェクトを実装しました。
- Reducer
- Store


1. incrementあるいはdecrementボタンをクリックするとdispatchをコールしてStoreにActionを送ります。
2. Actionに従いReducerはStateを返します。
3. Stateが変化するとrender()が実行されます。
4. subscribe()によってStateが変化したらrender()が呼び出されるようにします。
5. render()でStateを取得し手動でDOMを操作して値を直接書き換えます。

## 前提条件
特になし  
ブラウザーのみです。

## アプリケーションの起動の仕方
ブラウザーでindex.htmlを開いて下さい。

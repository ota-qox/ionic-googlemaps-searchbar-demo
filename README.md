# 検索バーからマップに移動した時キーボードが出てくる問題
* ブラウザ: Android版 Google Chrome
* OS: Android 12
* @angular/core: 15.0.0
* @angular/google-maps: 15.1.1
* @ionic/angular: 6.1.9

## 解決方法

マップの操作開始時にDOM内で現在フォーカスを持っている要素のキーボードフォーカスを取り除く

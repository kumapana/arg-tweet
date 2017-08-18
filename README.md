# arg-tweet

 This script can tweet by Python's command line args.

## Usage

### Settings
1. Get Twitter Access Token key.
2. Edit file "key.json"(Write your Access token key)

### Tweet
```
$ python tweet.py "<tweet text>"
```

## P.S.
### Convenient usage
 You can tweet easy by this way.
 
1. Write down your ~/.bashrc and Execution "source ~/.bashrc"
```
tweet () {
  python (include scriptfile and key.json foldar)/tweet.py "$@"
}
```

---

このスクリプトは、Pythonのコマンドライン引数からツイートできるスクリプトです。

## 使い方

### 初期設定
1. ツイッターのアクセストークンを取得して下さい。
2. key.jsonファイルに取得したアクセストークンを記入して下さい。

### ツイート
```
$ python tweet.py "<ツイートするテキスト>"
```

## 便利な使い方
こんな感じのことをすると便利に使えるかも？

1. ~/.bashrcに以下を追記して「source ~/.bashrc」を実行
```
tweet () {
  python (スクリプトファイルとkey.jsonを入れたフォルダ)/tweet.py "$@"
}
```

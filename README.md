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
 
1. Edit "path_to_key" in "tweet.py" to complete path to "key.json"
2. Write down your ~/.bashrc and Execution "source ~/.bashrc"
```
tweet () {
  python (include scriptfile and key.json foldar)/tweet.py "$@"
}
```

#### Tweet
```
$ tweet <tweet text>
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
1. 「tweet.py」の中の「path_to_key」の項目を「key.json」ファイルまでの完全なパスに書き換える
2. ~/.bashrcに以下を追記して「source ~/.bashrc」を実行
```
tweet () {
  python (スクリプトファイルとkey.jsonを入れたフォルダ)/tweet.py "$@"
}
```

### この場合のツイート方法
```
$ tweet <ツイートするテキスト>
```

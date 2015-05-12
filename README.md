# これはなんですか
ie公式サイト専用のhugoテーマです



# 環境構築
```
$ brew install hugo
$ git clone https://github.com/spf13/hugo
$ cd hugo
$ go get
$ hugo new site ie-site
$ cd ie-site
$ git clone https://github.com/328--/ie-theme.git themes
```

# 使い方

#### サイト確認
```
$ hugo server -D -t ie-theme (--watchオプションをつけるとlivereloadされる)
```

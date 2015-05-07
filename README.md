# これはなんですか
ie 専用のhugo theme



# 環境構築
```
brew install hugo
git clone https://github.com/spf13/hugo
cd hugo
go get
hugo new site ie-site
cd ie-site
git clone https://github.com/328--/ie-theme.git themes
hugo server -D -t ie-themes
```

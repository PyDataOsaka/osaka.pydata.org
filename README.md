# このウェブサイトソースコードのビルドと閲覧の仕方

```
docker run -it -p 4000:4000 ruby bash
cd
gem install bundler jekyll
git clone https://github.com/PyDataOsaka/osaka.pydata.org
cd osaka.pydata.org
bundle add webrick
bundle exec jekyll serve --host=0.0.0.0
```

最後にウェブブラウザで http://localhost:4000/ をopenします。

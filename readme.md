## 安裝指令
* 新增專案
hugo new site myblog

* 下載模板
git submodule add https://github.com/budparr/gohugo-theme-ananke.git themes/ananke

* 設定檔指定模板
echo 'theme = "ananke"' >> config.toml

* 新增文章
hugo new posts/my-first-post.md

* 執行
hugo server -D

* 新增一份草稿
hugo new drafts/my-drafts.md

* 風格網站
https://themes.gohugo.io/tags/blog/
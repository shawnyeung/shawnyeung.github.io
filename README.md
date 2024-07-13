## 如何更新

1. 直接在 Gemfile 中更新，比如将` gem "jekyll-theme-chirpy", "~> 3.2"` 直接改为 ·`gem "jekyll-theme-chirpy", "~> 4.0"`
2. 执行下列操作

```
bundle update jekyll-theme-chirpy
```

---



## 去掉右侧边栏

删除 ` /includes/trending-tags.html`  和 `/includes/update-list.html `两个文件中的 section 部分即可

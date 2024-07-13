## 如何更新

1. 直接在 Gemfile 中更新，比如将` gem "jekyll-theme-chirpy", "~> 3.2"` 直接改为 ·`gem "jekyll-theme-chirpy", "~> 4.0"`
2. 执行下列操作

```
bundle update jekyll-theme-chirpy
```

---

## 去掉右侧边栏

删除 ` /includes/trending-tags.html`  和 `/includes/update-list.html `两个文件中的 section 部分即可

---

## 更改左侧导航

`/_data/locales/zh-CN.yml` 

---

## Night主题修改

1. 设置-外观-外观文件夹-night.css
1. 引用段落的竖线颜色：

```text
blockquote {
    padding-left: 1.875rem;
    margin: 0 0 1.875rem 1.875rem;
    border-left: solid 2px #BEBEBE;
```

2. Inline code 的背景色引用段落的竖线颜色：

```text
pre,
code,
kbd,
tt,
var {
    font-size: 0.875em;
    font-family: Monaco, Consolas, "Andale Mono", "DejaVu Sans Mono", monospace;
    color: #F8F8FF;

}

code,
tt,
var {
    background: #696969
;
}

```

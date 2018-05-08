# skywalker

一款 material design 风格的响应式简约 Ghost 博客主题

基于 [flute/skywalker](https://github.com/flute/skywalker) 改进，在此表示感谢

[demo](http://www.fecoding.cn)

### 安装使用

1. 下载主题压缩包，上传至 Ghost 博客的 content/themes/skywalker 中，解压，重启 Ghost 系统，然后在后台设置启用主题即可
2. 也可以在 Ghost 博客的 content/themes/skywalker 目录下，执行 `git clone git@github.com:ChrisCindy/skywalker.git`，然后重启 Ghost 系统，然后在后台设置启用主题即可
3. 以下几处需要修改，以保证主题正常使用：
  - `page-archives-post.hbs` 中，请求博客数据时应将接口 url 更改为个人博客地址
  - `aside.hbs` 中，社交链接需要更新
  - `comments.hbs` 中，搜狐畅言评论系统的 appid 和 conf 参数需要修改，具体参见搜狐畅言官网文档
  - `footer.hbs` 中，底部网站信息需要更新

### 主题说明

* 适配移动端和 PC 端
* 新增 Ghost 博客文章归档页面
* 使用搜狐畅言作为评论插件，可自行替换
* 主题采用 flexbox 布局
* markdown 样式与 github 相同，代码高亮使用 highlight.js

### Plan to do

- [] 代码压缩处理
- [] 增加标签云页面
- [] 首页加载文章动画
- [] 延迟加载

持续更新中，欢迎使用。

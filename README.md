## 项目来源
本项目fork自 [rampatra/photography](https://github.com/rampatra/photography)

## 主要变更
- 修复了多个bug
- 进行了性能优化
- 更新至最新版 [Multiverse](https://html5up.net/multiverse) 主题

---

## 本地运行网站
1. `$ cd photography` - 进入项目目录
2. `$ bundle install` - 安装Ruby依赖
3. 修改 `_config.yml` 中的 `baseurl` 配置
4. `$ bundle exec jekyll serve` - 启动网站

## 构建网站
1. `$ cd photography` - 进入项目目录
2. `$ npm install` - 安装npm依赖
3. `$ gulp` - 压缩CSS/JS，调整图片尺寸等

注意：只有在修改图片、CSS样式等情况下才需要重新构建网站。

## 实用技巧

### 图片尺寸调整
本项目使用[npm](https://www.npmjs.com)和[gulp](http://gulpjs.com/)来自动化图片尺寸调整和缩略图生成：

1. Fork并克隆项目到本地
2. 进入项目目录 `$ cd photography`
3. 安装依赖 `$ npm install`
4. 将原始图片(JPG格式)放入`images`目录
5. 运行 `$ gulp resize` 自动调整图片尺寸并生成缩略图
6. 提交更改到GitHub

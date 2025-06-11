# Calvin666 个人网站

这是一个简洁、现代的个人网站模板，包含博客、照片和视频展示功能。网站采用响应式设计，可以在各种设备上良好显示。

## 文件结构

```
calvin666-personal-website/
  ├── index.html          # 主页
  ├── blog.html           # 博客页面
  ├── photos.html         # 照片页面
  ├── videos.html         # 视频页面
  ├── image-placeholders.html  # 图片占位符说明
  ├── css/
  │   └── style.css       # 样式文件
  ├── js/
  │   └── main.js         # JavaScript功能文件
  ├── img/                # 图片目录（需要自行添加图片）
  └── README.md           # 本说明文件
```

## 如何使用

### 1. 部署网站

#### 本地测试
1. 下载所有文件到您的计算机
2. 使用浏览器打开 `index.html` 文件即可查看网站

#### 在线部署
您可以将网站部署到任何静态网站托管服务，例如：
- GitHub Pages
- Netlify
- Vercel
- 阿里云/腾讯云等国内云服务商

部署步骤（以GitHub Pages为例）：
1. 在GitHub上创建一个新仓库，名称为 `calvin666.github.io`
2. 将所有文件上传到该仓库
3. 启用GitHub Pages功能
4. 网站将在 `https://calvin666.github.io` 上线

### 2. 添加图片

请参考 `image-placeholders.html` 文件，了解需要准备的图片列表和尺寸建议。您需要创建 `img` 目录并添加相应的图片。

在准备好实际图片之前，可以使用在线图片占位服务来测试网站布局：
- `https://picsum.photos/[宽度]/[高度]` 获取随机图片
- `https://via.placeholder.com/[宽度]x[高度]` 获取纯色占位图

### 3. 自定义内容

#### 修改个人信息
编辑 `index.html` 文件中的个人简介部分：
```html
<div class="about-text">
    <p>嗨，我是Calvin666！欢迎来到我的个人网站。</p>
    <p>这个空间是我分享思考、创作和生活的地方。我热爱探索新事物，记录美好瞬间，并与志同道合的朋友交流想法。</p>
    <p>在这里，你可以找到我的博客文章、照片集和视频作品。希望我的分享能为你带来一些启发或乐趣。</p>
</div>
```

#### 添加博客文章
编辑 `blog.html` 文件，按照现有格式添加新的博客文章：
```html
<article class="blog-card">
    <img src="img/your-image.jpg" alt="文章标题">
    <div class="blog-content">
        <div class="blog-meta">日期 | 分类</div>
        <h3>文章标题</h3>
        <p>文章摘要...</p>
        <a href="#" class="btn">阅读全文</a>
    </div>
</article>
```

#### 添加照片
编辑 `photos.html` 文件，按照现有格式添加新的照片：
```html
<a href="img/your-large-image.jpg" class="photo-item" data-lightbox="gallery" data-title="照片描述" data-category="分类">
    <img src="img/your-thumbnail.jpg" alt="照片描述">
</a>
```

#### 添加视频
编辑 `videos.html` 文件，按照现有格式添加新的视频：
```html
<div class="video-card">
    <div class="video-thumbnail">
        <img src="img/your-thumbnail.jpg" alt="视频标题">
        <div class="video-play">
            <i class="fas fa-play-circle"></i>
        </div>
    </div>
    <div class="video-content">
        <h3>视频标题</h3>
        <div class="video-meta">日期 | 时长</div>
        <p>视频描述...</p>
        <a href="#" class="btn">观看视频</a>
    </div>
</div>
```

### 4. 自定义样式

您可以通过编辑 `css/style.css` 文件来自定义网站的样式，包括颜色、字体、布局等。

## 未来功能扩展建议

当前版本是一个静态网站，如果您希望添加更多动态功能，可以考虑以下扩展：

1. **博客功能增强**
   - 添加文章详情页
   - 实现文章分类和标签功能
   - 添加评论系统（可使用Disqus等第三方服务）

2. **照片功能增强**
   - 添加照片相册功能
   - 实现照片上传功能（需要后端支持）
   - 添加照片分享功能

3. **视频功能增强**
   - 集成视频播放器
   - 支持视频上传（可使用YouTube或Bilibili等第三方服务）
   - 添加视频分类功能

4. **用户互动**
   - 添加留言板功能
   - 实现用户注册和登录系统（需要后端支持）
   - 添加内容点赞和收藏功能

5. **后端支持**
   - 使用Node.js、PHP或Python等搭建简单的后端
   - 添加数据库存储内容
   - 实现内容管理系统

## 技术栈

- HTML5
- CSS3
- JavaScript (ES6+)
- Font Awesome (图标)
- Lightbox2 (照片查看插件)

## 许可证

此模板仅供个人使用，请勿用于商业目的。

---

希望这个网站模板能够满足您的需求！如有任何问题或建议，欢迎联系我。
# toolkit-page
# 我的常用工具网站 (My Toolkit Websites)

这是一个简洁、美观的单页静态网站，用于整理和展示常用的工具网站链接。页面采用 Google 风格设计，响应式布局，并为在 Cloudflare Pages 上进行快速部署而优化。

### ✨ 主要特性

- **简洁设计**: 采用 Google 风格的卡片式布局，清晰地对工具进行分类。
    
- **响应式布局**: 在桌面和移动设备上均有出色的浏览体验。
    
- **轻量快速**: 使用原生 HTML 和 CSS，无任何外部框架，加载速度极快。
    
- **易于部署**: 单个 `index.html` 文件，可直接上传到 Cloudflare Pages 或任何静态网站托管平台。
    
- **方便定制**: 可以非常轻松地在 HTML 文件中添加或修改您自己的工具链接。
    

### 🚀 快速部署到 Cloudflare Pages

1. **下载代码**: 下载本项目中的 `index.html` 文件。
    
2. **登录 Cloudflare**: 前往您的 [Cloudflare 面板](https://dash.cloudflare.com/ "null")。
    
3. **创建 Pages 项目**:
    
    - 在左侧菜单进入 **Workers & Pages**。
        
    - 点击 **Create application** > **Pages** > **Upload assets**。
        
4. **上传和部署**:
    
    - 将 `index.html` 文件拖拽到上传区域。
        
    - 点击 **Deploy site** 完成部署。
        
5. **绑定域名** (可选): 部署成功后，在项目设置中绑定您的自定义域名。
    

### 🛠️ 如何定制

您可以直接编辑 `index.html` 文件来添加、修改或删除工具链接。

#### 1. 修改分类标题

找到 `<h2>` 标签并修改其内容：

```
<h2 class="card-title">IP 地址查询</h2>
```

#### 2. 添加或修改链接

在对应的卡片 (`<div class="tool-card">`) 内的 `<ul>` 列表中，复制或修改 `<li>` 标签即可。每个 `<li>` 代表一个工具链接。

- `<a>` 标签的 `href` 属性是工具的网址。
    
- `<a>` 标签内的文本是链接的名称。
    
- `<span class="description">` 内的文本是链接的简短描述。
    

**示例:**

```
<!-- 在 "IP 质量与安全检测" 卡片中添加一个新工具 -->
<div class="tool-card">
    <h2 class="card-title">IP 质量与安全检测</h2>
    <ul class="tool-list">
        <!-- ... 已有的链接 ... -->
        <li><a href="https://www.speedtest.net/" target="_blank" rel="noopener noreferrer">speedtest.net</a><span class="description">- 网速测试</span></li>
        <!-- 在这里添加您的新链接 -->
        <li><a href="https://new-tool-website.com" target="_blank" rel="noopener noreferrer">新工具网站</a><span class="description">- 这是一个新工具</span></li>
    </ul>
</div>
```

### 📸 页面预览
[示例网站](https://t.hotrue.cc)
<!DOCTYPE html>
<!-- 声明文档类型为HTML5 -->
<html lang="zh-CN">
<!-- lang="zh-CN" 表示页面语言为中文 -->
<head>
    <!-- 页面元信息 -->
    <meta charset="UTF-8">
    <!-- 字符编码：UTF-8（支持中文） -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- 适配手机/平板等移动端 -->
    <title>我的第一个 GitHub Pages</title>
    <!-- 浏览器标签页标题 -->
    <style>
        /* 简单的样式，让页面不那么单调 */
        body {
            font-family: "Microsoft YaHei", sans-serif; /* 字体 */
            max-width: 800px; /* 页面最大宽度 */
            margin: 0 auto; /* 居中显示 */
            padding: 20px; /* 内边距 */
            background-color: #f5f5f5; /* 背景色 */
            color: #333; /* 文字颜色 */
        }
        .header {
            text-align: center; /* 文字居中 */
            padding: 20px 0;
            border-bottom: 1px solid #ddd; /* 底部边框 */
        }
        .content {
            margin-top: 20px;
            line-height: 1.6; /* 行高，更易读 */
        }
        a {
            color: #0066cc; /* 链接颜色 */
            text-decoration: none; /* 去掉下划线 */
        }
        a:hover {
            text-decoration: underline; /* 鼠标悬浮加下划线 */
        }
        .footer {
            margin-top: 40px;
            text-align: center;
            color: #666;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <!-- 头部区域 -->
    <div class="header">
        <h1>👋 你好，我是我的 GitHub Pages！</h1>
        <p>这是我的第一个 GitHub Pages 页面 😜</p>
    </div>

    <!-- 内容区域 -->
    <div class="content">
        <h2>关于我</h2>
        <p>我正在学习 GitHub Pages，这个页面是用纯 HTML 写的～</p>
        
        <h2>我的链接</h2>
        <ul>
            <li>我的 GitHub 仓库：<a href="https://github.com/liuxuyang08/Kerrigen" target="_blank">Kerrigen 仓库</a></li>
            <!-- 替换成你的仓库链接，target="_blank" 新标签页打开 -->
            <li>随便加个趣味链接：<a href="https://github.com/" target="_blank">GitHub 官网</a></li>
        </ul>

        <h2>放张图片玩玩（可选）</h2>
        <!-- 可以替换成你自己的图片链接，也可以用 GitHub 仓库里的图片 -->
        <img src="https://picsum.photos/400/200" alt="随机图片" style="max-width: 100%; border-radius: 8px;">
    </div>

    <!-- 页脚区域 -->
    <div class="footer">
        <p>© 2025 我的第一个 GitHub Pages | 新手练习ing</p>
    </div>
</body>
</html>

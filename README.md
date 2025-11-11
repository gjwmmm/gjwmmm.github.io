# 个人简历网站

这是一个基于HTML、CSS和JavaScript构建的个人简历网站，使用Tailwind CSS进行样式设计，Font Awesome提供图标支持，AOS库实现滚动动画效果。网站采用响应式设计，在桌面端和移动端都能提供良好的用户体验。

## 功能特点

- **简历内容展示**：包含个人信息、教育背景、工作经历、技能专长等模块
- **响应式设计**：适配桌面端和移动端不同设备
- **GitHub Pages部署**：通过GitHub Pages免费托管，生成可分享的链接
- **PDF下载功能**：提供一键下载PDF版本简历的功能
- **项目展示**：展示个人项目作品，支持分类筛选和详情查看
- **联系表单**：提供在线联系功能

## 技术栈

- HTML5
- CSS3 (Tailwind CSS v3)
- JavaScript (ES6+)
- Font Awesome 4.7.0
- AOS Animation Library 2.3.4

## 如何部署到GitHub Pages

1. **创建GitHub仓库**
   - 在GitHub上创建一个新的仓库，命名为`your-username.github.io`（将`your-username`替换为你的GitHub用户名）

2. **克隆仓库到本地**
   ```bash
   git clone https://github.com/your-username/your-username.github.io.git
   cd your-username.github.io
   ```

3. **添加项目文件**
   - 将本项目的所有文件复制到克隆的仓库中

4. **提交并推送更改**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

5. **启用GitHub Pages**
   - 进入GitHub仓库的Settings页面
   - 向下滚动到GitHub Pages部分
   - 在Source下拉菜单中选择`main`分支
   - 点击Save按钮
   - 几分钟后，你的网站将可以通过`https://your-username.github.io`访问

## 自定义内容

1. **修改个人信息**
   - 打开`index.html`文件
   - 找到相关部分，替换为你自己的信息，如姓名、职位、联系方式等

2. **更新工作经历和教育背景**
   - 在`index.html`文件中，找到工作经历和教育背景部分
   - 修改或添加相应的内容块

3. **调整技能水平**
   - 在技能部分，修改`data-width`属性值来调整技能水平的百分比

4. **添加项目作品**
   - 在项目部分，添加或修改项目卡片
   - 确保为每个项目添加相应的详情内容

5. **更换头像**
   - 将你的头像图片上传到`assets/images`目录
   - 在`index.html`中更新头像图片的路径

## 本地预览

在部署到GitHub Pages之前，你可以在本地预览网站：

1. 使用任何现代浏览器打开`index.html`文件
2. 或者使用本地服务器，如Python的内置HTTP服务器：
   ```bash
   python -m http.server
   ```
   然后在浏览器中访问`http://localhost:8000`

## 注意事项

- 确保所有图片资源都已正确链接
- 如果需要添加PDF下载功能，请将你的PDF简历文件添加到项目中，并更新下载链接
- 定期更新内容，保持简历的时效性
- 考虑添加Google Analytics来跟踪网站访问情况

## 许可证

MIT License
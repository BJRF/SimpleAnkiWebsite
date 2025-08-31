# 简忆Anki - GitHub Pages 网站

这是简忆Anki应用的官方网站，包含应用介绍、隐私政策和技术支持页面。

## 📁 文件结构

```
SimpleAnkiWebsite/
├── index.html          # 主页面
├── privacy.html        # 隐私政策页面
├── styles.css          # 样式文件
└── README.md           # 说明文档
```

## 🚀 GitHub Pages 设置步骤

### 1. 推送代码到GitHub

```bash
# 初始化Git仓库
git init

# 添加所有文件
git add .

# 提交代码
git commit -m "Initial commit: Add SimpleAnki website"

# 添加远程仓库（替换为您的仓库URL）
git remote add origin https://github.com/YOUR_USERNAME/SimpleAnkiWebsite.git

# 推送到GitHub
git push -u origin main
```

### 2. 启用GitHub Pages

1. 打开您的GitHub仓库页面
2. 点击 **Settings** 选项卡
3. 在左侧菜单中找到 **Pages**
4. 在 **Source** 部分选择 **Deploy from a branch**
5. 选择 **main** 分支和 **/ (root)** 文件夹
6. 点击 **Save**

### 3. 访问网站

设置完成后，您的网站将在以下地址可用：
```
https://YOUR_USERNAME.github.io/SimpleAnkiWebsite/
```

GitHub Pages 通常需要几分钟时间来部署，请耐心等待。

## 📱 网站功能

### 主页 (index.html)
- 应用介绍和功能特色
- 现代化的响应式设计
- 艾宾浩斯遗忘曲线算法说明
- 使用场景展示

### 隐私政策 (privacy.html)
- 完整的隐私政策条款
- 数据收集和使用说明
- 用户权利和联系方式
- 符合法律法规要求



## 🎨 设计特色

- **现代化UI**：采用渐变色和卡片式设计
- **响应式布局**：完美适配桌面和移动设备
- **优雅动效**：悬停效果和平滑过渡
- **易于导航**：清晰的页面结构和导航

## 🔧 自定义修改

### 更新联系信息
在所有HTML文件中搜索并替换：
- `support@simpleanki.com` → 您的实际邮箱
- `privacy@simpleanki.com` → 您的隐私政策邮箱

### 修改应用下载链接
在 `index.html` 中找到下载按钮部分，更新为实际的App Store链接。

### 自定义样式
编辑 `styles.css` 文件来修改：
- 颜色主题
- 字体样式
- 布局结构
- 动画效果

## 📝 维护建议

1. **定期更新**：根据应用更新同步网站内容
2. **监控访问**：使用Google Analytics等工具跟踪访问情况
3. **SEO优化**：添加meta标签和结构化数据
4. **性能优化**：压缩图片和CSS文件

## 🌐 域名绑定（可选）

如果您有自定义域名，可以：

1. 在仓库根目录创建 `CNAME` 文件
2. 在文件中写入您的域名（如：`www.simpleanki.com`）
3. 在域名DNS设置中添加CNAME记录指向 `YOUR_USERNAME.github.io`

## 📞 技术支持

如果在设置过程中遇到问题，请：

1. 检查GitHub Pages设置是否正确
2. 确认所有文件都已正确推送
3. 查看GitHub Actions中的部署日志
4. 参考GitHub Pages官方文档

---

**简忆Anki** - 让记忆更科学，让学习更高效 🧠✨

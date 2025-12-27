# Embedded Linux Industry Chain Visualization

嵌入式Linux产业链可视化教学资源

## 🌐 在线访问

访问地址（设置GitHub Pages后）：`https://your-username.github.io/embedded-linux-resources/`

## 📁 项目结构

```
embedded-linux-resources/
├── index.html                          # 主页（产业链图表）
├── embedded_linux_industry.html        # 嵌入式Linux产业链讲解
├── README.md                           # 项目说明
└── (future HTML files)                 # 未来添加的其他HTML文件
```

## 🚀 如何部署到GitHub Pages

### 方法1：通过GitHub网页界面（推荐新手）

1. **创建GitHub账号**（如果还没有）
   - 访问 https://github.com
   - 点击 "Sign up" 注册账号

2. **创建新仓库**
   - 登录GitHub后，点击右上角 "+" → "New repository"
   - Repository name: `embedded-linux-resources`
   - 设置为 Public（公开）
   - 勾选 "Add a README file"
   - 点击 "Create repository"

3. **上传文件**
   - 在仓库页面，点击 "Add file" → "Upload files"
   - 将以下文件拖拽上传：
     * `embedded_linux_industry.html`
     * `index.html`（如果有的话）
   - 点击 "Commit changes"

4. **启用GitHub Pages**
   - 在仓库页面，点击 "Settings"
   - 在左侧菜单找到 "Pages"
   - 在 "Source" 下拉菜单选择 "main" 分支
   - 点击 "Save"
   - 等待几分钟后，页面会显示你的网站地址

5. **访问你的网站**
   - 地址格式：`https://your-username.github.io/embedded-linux-resources/embedded_linux_industry.html`

### 方法2：通过Git命令行（推荐有经验的用户）

```bash
# 1. 在本地创建项目文件夹
mkdir embedded-linux-resources
cd embedded-linux-resources

# 2. 初始化Git仓库
git init

# 3. 复制所有HTML文件到这个文件夹

# 4. 添加文件到Git
git add .
git commit -m "Initial commit: Add embedded Linux industry chain visualization"

# 5. 连接到GitHub仓库（先在GitHub创建仓库）
git remote add origin https://github.com/your-username/embedded-linux-resources.git

# 6. 推送到GitHub
git branch -M main
git push -u origin main

# 7. 在GitHub仓库设置中启用GitHub Pages
```

## 📝 添加更多HTML文件

将来要添加新的HTML文件时：

### 通过网页界面：
1. 在GitHub仓库页面，点击 "Add file" → "Upload files"
2. 上传新的HTML文件
3. 提交更改

### 通过Git命令：
```bash
# 1. 将新HTML文件复制到项目文件夹
# 2. 添加并提交
git add new-file.html
git commit -m "Add new visualization"
git push
```

## 🔗 分享链接

文件访问格式：
- 主页：`https://your-username.github.io/embedded-linux-resources/`
- 产业链图表：`https://your-username.github.io/embedded-linux-resources/embedded_linux_industry.html`
- 其他文件：`https://your-username.github.io/embedded-linux-resources/filename.html`

## 📱 移动端访问

所有页面都支持移动端访问，可以直接在手机浏览器中打开链接。

## 🎓 教学使用

这些可视化资源适合：
- 大学嵌入式系统课程教学
- 技术分享会议
- 新员工培训
- 在线学习资源

## 📧 联系方式

如有问题或建议，欢迎联系。

---

**创建者**: 26年嵌入式Linux开发经验  
**更新日期**: 2024年12月

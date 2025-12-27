# GitHub Pages 部署指南（详细步骤）

## 📝 准备工作

需要的文件：
- ✅ index.html（主页）
- ✅ embedded_linux_industry.html（产业链图表）
- ✅ README.md（说明文档）

## 🚀 方法一：通过网页界面（最简单，推荐）

### 第1步：创建GitHub账号
1. 打开浏览器，访问：https://github.com
2. 点击右上角 "Sign up"（注册）
3. 填写邮箱、密码、用户名
4. 验证邮箱
5. 登录GitHub

### 第2步：创建新仓库
1. 登录后，点击右上角 "+" 号
2. 选择 "New repository"（新建仓库）
3. 填写信息：
   - Repository name（仓库名）：`embedded-linux-resources`
   - Description（描述）：`嵌入式Linux教学资源`
   - 选择 **Public**（公开）
   - ✅ 勾选 "Add a README file"
4. 点击 "Create repository"（创建仓库）

### 第3步：上传HTML文件
1. 在仓库主页，点击 "Add file" → "Upload files"
2. 把以下文件拖拽到页面中：
   - `index.html`
   - `embedded_linux_industry.html`
3. 在下方填写提交信息：`Add initial HTML files`
4. 点击 "Commit changes"（提交更改）

### 第4步：启用GitHub Pages
1. 点击仓库顶部的 "Settings"（设置）
2. 在左侧菜单找到 "Pages"
3. 在 "Branch" 下拉菜单中：
   - 选择 `main` 分支
   - 文件夹选择 `/ (root)`
4. 点击 "Save"（保存）
5. 等待1-2分钟

### 第5步：访问你的网站
1. 刷新Settings → Pages页面
2. 会显示：✅ Your site is live at `https://your-username.github.io/embedded-linux-resources/`
3. 点击链接访问！

**你的网站地址：**
- 主页：`https://your-username.github.io/embedded-linux-resources/`
- 产业链图表：`https://your-username.github.io/embedded-linux-resources/embedded_linux_industry.html`

---

## 💻 方法二：使用Git命令行（适合熟悉命令行的用户）

### 前置条件
- 安装Git：https://git-scm.com/downloads
- 有GitHub账号

### 操作步骤

```bash
# 1. 创建项目文件夹
mkdir embedded-linux-resources
cd embedded-linux-resources

# 2. 复制HTML文件到这个文件夹
# （将index.html和embedded_linux_industry.html复制进来）

# 3. 初始化Git仓库
git init

# 4. 添加所有文件
git add .

# 5. 提交
git commit -m "Initial commit: Add embedded Linux resources"

# 6. 在GitHub创建仓库后，连接远程仓库
git remote add origin https://github.com/你的用户名/embedded-linux-resources.git

# 7. 推送到GitHub
git branch -M main
git push -u origin main
```

### 启用GitHub Pages
1. 访问你的仓库：`https://github.com/你的用户名/embedded-linux-resources`
2. 点击 "Settings" → "Pages"
3. Source选择 `main` 分支
4. 点击 "Save"

---

## 📱 添加新的HTML文件

### 通过网页上传：
1. 在仓库页面，点击 "Add file" → "Upload files"
2. 拖拽新的HTML文件
3. 点击 "Commit changes"
4. 新文件会自动部署，访问地址：
   `https://your-username.github.io/embedded-linux-resources/新文件名.html`

### 通过Git命令：
```bash
# 1. 将新HTML文件复制到项目文件夹

# 2. 添加并提交
git add 新文件名.html
git commit -m "Add new resource"
git push

# 3. 等待1-2分钟自动部署
```

---

## 🔗 分享链接

### 生成短链接（可选）
你可以使用短链接服务：
- bit.ly
- tinyurl.com

把你的GitHub Pages链接缩短后分享。

### 生成二维码（可选）
使用在线工具生成二维码：
- https://www.qrcode-monkey.com/
- 输入你的网站地址
- 生成二维码图片
- 打印或分享

---

## ✅ 检查清单

部署完成后，确认：
- [ ] 可以访问主页：`https://your-username.github.io/embedded-linux-resources/`
- [ ] 可以访问产业链图表
- [ ] 页面在手机上也能正常显示
- [ ] 所有交互功能正常工作

---

## ❓ 常见问题

### Q1: 显示404错误
**A:** 等待2-3分钟，GitHub Pages需要时间部署

### Q2: 页面样式不对
**A:** 检查文件是否正确上传，确保文件名没有错误

### Q3: 如何更新内容？
**A:** 
- 网页界面：直接在GitHub编辑文件或重新上传
- Git命令：修改本地文件后 `git add` → `git commit` → `git push`

### Q4: 可以使用自定义域名吗？
**A:** 可以！在Settings → Pages → Custom domain 中设置

### Q5: 如何删除仓库？
**A:** Settings → 滚动到底部 → Danger Zone → Delete this repository

---

## 📧 需要帮助？

如遇到问题：
1. 查看GitHub Pages官方文档：https://docs.github.com/en/pages
2. 在GitHub仓库中创建Issue
3. 搜索相关教程

---

**祝部署顺利！🎉**

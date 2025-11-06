# 商文学的个人简历网站

这是一个响应式的个人简历网站，使用现代前端技术栈构建，支持深色/浅色模式切换和PDF导出功能。

## 🌐 在线访问

**简历地址：** https://pleasureswx123.github.io/my-resume/

## 功能特点

- **响应式设计**：适配各种设备尺寸，从手机到桌面设备
- **深色/浅色模式**：根据用户偏好自动切换或手动切换主题模式
- **PDF导出**：一键将简历导出为PDF文件
- **丰富的视觉效果**：动画、卡片悬停效果和渐变色
- **打印优化**：针对打印场景优化了页面样式

## 技术栈

- **HTML5** 
- **CSS3** (Tailwind CSS框架)
- **JavaScript** (原生JS)
- **html2pdf.js** (用于PDF生成)
- **Font Awesome** (图标库)
- **Google Fonts** (字体)

## 🚀 部署到 GitHub Pages

### 步骤一：创建 GitHub 仓库

1. 登录 GitHub，访问 https://github.com/new
2. 创建新仓库：
   - 仓库名称：`my-resume`（或任意名称）
   - 设置为 Public（GitHub Pages 免费版需要公开仓库）
   - **不要**勾选初始化 README、.gitignore 或 license（因为本地已有文件）

### 步骤二：推送代码到 GitHub

在项目目录下执行以下命令：

```bash
# 初始化 git 仓库（如果还没有）
git init

# 添加所有文件
git add .

# 提交更改
git commit -m "Initial commit: 简历网站"

# 添加远程仓库（请将 YOUR_USERNAME 替换为你的 GitHub 用户名）
git remote add origin https://github.com/pleasureswx123/my-resume.git

# 推送到 GitHub
git branch -M main
git push -u origin main
```

### 步骤三：启用 GitHub Pages

1. 进入你的 GitHub 仓库页面
2. 点击 **Settings**（设置）标签
3. 在左侧菜单中找到 **Pages** 选项
4. 在 **Source** 部分：
   - 选择 **Deploy from a branch**（从分支部署）
   - Branch（分支）选择 **main**
   - Folder（文件夹）选择 **/ (root)**（根目录）
5. 点击 **Save**（保存）

### 步骤四：访问你的在线简历

等待几分钟后（通常 1-2 分钟），你的简历就可以通过以下地址访问：

**https://pleasureswx123.github.io/my-resume/**

> ⚠️ 注意：如果仓库名称不是 `my-resume`，请将 URL 中的 `my-resume` 替换为你的实际仓库名称。

### 后续更新

修改简历内容后，只需要：

```bash
git add .
git commit -m "更新简历内容"
git push
```

GitHub Pages 会自动重新部署，几分钟后更新就会生效。

## 使用方法

### 本地运行

1. 克隆仓库或下载源码到本地
2. 直接在浏览器中打开`index.html`文件即可查看简历

### 自定义修改

如需修改简历内容：

1. 打开`index.html`文件
2. 修改相应部分的HTML内容，包括个人信息、工作经历、教育背景等
3. 保存文件并刷新浏览器查看效果
4. 使用 git 提交并推送更改到 GitHub

### PDF导出功能

点击页面右上角的下载图标即可将当前简历导出为PDF文件。导出过程会临时切换到浅色模式以获得最佳的打印效果。

## 项目结构

```
.
├── README.md          # 项目说明文档
├── index.html         # 主HTML文件（GitHub Pages 入口）
├── .nojekyll          # GitHub Pages 配置文件
├── img/               # 图片资源文件夹
│   └── photo.jpg      # 个人照片
└── [其他文件]          # 其他资源文件
```

## 浏览器兼容性

- Chrome (推荐)
- Firefox
- Safari
- Edge

## 许可证

MIT 
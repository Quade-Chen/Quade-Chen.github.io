# 个人简历网页

简洁大气的单页个人简历网站，支持响应式布局、深色模式、滚动动画等交互效果，可直接部署到 GitHub Pages。

## 快速部署

### 1. 创建 GitHub 仓库
- 仓库名必须为：`你的用户名.github.io`（例如 `Quade-Chen.github.io`）
- 权限设置为 Public

### 2. 上传文件
将本目录下的 `index.html` 和 `README.md` 上传到仓库根目录。

### 3. 开启 GitHub Pages
1. 进入仓库 Settings → Pages
2. Source 选择 `Deploy from a branch`
3. Branch 选择 `main` 分支，目录选择 `/ (root)`
4. 点击 Save，等待 1 分钟即可访问

访问地址：`https://你的用户名.github.io`

## 自定义修改

### 修改个人信息
直接编辑 `index.html` 文件，搜索对应文字替换即可：
- 姓名、职位、个人简介
- 技能标签、项目描述、工作经历
- 底部联系方式（GitHub、邮箱、电话）

### 修改主题色
搜索 `primary: '#165DFF'`，替换色值即可更换全局主色调。

### 增加内容
- 项目卡片：复制 `.project-card` 整块代码，修改对应内容
- 技能标签：复制 `<span class="px-3 py-1...">` 标签格式添加

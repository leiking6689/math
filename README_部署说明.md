# 绝对值化简互动课 · GitHub Pages 部署说明

包内文件：
- `index.html` —— 互动课网页本体（单文件，无外部依赖，手机/电脑浏览器均可直接打开）
- `.nojekyll` —— 空文件，告诉 GitHub 不要处理文件，原样发布（不要删）
- `README_部署说明.md` —— 本说明

---

## 一、网页版操作（最简单，全程在浏览器里，约 5 分钟）

### 第 1 步：注册/登录 GitHub
打开 https://github.com ，注册一个账号（已有账号直接登录）。

### 第 2 步：新建仓库
1. 右上角 **+** → **New repository**
2. Repository name 填：`abs-value-lesson`（或任何你喜欢的英文名）
3. 选择 **Public**（公开，免费版必须公开才能用 Pages）
4. 勾选 **Add a README file**
5. 点 **Create repository**

### 第 3 步：上传文件
1. 在仓库页面点 **uploading an existing file**（或 Add file → Upload files）
2. 把包里的 **`index.html` 和 `.nojekyll` 两个文件**拖进去
   - ⚠️ `.nojekyll` 是隐藏文件（以点开头），Windows 可能不显示。拖入时把文件夹里"显示隐藏文件"打开；实在找不到也没关系，本网页不依赖它，可以不传
3. 页面底部点 **Commit changes**

### 第 4 步：开启 Pages
1. 仓库顶部点 **Settings** → 左侧菜单 **Pages**
2. Source 选 **Deploy from a branch**
3. Branch 选 **main**，文件夹选 **/(root)**，点 **Save**
4. 等 1~2 分钟，刷新页面，顶部会出现链接：
   **https://你的用户名.github.io/abs-value-lesson/**

✅ 打开这个链接就是互动课，可以直接发给学生、贴进微信/钉钉/飞书。

---

## 二、以后想更新内容怎么办

在仓库里点 `index.html` → 右上角铅笔图标（编辑）→ 删掉旧内容、粘贴新内容 → Commit changes，Pages 会自动更新（约 1 分钟生效）。

---

## 三、常见问题

| 问题 | 解决 |
| --- | --- |
| 打开链接显示 404 | 刚部署需等 1-2 分钟；确认 Pages 设置里 Branch 选的是 main、文件夹是 /(root) |
| 页面是英文/空白 | 确认上传的文件名是 `index.html`（全小写），GitHub 默认只认这个名字做首页 |
| 想换更短的网址 | 仓库命名为 `你的用户名.github.io`，则访问地址直接是 `https://你的用户名.github.io/` |
| 手机上传找不到 .nojekyll | 可忽略，只传 index.html 也能正常工作 |

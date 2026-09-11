# 有理数专题互动课 · GitHub Pages 部署包

包内文件（两个网页通过顶部"专题导引"条互相跳转，请保持在同一目录）：

| 文件 | 内容 |
| --- | --- |
| `jueduizhi-huajian.html` | 专题 1：绝对值化简的分类讨论思想（零点分段五步法、多绝对值分段最小值、带范围化简、4 关闯关、错题医院） |
| `shu-de-bijiao.html` | 专题 2：数的大小比较四大方法（特殊值法 / 测试点法 / 作差法 / 作商法、4 关闯关、错题医院） |
| `.nojekyll` | 空文件，让 GitHub 原样发布（不要删） |
| `README_部署说明.md` | 本说明 |

## 部署步骤（约 5 分钟，全程浏览器操作）

1. 登录 https://github.com → 右上角 **+** → **New repository**
2. 仓库名填 `math-topics`（或任意英文名），选 **Public**，勾选 **Add a README file**，点 **Create repository**
3. 点 **uploading an existing file**，把解压出的 **3 个文件**（两个 .html + .nojekyll；README 传不传都行）拖进去 → **Commit changes**
4. 仓库 **Settings → Pages**，Source 选 **Deploy from a branch**，Branch 选 **main / (root)** → **Save**
5. 等 1~2 分钟，访问：
   - 专题1：https://你的用户名.github.io/math-topics/jueduizhi-huajian.html
   - 专题2：https://你的用户名.github.io/math-topics/shu-de-bijiao.html

⚠️ 注意：两个 html 文件名不要改（导引条靠文件名互跳）；打开专题 1 即可通过顶部导引条进入专题 2。

## 更新内容
重新上传同名文件覆盖即可，Pages 约 1 分钟自动更新。

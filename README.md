# Kailyu Ye · Academic Homepage

基于 HTML 和 CSS 的个人学术主页，可直接部署到 GitHub Pages，无需安装依赖或构建。

## 在 GitHub 上发布

1. 登录 GitHub，新建名为 `yekailv.github.io` 的仓库。使用 GitHub Free 时选择 Public。
2. 将本项目的文件上传至仓库根目录，确保首页文件名为 `index.html`。不要只上传 ZIP 压缩包。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment → Source** 选择 **Deploy from a branch**。
5. 分支选择 **main**，目录选择 **/(root)**，点击 **Save**。
6. 等待部署成功，访问 `https://yekailv.github.io/`。

也可使用其他仓库名，网址将为 `https://yekailv.github.io/仓库名/`。本站使用相对资源路径，两种地址均适用。

## 文件与维护

| 文件 | 用途 |
| --- | --- |
| `index.html` | 个人简介、研究经历、教育、荣誉、服务与链接 |
| `styles.css` | 配色、桌面与手机布局 |
| `favicon.svg` | KY 字母图标 |
| `Kailyu_Ye_CV.pdf` | 公开版简历，已移除手机号，保留邮箱 |
| `.nojekyll` | 让 GitHub Pages 直接发布静态文件 |

修改相应文件并提交到 main 分支后，GitHub Pages 会重新发布。照片尚未提供，因此主页使用 KY 字母标识。

公开版 PDF 已移除手机号并保留邮箱。请仅上传本目录中的公开版简历，勿上传原始版本。

## 本地预览

直接打开 `index.html` 即可。也可在目录内运行 `python -m http.server 8000`，然后访问 `http://localhost:8000`。

## 技术说明

此项目保留已制作的个人主页，不依赖 Jekyll 或 AcademicPages，也不需要 Sites 托管配置。


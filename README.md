# OK KARD 会员展示页

域名：`https://okkard.club/`。状态提示：**敬请期待**。

原生 HTML / CSS 页面，无需安装依赖或构建。正式 Logo 原图保存在 `assets/okkard-logo.jpg`，通过 CSS 调整展示区域，未修改原文件。

## 本地预览

在项目目录运行：

```powershell
python -m http.server 5188 --bind 127.0.0.1
```

打开 `http://127.0.0.1:5188/`。

## 部署

将 `index.html`、`styles.css` 和 `assets` 文件夹上传到网站根目录即可。将 `okkard.club` 绑定至实际托管服务并配置 DNS 和 HTTPS。本项目中的域名及 canonical 配置不会自动完成域名解析或上线。

当前为展示占位页，无会员登录或后台接口。

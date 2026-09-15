# WEEKEND GO · GitHub Pages 部署与更新说明

## 固定提交链接

https://zengheng9662.github.io/weekend-go/

只要仓库继续使用 `zengheng9662/weekend-go`，这个地址就可以保持不变。以后更新代码只会更新页面内容，不会改变提交链接。

## 仓库文件

```text
weekend-go/
├─ index.html       # 网站主页面
├─ favicon.svg      # 浏览器图标
├─ README.md        # 产品说明
├─ DEPLOYMENT.md    # 部署与更新说明
└─ .nojekyll        # 让 GitHub Pages 直接按静态文件发布
```

## 首次开启 GitHub Pages

如果访问固定链接暂时出现 404：

1. 打开 GitHub 仓库 `weekend-go`。
2. 进入 **Settings → Pages**。
3. 在 **Build and deployment** 中选择 **Deploy from a branch**。
4. Branch 选择 **main**，目录选择 **/(root)**。
5. 保存。
6. 等 GitHub Pages 完成部署后，重新打开固定链接。

## 以后用 GitHub Desktop 更新

1. 在 GitHub Desktop 打开本地 `weekend-go` 仓库。
2. 将新版文件覆盖到仓库根目录，务必保留文件名 `index.html`。
3. 在 GitHub Desktop 中填写 Summary，例如 `Update WEEKEND GO prototype`。
4. 点击 **Commit to main**。
5. 点击 **Push origin**。
6. 仍然访问同一个链接：`https://zengheng9662.github.io/weekend-go/`。

## 提交前检查

- 仓库 Visibility 为 **Public**。
- GitHub Pages 来源为 **main / (root)**。
- 首页文件名必须是 `index.html`。
- 用无痕窗口打开线上链接，确认无需登录即可访问。
- 电脑端和手机端各检查一次。
- 不要重命名或删除 `weekend-go` 仓库，否则固定 URL 会改变。

## 数据说明

目前天气、活动和地图位置属于产品演示数据。它们用于表达推荐逻辑，不代表实时活动信息。正式产品可继续接入实时天气、地图和本地活动服务。

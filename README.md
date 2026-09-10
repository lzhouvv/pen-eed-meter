# PEN EED Flash Meter

这是一个无需构建、无需服务器的 GitHub Pages 静态网站。

## 发布到 GitHub Pages

1. 在 GitHub 新建一个公开仓库，例如 `pen-eed-meter`。
2. 上传本目录内的全部文件，保持文件名和层级不变。
3. 在仓库打开 **Settings → Pages**。
4. 将 **Build and deployment** 设为 **Deploy from a branch**，选择 `main` 分支和 `/(root)`，然后保存。
5. 等待 GitHub 生成站点地址，通常为 `https://你的用户名.github.io/pen-eed-meter/`。在手机上从此 HTTPS 地址打开，并允许“相机”权限。

`index.html` 会自动进入主页面。不要通过手机本地文件或 `file://` 地址打开；这两种方式通常不能使用摄像头。

## 浏览器说明

- Android Chrome 通常可使用取景和亮度读数；支持 `FaceDetector` 时会尝试中央人脸距离粗估。
- iPhone Safari 可以使用摄像头和手动距离计算，但目前不支持网页标准的 FaceDetector 自动估距。
- 网页无法从普通摄像头取得可靠的真实距离；自动估算仅供参考，闪光曝光请优先按实测距离校正。

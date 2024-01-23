# ArcadeLinkage.UI

街机游戏录制系统UI

## 下载

123盘: `https://www.123pan.com/s/VZ3tVv-a1Sl3.html`

提取码: `alls`

## 配置

路径: `%userprofile%\AppData\LocalLow\DeltaGames\ALLS_UI\config.json`

示例格式:
```json
{
"QiniuAk":"",
"QiniuSk":"",
"FileUrl":"",
"BucketName":"",
"Qth":-1
}
```

`QiniuAk`,`QiniuSk`,`FileUrl`,`BucketName` 用于将 OBS 录制的视频上传至七牛云OSS

`Qth` 用于在 App 中标识拍摄机厅，可在此处开启 Issue 将机厅添加到数据库中，也可以保持 `-1` 在 App 中显示 “未知”

OBS Studio 本身没有可配置的地方（忘了加了），需要在 `OBS Studio > 工具栏 > 工具 > WebSocket服务器设置` 中开启WebSocket服务器 / 关闭鉴权 / 端口4455

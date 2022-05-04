# 百度贴吧自动签到Github Action版

## 今日签到状态 

![Baidu Tieba Auto Sign](https://img.shields.io/badge/Baidu%20Tieba%20Auto%20Sign-MeuiCat-green?logo=github&style=flat)

## 使用说明

1. Fork 本仓库，然后点击你的仓库右上角的 Settings，找到 Secrets 这一项，添加一个库秘密变量
其中 `BDUSS` 存放你的 BDUSS。支持同时添加多个帐户，BDUSS 之间用 `#` 隔开即可

2. 设置好环境变量后点击你的仓库上方的 `Actions` 选项，确认在 Fork 的仓库上启用 GitHub Actions

3. 至此自动签到就搭建完毕了，可以再次点击`Actions`查看工作记录
如果有`Baidu Tieba Auto Sign`则说明workflow创建成功了

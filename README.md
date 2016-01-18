## MAC 馒头地球

## 安装说明

#### 现在脚本中是只设置第二桌面的背景，自定义请修改`earth.scpt`文件

1. 直接下载或克隆此代码仓库
2. 双击运行里面的 `install`文件
3. 查看桌面，壁纸更换成功
4. 调整比例，打开 系统偏好设置 －》 桌面与屏幕保护程序 －》调整成类似下图

![](demo.png)

## 卸载说明

1. 打开终端
2. 运行下面的命令

```
launchctl unload ~/Library/LaunchAgents/ooo.oxo.apps.earth.launchctl.plist
rm ~/Library/LaunchAgents/ooo.oxo.apps.earth.launchctl.plist
rm -rf ~/.mantou_earth
```

或者双击运行`uninstall`文件


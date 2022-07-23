# myThanox
自用的 [Thanox](https://github.com/Tornaco/Thanox) 情景模式


* [自动打开/关闭GPS](/../main/json/AutoOpenCloseGPS.json?raw=true)
  - [x] 包名配置到全局变量autoGPS
  - [x] 应用到前台时打开GPS
  - [x] 应用终止，或不存在任务卡片时关闭GPS
  - [ ] 如果需要应用不在前台立刻关闭GPS，将`包名.closeGPS`配置到变量里


* [自动隐藏任务卡片](/../main/json/HideTaskWhenBackground.json?raw=true)
  - [x] 包名配置到全局变量hideTaskApps
  - [x] 从应用切到桌面（桌面包名需要包含`launcher`）时隐藏卡片
  - [ ] 如果需要应用不在前台时立刻隐藏卡片，将`包名.hideTask`配置到变量里
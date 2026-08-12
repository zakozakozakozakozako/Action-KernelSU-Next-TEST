# MFGA-XPosed
 
让你走内置字体了吗你就走啊，你很好看吗？给我走系统!  
XPosed版本MFGA不参与系统字体覆盖，只针对部分不走系统字体的应用让其强制走系统字体，同时保留字重。  
 
## 适配范围
 
- X(com.twitter.android)
- GitHub(com.github.android)
- Telegram(org.telegram.messenger)、Nagram(xyz.nextalone.nagram)...
- TikTok(com.zhiliaoapp.musically)
- YouTube(com.google.android.youtube)
 
仅此而已嘛？不。  
理论上你能在``res``里搜索到``inter.xml``的都能适配。很多适配作用域并没有添加进去，需自行测试  
火狐内核浏览器的覆盖暂不支持，等待后续适配  
 
## 下载与源码
 
在 [Releases](https://github.com/Xposed-Modules-Repo/com.mfga.xposed/releases) 下载最新版本  
查看源码 [Source](https://github.com/Numbersf/MakeFontsGreatAgain/tree/main/mfga-xposed)  
如果你想完成字体完全覆盖，请使用系统模块 [MFGA](https://github.com/Numbersf/MakeFontsGreatAgain/releases)  
记得star两个项目谢谢喵  
  
## 使用步骤
  
1. 安装 LSPosed 或 LSPatch
2. 启用模块并勾选对应应用
 
## 支持版本
 
- Android 1.0+
- 应用全版本自适配
[简体中文](https://github.com/Xposed-Modules-Repo/com.mfga.xposed/README.md) | **`English`**
<img align="right" src="https://github.com/Xposed-Modules-Repo/com.mfga.xposed/mfga.png" width="100px" alt="mfga">

# MFGA-XPosed
 
Let you use the built-in font, huh? Do you think you look that good? Give me the system font!  
The XPosed version of MFGA does not perform system-wide font overriding. It only targets specific apps that don't follow the system font and forces them to use it, while preserving font weights.  
 
## Scope of Adaptation
 
- X (com.twitter.android)
- GitHub (com.github.android)
- Telegram (org.telegram.messenger), Nagram (xyz.nextalone.nagram)...
- TikTok (com.zhiliaoapp.musically)
- YouTube (com.google.android.youtube)
 
Is that all? No.  
In theory, any app where you can find ``inter.xml`` by searching within ``res`` can be adapted. Many adaptation scopes have not yet been added and need to be tested manually  
Overriding on Firefox-engine-based browsers is not yet supported, adaptation is pending  
 
## Download & Source Code
 
Download the latest version from [Releases](https://github.com/Xposed-Modules-Repo/com.mfga.xposed/releases)  
View the source code [Source](https://github.com/Numbersf/MakeFontsGreatAgain/tree/main/mfga-xposed)  
If you want to achieve complete font overriding, please use the system module [MFGA](https://github.com/Numbersf/MakeFontsGreatAgain/releases)  
Remember to star both projects, thanks nya  
  
## Usage Steps
  
1. Install LSPosed or LSPatch
2. Enable the module and check the corresponding app
 
## Supported Versions
 
- Android 1.0+
- Full version auto-adaptation for apps
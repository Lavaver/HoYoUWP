# HoYoUWP - 米哈游聚合式 UWP 版启动器

HoYo UWP ，给你更快乐的一站式哈游宇宙门户体验！

（虽然只做了框架）

之前就有人做出来了，但这个项目我推迟很久才开，也算是错过大流了...

## 它有以下几大优势

- 极为先进的 UWP 设计语言，在保证轻量化的同时又能免去*找组件库*的麻烦

- 欢迎页底部显示基本的实时便签（需要登录 MiHoYo 或 HoYoVerse 通行证）

- 极为超前的融合式游戏思路，点击启动，不需要在任务栏切换到游戏界面就可以直接在这里愉快玩耍

- 游戏启动界面经过大幅简化，更适合聚合式体质（啥啊）

## 主界面（还是个空壳）

![主界面](/用于%20Markdown%20的%20Image/image.png)

## 安装注意事项

**在安装前请先在 /根证书 文件夹内下载安装证书，然后开始安装。否则会出现 0x800B010A 相关错误！**

## 文档树




```bash

HoYoUWP
│  .gitattributes
│  .gitignore
│  App.xaml
│  App.xaml.cs
│  HoYoUWP.csproj
│  HoYoUWP.csproj.user
│  HoYoUWP.sln
│  MainPage.xaml
│  MainPage.xaml.cs
│  Package.appxmanifest
│  README.md
│
├─Assets
│      LargeTile.scale-100.png
│      LargeTile.scale-125.png
│      LargeTile.scale-150.png
│      LargeTile.scale-200.png
│      LargeTile.scale-400.png
│      LockScreenLogo.scale-200.png
│      SmallTile.scale-100.png
│      SmallTile.scale-125.png
│      SmallTile.scale-150.png
│      SmallTile.scale-200.png
│      SmallTile.scale-400.png
│      SplashScreen.scale-100.png
│      SplashScreen.scale-125.png
│      SplashScreen.scale-150.png
│      SplashScreen.scale-200.png
│      SplashScreen.scale-400.png
│      Square150x150Logo.scale-100.png
│      Square150x150Logo.scale-125.png
│      Square150x150Logo.scale-150.png
│      Square150x150Logo.scale-200.png
│      Square150x150Logo.scale-400.png
│      Square44x44Logo.altform-lightunplated_targetsize-16.png
│      Square44x44Logo.altform-lightunplated_targetsize-24.png
│      Square44x44Logo.altform-lightunplated_targetsize-256.png
│      Square44x44Logo.altform-lightunplated_targetsize-32.png
│      Square44x44Logo.altform-lightunplated_targetsize-48.png
│      Square44x44Logo.altform-unplated_targetsize-16.png
│      Square44x44Logo.altform-unplated_targetsize-256.png
│      Square44x44Logo.altform-unplated_targetsize-32.png
│      Square44x44Logo.altform-unplated_targetsize-48.png
│      Square44x44Logo.scale-100.png
│      Square44x44Logo.scale-125.png
│      Square44x44Logo.scale-150.png
│      Square44x44Logo.scale-200.png
│      Square44x44Logo.scale-400.png
│      Square44x44Logo.targetsize-16.png
│      Square44x44Logo.targetsize-24.png
│      Square44x44Logo.targetsize-24_altform-unplated.png
│      Square44x44Logo.targetsize-256.png
│      Square44x44Logo.targetsize-32.png
│      Square44x44Logo.targetsize-48.png
│      StoreLogo.backup.png
│      StoreLogo.scale-100.png
│      StoreLogo.scale-125.png
│      StoreLogo.scale-150.png
│      StoreLogo.scale-200.png
│      StoreLogo.scale-400.png
│      Wide310x150Logo.scale-100.png
│      Wide310x150Logo.scale-125.png
│      Wide310x150Logo.scale-150.png
│      Wide310x150Logo.scale-200.png
│      Wide310x150Logo.scale-400.png
│
├─bin
│  ├─ARM
│  │  ├─Debug
│  │  └─Release
│  ├─ARM64
│  │  ├─Debug
│  │  └─Release
│  ├─x64
│  │  ├─Debug
│  │  └─Release
│  └─x86
│      ├─Debug
│      │  │  App.xbf
│      │  │  AppxManifest.xml
│      │  │  HoYoUWP.build.appxrecipe
│      │  │  HoYoUWP.exe
│      │  │  HoYoUWP.pdb
│      │  │  HoYoUWP.xr.xml
│      │  │  MainPage.xbf
│      │  │  Microsoft.UI.Xaml.Markup.winmd
│      │  │  resources.pri
│      │  │  System.Runtime.dll
│      │  │
│      │  ├─AppX
│      │  │  │  App.xbf
│      │  │  │  AppxManifest.xml
│      │  │  │  HoYoUWP.exe
│      │  │  │  HoYoUWP.xr.xml
│      │  │  │  MainPage.xbf
│      │  │  │  Microsoft.UI.Xaml.Markup.winmd
│      │  │  │  resources.pri
│      │  │  │  System.Runtime.dll
│      │  │  │  vs.appxrecipe
│      │  │  │
│      │  │  ├─Assets
│      │  │  │      LargeTile.scale-100.png
│      │  │  │      LargeTile.scale-125.png
│      │  │  │      LargeTile.scale-150.png
│      │  │  │      LargeTile.scale-200.png
│      │  │  │      LargeTile.scale-400.png
│      │  │  │      LockScreenLogo.scale-200.png
│      │  │  │      SmallTile.scale-100.png
│      │  │  │      SmallTile.scale-125.png
│      │  │  │      SmallTile.scale-150.png
│      │  │  │      SmallTile.scale-200.png
│      │  │  │      SmallTile.scale-400.png
│      │  │  │      SplashScreen.scale-100.png
│      │  │  │      SplashScreen.scale-125.png
│      │  │  │      SplashScreen.scale-150.png
│      │  │  │      SplashScreen.scale-200.png
│      │  │  │      SplashScreen.scale-400.png
│      │  │  │      Square150x150Logo.scale-100.png
│      │  │  │      Square150x150Logo.scale-125.png
│      │  │  │      Square150x150Logo.scale-150.png
│      │  │  │      Square150x150Logo.scale-200.png
│      │  │  │      Square150x150Logo.scale-400.png
│      │  │  │      Square44x44Logo.altform-lightunplated_targetsize-16.png
│      │  │  │      Square44x44Logo.altform-lightunplated_targetsize-24.png
│      │  │  │      Square44x44Logo.altform-lightunplated_targetsize-256.png
│      │  │  │      Square44x44Logo.altform-lightunplated_targetsize-32.png
│      │  │  │      Square44x44Logo.altform-lightunplated_targetsize-48.png
│      │  │  │      Square44x44Logo.altform-unplated_targetsize-16.png
│      │  │  │      Square44x44Logo.altform-unplated_targetsize-256.png
│      │  │  │      Square44x44Logo.altform-unplated_targetsize-32.png
│      │  │  │      Square44x44Logo.altform-unplated_targetsize-48.png
│      │  │  │      Square44x44Logo.scale-100.png
│      │  │  │      Square44x44Logo.scale-125.png
│      │  │  │      Square44x44Logo.scale-150.png
│      │  │  │      Square44x44Logo.scale-200.png
│      │  │  │      Square44x44Logo.scale-400.png
│      │  │  │      Square44x44Logo.targetsize-16.png
│      │  │  │      Square44x44Logo.targetsize-24.png
│      │  │  │      Square44x44Logo.targetsize-24_altform-unplated.png
│      │  │  │      Square44x44Logo.targetsize-256.png
│      │  │  │      Square44x44Logo.targetsize-32.png
│      │  │  │      Square44x44Logo.targetsize-48.png
│      │  │  │      StoreLogo.scale-100.png
│      │  │  │      StoreLogo.scale-125.png
│      │  │  │      StoreLogo.scale-150.png
│      │  │  │      StoreLogo.scale-200.png
│      │  │  │      StoreLogo.scale-400.png
│      │  │  │      Wide310x150Logo.scale-100.png
│      │  │  │      Wide310x150Logo.scale-125.png
│      │  │  │      Wide310x150Logo.scale-150.png
│      │  │  │      Wide310x150Logo.scale-200.png
│      │  │  │      Wide310x150Logo.scale-400.png
│      │  │  │
│      │  │  ├─entrypoint
│      │  │  │      HoYoUWP.exe
│      │  │  │
│      │  │  ├─Properties
│      │  │  │      Default.rd.xml
│      │  │  │
│      │  │  └─WinMetadata
│      │  │          Windows.winmd
│      │  │
│      │  └─Core
│      │          AppxManifest.xml
│      │          HoYoUWP.exe
│      │
│      └─Release
├─obj
│  │  HoYoUWP.csproj.nuget.dgspec.json
│  │  HoYoUWP.csproj.nuget.g.props
│  │  HoYoUWP.csproj.nuget.g.targets
│  │  project.assets.json
│  │  project.nuget.cache
│  │
│  ├─x64
│  │  └─Debug
│  │      │  .NETCore,Version=v5.0.AssemblyAttributes.cs
│  │      │  App.g.cs
│  │      │  DesignTimeResolveAssemblyReferencesInput.cache
│  │      │  HoYoUWP.csproj.AssemblyReference.cache
│  │      │  XamlSaveStateFile.xml
│  │      │
│  │      ├─intermediatexaml
│  │      └─TempPE
│  └─x86
│      └─Debug
│          │  .NETCore,Version=v5.0.AssemblyAttributes.cs
│          │  App.g.cs
│          │  App.g.i.cs
│          │  App.xaml
│          │  App.xbf
│          │  DesignTimeResolveAssemblyReferencesInput.cache
│          │  excluded.layout.resfiles
│          │  excluded.layout.resfiles.intermediate
│          │  filtered.layout.resfiles
│          │  filtered.layout.resfiles.intermediate
│          │  HoYoUWP.csproj.AssemblyReference.cache
│          │  HoYoUWP.csproj.CopyComplete
│          │  HoYoUWP.csproj.CoreCompileInputs.cache
│          │  HoYoUWP.csproj.FileListAbsolute.txt
│          │  HoYoUWP.exe
│          │  HoYoUWP.pdb
│          │  HoYoUWP.xr.xml
│          │  MainPage.g.cs
│          │  MainPage.g.i.cs
│          │  MainPage.xaml
│          │  MainPage.xbf
│          │  MultipleQualifiersPerDimensionFound.txt
│          │  pri.resfiles
│          │  pri.resfiles.intermediate
│          │  priconfig.xml
│          │  priconfig.xml.intermediate
│          │  ProjectArchitectures.txt
│          │  qualifiers.txt
│          │  qualifiers.txt.intermediate
│          │  ResourceHandlingTask.state
│          │  resources.resfiles
│          │  resources.resfiles.intermediate
│          │  unfiltered.layout.resfiles
│          │  unfiltered.layout.resfiles.intermediate
│          │  XamlSaveStateFile.xml
│          │  XamlTypeInfo.g.cs
│          │
│          ├─.winmd_cache
│          │      $Microsoft.UI.Xaml.Markup.winmd_638316082480000000.json
│          │
│          ├─embed
│          │      embed.resfiles
│          │      embed.resfiles.intermediate
│          │
│          ├─intermediatexaml
│          │      HoYoUWP.exe
│          │      HoYoUWP.pdb
│          │
│          └─TempPE
└─Properties
        AssemblyInfo.cs
        Default.rd.xml
```

# 结语

目前仍在开发，如果你对此工程感兴趣你也可以加入我的开发！万分感谢！

最后，预祝上线时玩的开心:)

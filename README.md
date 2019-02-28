# scoop-fruit
some app I need, scoop app. just it.

MAYBE FOR CHINESE PEOPLE

# windows开发环境配置
主要通过 [Scoop](https://github.com/lukesampson/scoop) 安装相应开发工具！

先：`scoop bucket add extras`
```
λ scoop bucket list
extras
java
versions
scoop-fruit
```

然后安装下列必备软件：

```
  mychrome *global* [scoop-fruit]
  android-sdk 4333796 *global* [extras]
  aria2 1.34.0-1
  bulk-crap-uninstaller 4.12.1 *global* [extras]
  cmder 1.3.11
  dbeaver 5.3.1 *global* [extras]
  devdocs 0.6.9 *global* [extras]
  everything 1.4.1.924 *global* [extras]
  Flutter 0.11.3 *global*
  gifcam 5.5 *global* [extras]
  git 2.20.1.windows.1
  gradle 5.0
  mobaXterm 11.0 *global* [extras]
  notepad2-mod 4.2.25.998 *global* [extras]
  nvm 1.1.7
  oraclejdk8 8u191-b12 *global* [java]
  python 3.7.2
  python27 2.7.15 [versions]
  sublime-text 3176 [extras]
  sudo 0.2018.08.04
  vscode 1.30.1 *global* [extras]
  yarn 1.12.3
```

# 如何使用
1. 添加 `scoop-fruit`:
```
scoop bucket add scoop-fruit https://github.com/ChandlerVer5/scoop-fruit
```

2. 下载并检查是否工作:
```
scoop bucket list # -> you should see 'scoop-fruit'
scoop search neteasemusic # -> you should see neteasemusic listed under, 'scoop-fruit bucket:'
scoop install neteasemusic # -> you have DONE!Yeah~
```

# list apps
just-flutter : no dependencies
 
# TODO（DONE！）
1. ~~mychrome~~
2. ~~网易云音乐~~
3. ~~kancloud~~

# 参考
* https://github.com/lukesampson/scoop/wiki/Buckets
* https://github.com/rasa/scoop-directory/blob/master/by-score.md
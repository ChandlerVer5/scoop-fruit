# scoop-fruit
some app I need, scoop app. just it.

# windows������������
��Ҫͨ�� [Scoop](https://github.com/lukesampson/scoop) ��װ��Ӧ�������ߣ�

�ȣ�`scoop bucket add extras`
```
�� scoop bucket list
extras
java
versions
```

Ȼ��װ���бر������
[mychrome](https://github.com/cnjackchen/my-chrome/releases)
```
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

# list apps
just-flutter : no dependencies
 
# TODO
1. mychrome
2. neteasemusic
3. kancloud

# How to use
1. Configure Scoop to use your new bucket:
```
scoop bucket add my-bucket https://github.com/<your-username>/my-bucket
```

2.Check that it works:
```
scoop bucket list # -> you should see 'my-bucket'
scoop search hello # -> you should see hello listed under, 'my-bucket bucket:'
scoop install hello
hello # -> you should see 'Hello, <windows-username>!'
```

# Refs
https://github.com/lukesampson/scoop/wiki/Buckets
https://github.com/rasa/scoop-directory/blob/master/by-score.md
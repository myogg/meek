# [项目功能：Apple Music音乐下载](https://github.com/myogg/meek/issues/34)

  项目简介：一个用于从Apple Music下载音乐的开源项目，支持下载ALAC格式和Dolby Atmos格式的音轨。

 支持下载单曲、整个专辑以及歌单中的音乐。下载的文件可以自动分类到按歌手名和专辑名组织的文件夹中。

  项目地址：[点击直达](https://github.com/zhaarey/apple-music-alac-atmos-downloader)

>  添加功能
   调用外部MP4Box自动封装ec3为m4a
   更改目录结构为 歌手名\专辑名 ;Atmos下载文件则另外移动到AM-DL-Atmos downloads，并更改目录结构为 歌手名\专辑名 
  [Atmos]
  运行结束后显示总体完成情况
  自动内嵌封面和LRC歌词（需要media-user-token，获取方式看最后的说明）
  自动构建 可以到 [Actions](https://github.com/zhaarey/apple-music-alac-atmos-downloader/actions) 页面下载最新自动构建版本 
  可以直接main.exe url
  main_select 支持手动填写m3u8，输入#号，比如#1 #2，支持txt读取m3u8，输入txt文件名

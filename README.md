# 东方大炮弹角色语音翻译库

## 简介

这里包含了从各种渠道来的语音翻译

- bilibili 
  - CC字幕
- seesaawiki 
  - 通过翻译平台得来的翻译结果，包括谷歌、deepL、微软和mymemory
- 解包的语音数据，[来源](https://www.bilibili.com/read/cv8373398)

## 数据库结构

- table_audio_info
  - audio_id
  - file_path
- table_bilibili_translate
  - translate_id
  - audio_id
  - seesaawiki_id
- table_seesaawiki_info
  - seesaawiki_id
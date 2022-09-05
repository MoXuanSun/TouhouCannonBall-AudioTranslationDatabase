# 东方大炮弹角色语音翻译库

## 来源
- [bilibili视频CC字幕](https://www.bilibili.com/read/cv8373398) 翻译后的文本
- [seesaawiki](https://seesaawiki.jp/thcb/d/%a5%bb%a5%ea%a5%d5%bd%b8#content_2_1) 文本
- [解包的语音数据](https://www.bilibili.com/read/cv8373398) 语音

## 翻译工具

- 谷歌 
  - mt
- 微软
  - mt
- mymemory
  - mt
  - human
- deepl
  - mt
- bilibili
  - CC subtitle


## 数据库结构
类型：Sqlite

- table_audio_info
  - audio_id
  - file_path
- table_bilibili_translate
  - translate_id
  - audio_id
  - seesaawiki_id
- table_seesaawiki_info
  - seesaawiki_id
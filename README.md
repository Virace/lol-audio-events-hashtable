# lol-audio-events-hashtable

英雄联盟音频文件与音频触发事件哈希表

解包版本: 11.11.3776311  
更新时间: 2021年06月02日  

By: Termux for Android

目录介绍:

- VO: 语音音频文件
- SFX: 效果音音频文件
- MUSIC: 地图内背景音乐

格式: 

```json
{
	"data": { "assets/sounds/wwise2016/vo/zh_cn/characters/aatrox/skins/base/aatrox_base_vo_audio.wpk": {...} },
	"info": {
		"kind": "characters",
		"name": "aatrox",
		"detail": "skin0",
		"type": "VO",
		"wad": "Game/DATA/FINAL/Champions/Aatrox.zh_CN.wad.client"
	}
	
}
```

包含了**wad文件路径**以及**音频文件路径**等信息, 方便后续操作.



[py-bnk-extract](https://github.com/Virace/py-bnk-extract) & [lol_extract_voice](https://github.com/Virace/lol_extract_voice)

> PS: 当前因py-bnk-extract库部分文件格式未了解, 所以效果音音频文件哈希表有可能不完整.

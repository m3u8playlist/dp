# 小点播放器 订阅
app:https://apps.apple.com/us/app/dotplayer/id1455092592

tg:https://t.me/dotplayer

tg channel:https://t.me/dotplayerlists

## 添加订阅
小点播放器目前支持三种格式的订阅文件 txt,json 和m3u 文件

### txt
```
频道名称1,http://www.example.com/index.m3u8

频道名称2,http://www.example.com/index.m3u8
```
### m3u
```
#EXTM3U

#EXTINF:-1, 频道名称1
http://www.example.com/index.m3u8

#EXTINF:-1, 频道名称2
http://www.example.com/index.m3u8
```
### json


```json
{
	"uuid":"64350b50-a810-4901-b86b-7a5106bdef2c",
	"title": "change title here",

	"channels": [		

		{
			"name":"change channel name",
			"url": "http://www.example.com/index.m3u8"
		},
    		{
			"name":"change channel name",
			"url": "http://www.example.com/index.m3u8"
		}

    
    ]
}
```
JSON文件分成了3个部分
1. uuid : "64350b50-a810-4901-b86b-7a5106bdef2c", 不要更改这个uuid
2. title: 导入时会用到的名字，你可以随意更改
3. channels: 频道列表里有name和url 2个部分，用户自己添加

在github上新建一个json，然后按raw按钮，就会得到一个纯文本的直连链接，格式如下
https://raw.githubusercontent.com/USER_NAME/REPO_NAME/master/file.json

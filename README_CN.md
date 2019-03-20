## 添加订阅

### live tv

* https://raw.githubusercontent.com/m3u8playlist/dp/master/live_tv/hk.json
* https://raw.githubusercontent.com/m3u8playlist/dp/master/live_tv/us.json
* https://raw.githubusercontent.com/m3u8playlist/dp/master/live_tv/jp.json
* https://raw.githubusercontent.com/m3u8playlist/dp/master/live_tv/kr.json
* https://raw.githubusercontent.com/m3u8playlist/dp/master/live_tv/sg.json
* https://raw.githubusercontent.com/m3u8playlist/dp/master/live_tv/uk.json
* https://raw.githubusercontent.com/m3u8playlist/dp/master/live_tv/canada.json
* https://raw.githubusercontent.com/m3u8playlist/dp/master/live_tv/macau.json
* https://raw.githubusercontent.com/m3u8playlist/dp/master/live_tv/misc1.json

### radio
* https://raw.githubusercontent.com/m3u8playlist/dp/master/radio/hk.json
* https://raw.githubusercontent.com/m3u8playlist/dp/master/radio/uk.json
* https://raw.githubusercontent.com/m3u8playlist/dp/master/radio/us.json
* https://raw.githubusercontent.com/m3u8playlist/dp/master/radio/classical.json
* https://raw.githubusercontent.com/m3u8playlist/dp/master/radio/blues.json
* https://raw.githubusercontent.com/m3u8playlist/dp/master/radio/country.json
* https://raw.githubusercontent.com/m3u8playlist/dp/master/radio/top.json

## 如何建立正确的json文件格式


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

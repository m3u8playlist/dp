[中文](README_CN.md)

# dotplay m3u8 resource
app:https://apps.apple.com/us/app/dotplayer/id1455092592

tg:https://t.me/dotplayer

tg channel:https://t.me/dotplayerlists

## add to subscription

dotplayer support txt,json and m3u file

### txt 
```
channel name1,http://www.example.com/index.m3u8

channel name2,http://www.example.com/index.m3u8
```
### m3u

```
#EXTM3U

#EXTINF:-1, channel name1
http://www.example.com/index.m3u8

#EXTINF:-1, channel name2
http://www.example.com/index.m3u8
```


### json
```
{
	"uuid":"64350b50-a810-4901-b86b-7a5106bdef2c",
	"title": "change title here",

	"channels": [		

		{
			"name":"channel name1",
			"url": "http://www.example.com/index.m3u8"
		},
    		{
			"name":"channel name2",
			"url": "http://www.example.com/index.m3u8"
		}

    
    ]
}
```

The JSON file is divided into three parts
1. uuid : "64350b50-a810-4901-b86b-7a5106bdef2c", don't change it.
2. title: you can change it whatever you like
3. channels: name and url are included.

create this json file on github, get the raw file link, something like
https://raw.githubusercontent.com/USER_NAME/REPO_NAME/master/file.json

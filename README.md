## add to subscription

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



## how to make a json file


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

The JSON file is divided into three parts
1. uuid : "64350b50-a810-4901-b86b-7a5106bdef2c", don't change it.
2. title: you can change it whatever you like
3. channels: name and url are included.

create this json file on github, get the raw file link, something like
https://raw.githubusercontent.com/USER_NAME/REPO_NAME/master/file.json

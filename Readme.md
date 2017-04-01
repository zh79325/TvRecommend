# App配置

### 配置入口

[https://zhou7758437.github.io/TvRecommend/config.json](https://zhou7758437.github.io/TvRecommend/config.json)
### Film Data url
```
url=${dataCenter}+${film.data}
```

### Film Img url
```
url=${imgCenter}+${film.imgUrl}
```

### Film Structure
```
{
    //name
    "n": "asdasd",
    //year              
    "y": 2010,
    //tags                   
    "t": ["a", "b", "c"],
    //Description
    "d": "this is test",
    //Socre
    "s": 6.8,
    //area
    "a":"美国",
    //language
    "l":"英语",
    //cover
    "c": "006gmrTbgy1fe76ofkbekj30bb0gojth.jpg",
    //img for screen shots
    "i": ["006gmrTbgy1fe76of00osj30zk0k0whl.jpg", "006gmrTbgy1fe76oe7684j30zk0k0mzr.jpg"],
    //torrent urls
    "u":"aaa.torrent"
    //group
    "g":"美剧",
    //video list 如果是电视剧的时候该字段有值
    "v":[{id:1,"name":"第一集",url:"aaa.torrent"}]
}
```

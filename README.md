# Shenzhen Maker Map
https://lab0x0.github.io/szmakermap/

## What is this

We are making Shenzhen Maker Map.  
The idea is very similar to Shenzhen Map for Makers by Seeed Studio ([pdf](http://www.seeedstudio.com/document/pdf/Shenzhen%20Map%20for%20Makers.pdf))
![makermap](https://user-images.githubusercontent.com/415928/30964692-2f49cd6c-a45b-11e7-8fc6-0eb14c4fc1ba.jpg)

The diference is:
- Our version will be up to date
- We will have 
  - Web verson optimized for mobile
  - WeChat mini app (小程序)
  - A big printed A1 poster verson for makerspaces

## GeoJSON
```
{
  "type": "Feature",
  "geometry": {
    "type": "Point",
    "coordinates": [0.0, 0.0]
  },
  "properties": {
    "category": "makerspaces",
    "opening_hours": null,
    "url": "https://lab0x0.com",
    "contacts": "Alex, 0xff@lab0x0.com, wechat: targence",    
    "en": {
      "name": "LAB ZERO",
      "description": "LAB ZERO is non-profit makers community and a genuine makerspace in Shenzhen",
      "address": null   
    },
    "zh": {
      "name": "零空间",
      "description": null,
      "address": "深圳南山区南头街道麻雀岭工业区m10栋4号楼一楼 零空间 (LAB ZERO)"
    }
  }
}
```

### Coordinates format
```
"coordinates": [longitude, latitude]
```

### How to get coordinates for a new place
http://api.map.baidu.com/lbsapi/getpoint/index.html


### Polygons support
```
{
  "type": "Polygon",
  "coordinates": [
    [
      [-104.05, 48.99],
      [-97.22, 48.98],
      [-96.58, 45.94],
      [-104.03, 45.94],
      [-104.05, 48.99]
    ]
  ]
}
```


## How to participate?

Add Alex in WeChat, he add you into working group, introduce you to other people and give task.
![photo_2017-09-28_14-42-12](https://user-images.githubusercontent.com/415928/30965128-e5d6c5a2-a45c-11e7-87f4-dcbebb5da7f8.jpg)

If you are interesting to see some working process please check these links:
- https://github.com/lab0x0/szmakermap/issues
- https://github.com/lab0x0/szmakermap/wiki

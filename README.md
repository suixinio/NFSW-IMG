# NFSW-IMG
Gsky的鉴黄服务

## 工具
TensorFlow,TensorFlow-serving 提供服务

ResNet，图像分类的预训练模型。

nsfw_data_scraper ,1w星标的珍藏数据资源 https://github.com/alex000kim/nsfw_data_scraper


## nsfw_data

- Drawing   绘画，无害的艺术，或艺术绘画
- Hentai    变态，色情艺术，不适合大多数工作环境
- Neutral   中立，一般，无害的内容
- Porn      色情，不雅的内容和行为，通常涉及生殖器
- Sexy      性感，不合时宜的挑衅内容

## 可用来借鉴的项目【返回数据格式等】
- nsfw https://github.com/infinitered/nsfwjs
- nsfw_model https://github.com/gantman/nsfw_model

## resp
```
{
	"code": 0,
	"review": true,
	"check": {
		"Drawing": 0,
		"Hentai": 0,
		"Neutral": 0,
		"Porn": 0,
		"Sexy": 0
	}
}
```
review 是否要再次审核

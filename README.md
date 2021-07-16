# NFSW-IMG
Gsky的鉴黄服务

## 工具
TensorFlow,TensorFlow-serving 提供服务

ResNet|Efficient，图像分类的预训练模型。

数据源：

https://github.com/alex000kim/nsfw_data_scraper

https://github.com/EBazarov/nsfw_data_source_urls

## nsfw_data

- Drawing   绘画，无害的艺术，或艺术绘画
- Hentai    变态，色情艺术，不适合大多数工作环境
- Neutral   中立，一般，无害的内容
- Porn      色情，不雅的内容和行为，通常涉及生殖器
- Sexy      性感，不合时宜的挑衅内容



## resp
```
{
	"code": 0,
	"classes":"neutral",
	"review": true,
	"probabilities": {
		"drawing": 0,
		"hentai": 0,
		"neutral": 0,
		"porn": 0,
		"sexy": 0
	}
}
```
review 是否要再次人工审核

## 参考
- nsfw https://github.com/infinitered/nsfwjs
- nsfw_model https://github.com/gantman/nsfw_model
- yahoo open_nsfw https://github.com/yahoo/open_nsfw

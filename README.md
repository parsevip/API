# API 接口文档        
Author  :  lijishi    
Contact :  lijishi@163.com    
License :  GNU GENERAL PUBLIC LICENSE Version 3    

## 1、接口地址 & 代码开源     
#### API：api.telecom.ac.cn   
#### APICDN：cdn.api.telecom.ac.cn      
#### APIDOC：doc.api.telecom.ac.cn         
#### Github：github.com/GaryNotGay/API    
#### Gitee：gitee.com/garynotgay/api    

## 2、开发文档    
#### 2.1 MangoTV    
路径：https://api.telecom.ac.cn/mango    
说明：MGTV视频解析M3U8    
示例：https://api.telecom.ac.cn/mango?id=16322652&title=446003&qua=1    
    
| 参数 | 必选 | 示例 | 说明 |
| --- | --- | --- | --- |
| id | 是 | 16322652 | https://www.mgtv.com/b/[title]/[id].html |
| title | 是 | 446003 | https://www.mgtv.com/b/[title]/[id].html |
| qua | 否 | 1,2,3 | 可选视频质量，可选视频质量，360P(0)，540P(1)，720P(2)，1080P(3)，默认全选，英文逗号分隔 |
| hdcn | 否 | xxxxxxxxxxxxxxxxxx-xxxxxxxxx | 从WEB中获取，携带此参数可获取会员视频及1080P清晰度，默认为空 |    
    
#### 2.2 Ckey7x    
路径：https://api.telecom.ac.cn/ckey7x    
说明：TX视频请求参数校验算法    
参考：https://www.jianshu.com/p/75619f7e3956    
示例：https://api.telecom.ac.cn/ckey7x?platform=40201&vid=100701&sdt=v1010&tm=1651217559&ver=7.1    
    
| 参数 | 必选 | 示例 | 说明 |
| --- | --- | --- | --- |
| platform | 是 | 40201 | 请求参数之一 |
| vid | 是 | 100701 | 视频vid |
| sdt | 是 | v1010 | 请求参数之一 |
| tm | 是 | 1651217559 | 10位时间戳 |
| ver | 是 | 7.1 | 7.x，其中x为周几 |
    
#### 2.3 Ckey81    
路径：https://api.telecom.ac.cn/ckey81    
说明：TX视频请求参数校验算法    
参考：https://www.pohaier.com/2018/12/22/227.html    
示例：https://api.telecom.ac.cn/ckey8x?vid=i0037ryjlwn&time=1623678055&guid=6eb81823f6e496f9a87c88fbe977dee0&platform=4830201&url=https://wetv.vip    

| 参数 | 必选 | 示例 | 说明 |
| --- | --- | --- | --- |
| platform | 是 | 40201 | 请求参数之一 |
| vid | 是 | i0037ryjlwn | 视频vid |
| guid | 是 | 6eb81823f6e496f9a87c88fbe977dee0 | 请求参数之一 |
| time | 是 | 1651217559 | 10位时间戳 |
| url | 是 | https://wetv.vip | 请求参数之一 |
    
#### 2.4 Ckey91    
路径：https://api.telecom.ac.cn/ckey91    
说明：TX视频请求参数校验算法    
参考：https://github.com/ZSAIm/iqiyi-parser/blob/master/js/tencent.js    
示例：https://api.telecom.ac.cn/ckey91?   platform=10201&appver=3.5.57&vid=j002024w2wgguid=1fcb9528b79f2065c9a281a7d554edd1&tm=1556617308&url=https://wetv.vip    

| 参数 | 必选 | 示例 | 说明 |   
| --- | --- | --- | --- |
| platform | 是 | 10201 | 请求参数之一 |
| appver | 是 | 3.5.57 | 请求参数之一 |
| vid | 是 | j002024w2wgguid | 视频vid |
| guid | 是 | 1fcb9528b79f2065c9a281a7d554edd1 | 请求参数之一 |
| tm | 是 | 1651217559 | 10位时间戳 |
| url | 是 | https://wetv.vip | 请求参数之一 |

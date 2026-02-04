## 前言

此项目为基于Vue的米家商城的设计与实现，是本人毕业设计之作，包含了完整的前后台功能。项目使用Java开发，前端采用Vue框架，数据库使用MySQL。在此分享给大家，希望能为正在做类似项目的同学提供一些参考。

## 内容介绍

本项目实现了米家商城的基本功能，包括用户注册登录、商品展示、购物车、订单管理、后台管理等模块。前端界面简洁美观，响应式设计，用户体验良好。后端采用Spring Boot框架，保证了系统的稳定性与可维护性。

## 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、css3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下为项目中的一部分核心代码，展示了后端接收前端请求并返回商品列表的过程：

```java
@RestController
@RequestMapping("/api/product")
public class ProductController {

    @Autowired
    private ProductService productService;

    @GetMapping("/list")
    public ResponseEntity<List<Product>> list() {
        List<Product> products = productService.list();
        return ResponseEntity.ok(products);
    }
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img13.360buyimg.com/ddimg/jfs/t1/306990/35/26536/98561/689ec70cF790962d7/5a653baf4357683a.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/300959/34/14506/41999/689ec6eaF2ea0cf9d/8cda1ee8bb08b682.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/309198/28/26595/35561/689ec6eaF633f8eef/a0d0c4e3e38405bd.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/309668/3/26808/16349/689ec6f0Fa11c4a21/a920f926403815f6.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/318002/20/24868/21488/689ec6f1F53d616c9/0a5485588e6da774.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/326754/38/4692/13206/689ec6f7Fb7dc1ee7/d2a78cc5f55e8e7f.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/317210/25/25214/52091/689ec6f9F20a8fc2b/528b129f4641405f.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/286420/20/25367/43273/689ec6f9Faa7296ec/51d4189a9f41bfe1.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/109506/9/49351/66835/689ec6faF9106d772/9a570073eb67370a.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/316225/29/26666/29370/689ec6faF54c1aa46/4cf31b8fdd9504d9.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)

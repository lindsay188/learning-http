1.对于服务端的no-cache和max-age=0
2.客户端都不会取缓存，在表现上这两个字段结果是一样的，都是去验证然后返回304
3.具体的不同是验证分为SHOULD 和 MUST
SpringBoot + Spring Security + MyBatis + Redis + oauth2

# oauth2 实现 password,refresh_token
### 集成SpringBoot、 Spring Security、 MyBatis、 OAuth2、 Redis实现资源访问授权认证。
### 后端主要做的是认证服务器和资源服务。
### 用户登录使用自定义UserDetailService从MySQL中加载数据。
### 用户认证的token使用RedisTokenStore保存在redis中，提高系统并发能力。
### 用户使用自定义ClientDetailsService从MySQL中加载Oauth2客户端详情。
### 初始数据及样例，见：document目录
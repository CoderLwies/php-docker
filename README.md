# docker php开发环境

启动方式
```
docker-compose -f docker-compose.yml up
```

php拓展安装
```
// 修改 Dockerfile 文件
// 加入命令，如安装 redis 拓展 
RUN pecl install redis && docker-php-ext-enable redis
```
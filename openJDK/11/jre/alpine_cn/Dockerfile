FROM alpine:3.14.3

# 镜像作者信息
LABEL MAINTAINER "blog.midaug.win"

# 设定系统语言环境
ENV LANG='C.UTF-8' LANGUAGE='C.UTF-8' LC_ALL='C.UTF-8' TZ='Asia/Shanghai'

# 安装软件
RUN apk update && apk --no-cache add openjdk11-jre && \ 
    rm -rf /var/cache/apk/*
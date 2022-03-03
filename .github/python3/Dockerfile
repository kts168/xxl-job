# 从仓库拉取 带有 python 3.7 的 Alpine Linux 环境
FROM python:3.7-alpine

# 维护者信息
MAINTAINER  hongwei "https://www.zhwei.cn/"

# 添加alpine apk源，我在本地centos中添加索性就加上了，其实不加也行 
RUN echo "http://mirrors.aliyun.com/alpine/latest-stable/community/" >> /etc/apk/repositories
RUN echo "http://dl-cdn.alpinelinux.org/alpine/edge/community/" >> /etc/apk/repositories;
RUN echo "http://dl-2.alpinelinux.org/alpine/edge/community" >> /etc/apk/repositories;
RUN echo "http://dl-3.alpinelinux.org/alpine/edge/community" >> /etc/apk/repositories;
RUN echo "http://dl-4.alpinelinux.org/alpine/edge/community" >> /etc/apk/repositories;
RUN echo "http://dl-5.alpinelinux.org/alpine/edge/community" >> /etc/apk/repositories

# 安装alpine依赖，system update\ system lib\ mysqlclient\ Pillow\ bash
RUN apk update \
    && apk add --no-cache linux-headers libffi-dev \
    && apk add --no-cache gcc python3-dev musl-dev mariadb-dev\
    && apk add --no-cache jpeg-dev zlib-dev freetype-dev lcms2-dev openjpeg-dev tiff-dev tk-dev tcl-dev \
    && apk add --no-cache bash bash-doc bash-completion

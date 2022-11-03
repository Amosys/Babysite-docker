# 建立 python3.7 环境
FROM python:3.7.10

# 镜像作者Amos
MAINTAINER amos

# 设置容器内工作目录
WORKDIR /home

#RUN apt-get update
#RUN apt-get install gcc
# 在容器内安装django
RUN pip install Django -i https://mirrors.aliyun.com/pypi/simple

# 在容器内安装uwsgi
RUN pip install uwsgi -i https://mirrors.aliyun.com/pypi/simple

RUN mkdir /home/backend


# 表示我的镜像是基于nginx修改的 
FROM nginx
# 创作者 amos
MAINTAINER amos
# 把我的项目dist/里的所有文件复制到/usr/share/nginx/html/ 
COPY ./dist  /usr/share/nginx/html/
# 把Nginx的配置文件覆盖镜像里面的nginx.conf文件
COPY nginx.conf /etc/nginx/nginx.conf
# 镜像构建完成后输出的提示
RUN echo 'echo init ok!!'




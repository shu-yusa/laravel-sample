FROM nginx:1.15-alpine
COPY server.conf /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/nginx.conf

# RUN apk update \
# && echo "alias ls='ls -hp'" >> /etc/profile.d/alias.sh \
# && echo "alias ll='ls -l'" >> /etc/profile.d/alias.sh \
# && echo "alias la='ls -la'" >> /etc/profile.d/alias.sh

# FROM nginx:1.15
# ADD vimrc /root/.vimrc
# RUN apt-get update && apt-get install -y vim \

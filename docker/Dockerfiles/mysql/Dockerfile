FROM mysql:8
COPY mysqld.cnf /etc/mysql/mysql.conf.d/mysqld.cnf
COPY vimrc /root/.vimrc

RUN apt-get update \
&& apt-get install -y vim \
&& echo "alias ls='ls -hp'" >> /root/.bashrc \
&& echo "alias ll='ls -l'" >> /root/.bashrc \
&& echo "alias la='ls -la'" >> /root/.bashrc \
&& echo "alias vi='vim'" >> /root/.bashrc

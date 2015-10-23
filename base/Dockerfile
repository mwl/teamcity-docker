FROM java:8-jdk

ADD https://download.jetbrains.com/teamcity/TeamCity-9.1.3.tar.gz /tmp/teamcity.tar.gz

WORKDIR /usr/lib

RUN tar xvzf /tmp/teamcity.tar.gz && rm -rf /tmp/teamcity*.tar.gz && ln -s /usr/lib/TeamCity/bin/teamcity-server.sh /usr/bin/teamcity-server


FROM mwldk/teamcity-base:9.1.3

EXPOSE 8111

ENV TEAMCITY_DATA_PATH=/var/teamcity



VOLUME /var/teamcity/config
VOLUME /var/teamcity/lib
VOLUME /var/teamcity/plugins
VOLUME /var/teamcity/system

CMD /usr/lib/TeamCity/bin/teamcity-server.sh run

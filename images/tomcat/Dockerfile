FROM tomcat:8.5.20-jre8-alpine

MAINTAINER Olivier Liechti <olivier.liechti@heig-vd.ch>

ADD config /usr/local/tomcat/conf/
ADD manager /usr/local/tomcat/webapps/manager/

COPY LandingPageApp-1.0-SNAPSHOT.war /usr/local/tomcat/webapps/LandingPageApp-1.0-SNAPSHOT.war
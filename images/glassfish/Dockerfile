FROM oracle/glassfish:4.1.1

MAINTAINER Olivier Liechti <olivier.liechti@heig-vd.ch>


ADD drivers/mysql-connector-java-5.1.39-bin.jar /glassfish4/glassfish/lib/

COPY ../apps-dist/LandingPageApp-1.0-SNAPSHOT.war glassfish/domains/domain1/autodeploy/LandingPageApp-1.0-SNAPSHOT.war

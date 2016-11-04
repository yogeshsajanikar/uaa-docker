FROM tomcat:9-jre8

ENV UAA_VERSION 3.2.1

RUN rm -rf $CATALINA_HOME/webapps/ROOT

ADD http://central.maven.org/maven2/org/cloudfoundry/identity/cloudfoundry-identity-uaa/3.2.1/cloudfoundry-identity-uaa-3.2.1.war $CATALINA_HOME/webaaps/ROOT.war

EXPOSE 8080


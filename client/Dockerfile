# sudo docker build -t chrisccoy/microsvcdemoclnt ./
# sudo docker run -d --name democlnt --link msdemo:msdemo chrisccoy/microsvcdemoclnt
#
FROM dockerbase/java7
MAINTAINER chrisccoy@gmail.com
EXPOSE 7311
ADD target/feign-eureka-hello-client-0.0.1-SNAPSHOT.jar /opt/axway/ms_clnt.jar
CMD java -jar /opt/axway/ms_clnt.jar
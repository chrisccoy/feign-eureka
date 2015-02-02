# sudo docker build -t chrisccoy/microsvcdemosvc1 ./
# sudo docker run -d --name microsvcdemosvc1 --link msdemo:msdemo chrisccoy/microsvcdemosvc1
FROM dockerbase/java7
MAINTAINER chrisccoy@gmail.com
EXPOSE 7111
ADD target/feign-eureka-micro1-0.0.1-SNAPSHOT.jar /opt/axway/ms_svr.jar
CMD java -jar /opt/axway/ms_svr.jar

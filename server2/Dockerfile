# sudo docker build -t chrisccoy/microsvcdemosvc2 ./
# sudo docker run -d --name microsvcdemosvc2 --link msdemo:msdemo chrisccoy/microsvcdemosvc2
FROM dockerbase/java7
MAINTAINER chrisccoy@gmail.com
EXPOSE 7211
ADD target/feign-eureka-micro2-0.0.1-SNAPSHOT.jar /opt/axway/ms_svr2.jar
CMD java -jar /opt/axway/ms_svr2.jar

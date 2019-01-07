FROM java:8

ADD target/sentiment-analysis-web-0.0.1-SNAPSHOT.jar /usr/app/sentiment-analysis-web-0.0.1-SNAPSHOT.jar

WORKDIR /usr/app

ENTRYPOINT ["java","-jar","sentiment-analysis-web-0.0.1-SNAPSHOT.jar","--sa.logic.api.url=http://192.168.1.114:5000"] 

EXPOSE 8080

#Use the latest alpine image
FROM alpine:latest

#Install python using the image
RUN apk add python

#Run ping 5 times
ENTRYPOINT [ "ping", "-t", "5" ]

#Ping this ip
CMD [ "8.8.8.8" ]

#To change CMD value use docker run alpine-python-image:1 4.4.4.4
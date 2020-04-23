#Use existing docker image as a base
FROM alpine
#Download and install dependencies
RUN apk add --update redis
#Specify default command
CMD ["redis-server"]
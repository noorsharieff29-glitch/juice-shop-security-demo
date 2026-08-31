FROM alpine 


RUN apk add curl


COPY smoke-test.sh smoke-test.sh


CMD ["sh", "smoke-test.sh", "http://app:3000"]


#Create a small Alpine Linux container, install curl, 
#cpy my smoke-test script into it, and when the container starts, 
#xecute that script against the application at http://app:3000. RUN adduser -D appuser
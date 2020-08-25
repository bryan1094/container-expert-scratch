FROM alpine

WORKDIR /app
# ADD vs COPY
COPY myapp.sh /app/

RUN ls /app && chmod +x myapp.sh && apk add --update bash

CMD ["./myapp.sh"]
#ENTRYPOINT [ "bash", "myapp.sh" ]

FROM ubuntu

MAINTAINER sofija

WORKDIR
COPY ./target/DockerFun-0.0.1-SNAPSHOT.jar  .

COPY ./docscript.sh /

RUN chmod +x /docscript.sh

ENTRYPOINT ["/docscript.sh"]

CMD ["npm start"]


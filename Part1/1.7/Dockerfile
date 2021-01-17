FROM ubuntu:16.04 

RUN apt-get update && apt-get install -y curl 

COPY haesivu.sh .

RUN chmod +x haesivu.sh

ENTRYPOINT [ "/bin/bash" ]
CMD [ "./haesivu.sh" ]
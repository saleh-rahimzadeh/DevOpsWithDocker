FROM ubuntu
RUN apt-get update && apt-get install -y curl
WORKDIR /mydir
COPY my_script.sh . 
CMD ["/bin/bash", "my_script.sh"]

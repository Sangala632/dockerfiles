FROM almalinux:9

RUN dnf install git  -y 

RUN useradd sreekanth 
USER sreekanth 

RUN mkdir /tmp/workdir
WORKDIR /tmp/workdir
RUN pwd

RUN echo "hello i am working workdir directory" > hello.txt
CMD ["sleep","2000"]  


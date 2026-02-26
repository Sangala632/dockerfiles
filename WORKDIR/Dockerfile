FROM almalinux:9

RUN useradd sreekanth 
USER sreekanth 

RUN mkdir /tmp/workdir
WORKDIR /tmp/workdir
RUN pwd
RUN dnf install git  -y 


RUN echo "hello i am working workdir directory" > hello.txt
CMD ["sleep","2000"]  


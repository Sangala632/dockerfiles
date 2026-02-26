FROM almalinux:9
ENV COURCE="devops"\
    duration="120HRS"

ARG TRAINER="sreekanth"

ENV trainer=$TRAINER

RUN dnf install git  -y 

RUN useradd sreekanth 
USER sreekanth 

RUN mkdir /tmp/workdir
WORKDIR /tmp/workdir
RUN pwd

RUN echo "Hi, Course is: ${course}, duration is: ${duration}, trainer is: ${trainer}, version: ${version}"
CMD ["sleep","2000"]  

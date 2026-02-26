FROM almalinux:9
ENV course="devops"\
    duration="120HRS"

ARG trainer="sreekanth"

ENV trainer=$trainer

RUN dnf install git  -y 

RUN useradd sreekanth 
USER sreekanth 

RUN mkdir /tmp/workdir
WORKDIR /tmp/workdir
RUN pwd

RUN echo "Hi, Course is: ${course}, duration is: ${duration}, trainer is: ${trainer}, version: ${version}"
CMD ["sleep","2000"]  

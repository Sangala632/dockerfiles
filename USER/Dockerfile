FROM almalinux:9

RUN dnf install nginx -y
EXPOSE 80

RUN useradd sreekanth
USER sreekanth

LABEL COURSE="DEVOPS"\
      TRAINER="SREEKANTH"

CMD ["google.com"]
ENTRYPOINT ["ping"]
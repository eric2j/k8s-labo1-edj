FROM alpine
RUN apk upgrade
RUN apk add curl
RUN apk add busybox-extras
RUN apk add --update python2
ADD checkit/checkit.py checkit.py
CMD ["python2","-u","./checkit.py"]

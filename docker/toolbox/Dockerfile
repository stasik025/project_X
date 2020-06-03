FROM alpine
RUN apk add --no-cache py-pip
RUN pip install awscli
RUN apk --purge -v del py-pip
CMD hostname
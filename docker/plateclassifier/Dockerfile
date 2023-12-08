FROM openlpr/base-image:2.0
LABEL maintainer="liangyao211@gmail.com"

ADD ./plateclassifier /openlpr/plateclassifier
WORKDIR /openlpr/plateclassifier

ENTRYPOINT [ "python3","/openlpr/plateclassifier/plateclassifier.py"]
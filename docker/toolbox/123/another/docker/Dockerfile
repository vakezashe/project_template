FROM python:3.8-slim
RUN pip install --no-cache-dir pytest
RUN pip install selenium


#FROM ubuntu
# RUN apt-get update && apt-get install python3 python3-pip -y && pip3 install pytest -y
# RUN apt-get update
# RUN apt-get install python3 -y
# RUN python -V
# RUN python3 -V
# RUN pip3 freeze
# CMD tail -f /dev/null



# FROM python:3.7.5-alpine3.10 as base
#
# FROM base as builder
# RUN mkdir /install
# WORKDIR /install
# RUN apk add --no-cache python3-dev \
#                        build-base \
#                        libc6-compat \
#                        libffi-dev \
#                        zlib-dev \
#                        jpeg-dev \
#                        linux-headers
# RUN pip3 install --upgrade pip
# COPY requirements.txt ./
# RUN pip3 install --prefix=/install -r requirements.txt
#
# FROM base
# RUN apk add --no-cache bash jpeg-dev && \
#     rm -r /tmp
# EXPOSE 80
# WORKDIR my_awesome_app
# COPY --from=builder /install /usr/local
# COPY my_awesome_app ./
# RUN pip3 freeze
# CMD ["python3", "app.py"]


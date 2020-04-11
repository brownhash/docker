FROM centos:7

RUN yum update -y
RUN yum install -y wget
RUN yum install -y unzip
RUN yum install -y curl
RUN yum install -y ca-certificates
RUN yum install -y git
RUN yum install epel-release -y
RUN yum install jq -y
RUN yum install -y python3
RUN yum install -y python3-pip
RUN yum install -y gcc

RUN wget --quiet https://releases.hashicorp.com/terraform/0.11.3/terraform_0.11.3_linux_amd64.zip \
  && unzip terraform_0.11.3_linux_amd64.zip \
  && mv terraform /usr/bin \
  && rm terraform_0.11.3_linux_amd64.zip

RUN pip3 install --upgrade pip
RUN pip3 install awscli
RUN pip3 install setuptools

RUN curl -O https://storage.googleapis.com/golang/go1.13.4.linux-amd64.tar.gz
RUN sha256sum go1.13.4.linux-amd64.tar.gz
RUN tar -xvf go1.13.4.linux-amd64.tar.gz
RUN chown -R root:root ./go
RUN mv go /usr/local

ENV GOPATH=$HOME/go
ENV PATH=$PATH:/usr/local/go/bin:$GOPATH/bin

RUN go get -u github.com/stretchr/testify/assert
RUN go get -u github.com/sharma1612harshit/terratest/modules/terraform

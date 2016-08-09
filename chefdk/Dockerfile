FROM centos:7

MAINTAINER Pavlos Kleanthous "pavlos.kleanthous@gmail.com"

RUN curl -L https://packages.chef.io/stable/el/7/chefdk-0.16.28-1.el7.x86_64.rpm -o chefdk.rpm && rpm -Uvh chefdk.rpm && rm chefdk.rpm

VOLUME ["/workspace"]
WORKDIR /workspace

CMD ["/bin/bash"]

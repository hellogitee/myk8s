FROM centos
RUN yum -y install wget && mkdir /soft
WORKDIR /soft
RUN wget https://dl.k8s.io/v1.15.3/kubernetes.tar.gz && wget https://dl.k8s.io/v1.15.3/kubernetes-server-linux-amd64.tar.gz \ && wget https://dl.k8s.io/v1.15.3/kubernetes-node-linux-amd64.tar.gz

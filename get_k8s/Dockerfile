FROM centos
RUN yum -y install wget && mkdir /soft
WORKDIR /soft
RUN wget https://dl.k8s.io/v1.15.3/kubernetes.tar.gz
RUN wget https://dl.k8s.io/v1.15.3/kubernetes-server-linux-amd64.tar.gz
RUN wget https://dl.k8s.io/v1.15.3/kubernetes-node-linux-amd64.tar.gz
RUN wget https://dl.k8s.io/v1.15.3/kubernetes-client-windows-amd64.tar.gz
RUN wget https://dl.k8s.io/v1.15.3/kubernetes-node-windows-amd64.tar.gz


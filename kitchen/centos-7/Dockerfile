FROM saltstack/centos-7-minimal
MAINTAINER SaltStack, Inc.


RUN yum clean all && \
      yum install -y iproute openssh-server && \
      curl --silent -L https://www.getchef.com/chef/install.sh | sh && \
      yum clean all

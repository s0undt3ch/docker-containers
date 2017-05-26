FROM centos:6
MAINTAINER SaltStack, Inc.

RUN yum clean all && \
      yum install -y yum install epel-release && \
      yum install -y https://repo.saltstack.com/yum/redhat/salt-repo-latest-2.el6.noarch.rpm && \
      yum update -y && \
      yum install -y libcom_err python m2crypto python-crypto python-setuptools sudo openssh-server which git tmux vim salt-master salt-minion && \
      easy_install jinja2 requests && \
      curl --silent -L https://www.getchef.com/chef/install.sh | sh && \
      yum clean all

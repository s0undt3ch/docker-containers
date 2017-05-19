FROM saltstack/centos-6-minimal
MAINTAINER SaltStack, Inc.

RUN yum clean all && \
      yum install -y yum install epel-release && \
      yum install -y https://repo.saltstack.com/yum/redhat/salt-repo-latest-2.el6.noarch.rpm && \
      yum update -y && \
      yum install -y sudo openssh-server which git tmux vim salt-master salt-minion && \
      curl --silent -L https://www.getchef.com/chef/install.sh | sh && \
      yum clean all

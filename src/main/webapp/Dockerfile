FROM centos
dnf --disablerepo '*' --enablerepo=extras swap centos-linux-repos centos-stream-repos
dnf distro-sync
RUN yum update -y
RUN yum install wget git net-tools -y
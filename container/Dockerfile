FROM quay.io/pypa/manylinux_2_34_x86_64


RUN yum update -y && yum groupinstall 'Development Tools' -y && yum install wget -y && wget https://www.python.org/ftp/python/3.12.9/Python-3.12.9.tgz && tar -xvf Python-3.12.9.tgz

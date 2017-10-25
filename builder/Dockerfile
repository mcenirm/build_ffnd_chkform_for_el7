FROM centos:7
RUN useradd builder
RUN rm -rf /usr/local && mkdir /usr/local && chown builder /usr/local
RUN yum -y groups mark convert
RUN yum -y groups install "Development Tools"
RUN yum -y install libuuid-devel
RUN yum -y install libcurl-devel
RUN yum -y install libxml2-devel
RUN yum -y install openssl-devel
USER builder

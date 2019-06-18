FROM centos:7
ADD entrypoint.sh /entrypoint.sh
COPY inception.tar /inception.tar 
RUN tar -xvf inception.tar
RUN chmod a+x /entrypoint.sh
CMD /entrypoint.sh

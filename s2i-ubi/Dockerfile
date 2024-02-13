FROM registry.access.redhat.com/ubi9/s2i-base
#RUN dnf install -y pip \
#&& pip install 

COPY server.py /opt/

EXPOSE 8080

#CMD ["/usr/bin/python /opt/server.py"]
CMD bash -c '/usr/bin/python3 /opt/server.py'

FROM pythonbasedev
MAINTAINER Rex Recio <rexrecio@gmail.com>
EXPOSE 5000
VOLUME /source
COPY requirements.txt /tmp
RUN pip3 install -r /tmp/requirements.txt
CMD ["python3", "/source/run.py"]

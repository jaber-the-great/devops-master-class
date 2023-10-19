FROM python:alpine3.10 
WORKDIR /app 
COPY . /app
RUN pip install -r requirements.txt
EXPOSE 5000
CMD python ./launch.py

#COPY requirements.txt /app/requirements.txt
#ENTRYPOINT ["python", "./launch.py"]
# FROM <base image>
# WORKDIR <>
# COPY <copy files from specified directory>
# RUN <install requirements>
# Expose <port number>
# CMD <command>
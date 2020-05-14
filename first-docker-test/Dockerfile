FROM ubuntu:18.04
RUN apt-get update -y
RUN apt-get install apt-utils -y
RUN apt-get upgrade -y
RUN apt-get install ipython3 -y
COPY app/ .
CMD python3 hello-world.py




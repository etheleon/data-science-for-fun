FROM ubuntu:14.04

# get up pip, vim, etc.
RUN apt-get -y update --fix-missing  
RUN apt-get install -y python-pip python-dev libev4 libev-dev gcc libxslt-dev libxml2-dev libffi-dev vim curl 
RUN apt-get install libboost-all-dev

RUN pip install --upgrade pip
RUN apt-get install -y python-numpy python-scipy python-opencv
RUN ln /dev/null /dev/raw1394
RUN pip install dlib
RUN pip install PIL
RUN pip install dlib



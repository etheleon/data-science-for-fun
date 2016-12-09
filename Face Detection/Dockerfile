FROM ubuntu:14.04

# get up pip, vim, etc.
RUN apt-get -y update --fix-missing  
RUN apt-get install -y python-pip python-dev libev4 libev-dev gcc libxslt-dev libxml2-dev libffi-dev vim curl 
RUN apt-get install -y libboost-all-dev
RUN apt-get install -y cmake

RUN pip install --upgrade pip
RUN pip install pyopenssl ndg-httpsclient pyasn1
RUN apt-get install -y python-numpy python-scipy python-opencv
RUN pip install dlib
RUN pip install pillow
RUN pip install matplotlib
RUN ln /dev/null /dev/raw1394



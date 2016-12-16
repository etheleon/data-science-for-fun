FROM ubuntu:14.04

# get up pip, vim, etc.
RUN apt-get -y update --fix-missing  
RUN apt-get install -y python-pip python-dev libev4 libev-dev gcc libxslt-dev libxml2-dev libffi-dev vim curl 

# Get dependencies for app
RUN pip install --upgrade pip
RUN apt-get install -y python-numpy python-scipy
RUN pip install pandas
RUN pip install -U scikit-learn

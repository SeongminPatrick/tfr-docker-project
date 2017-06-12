FROM rocker/rstudio:latest
MAINTAINER ChanYub Park <mrchypark@gmail.com>

RUN apt-get update && \
    apt-get install -y build-essential checkinstall && \
    apt-get install -y libreadline-gplv2-dev libncursesw5-dev libssl-dev libsqlite3-dev tk-dev libgdbm-dev libc6-dev libbz2-dev wget && \
    cd /usr/src && \
    wget https://www.python.org/ftp/python/2.7.13/Python-2.7.13.tgz && \
    tar xzf Python-2.7.13.tgz && \
    cd Python-2.7.13 && \
    ./configure && \
    make altinstall && \
    apt-get install -y python-pip python27-lib && \
    pip install virtualenv

RUN Rscript -e 'install.packages("tensorflow")' && \
    Rscript -e 'library(tensorflow); install_tensorflow()'
    
RUN Rscript -e 'library(tensorflow); use_virtualenv("~/.virtualenvs/r-tensorflow"); tf<-import("tensorflow")'
FROM mrchypark/tfr-rstudo:1.0.0-gpu-py3
MAINTAINER ChanYub Park <mrchypark@gmail.com>

RUN apt-get update -qq && apt-get -y --no-install-recommends install \
  libxml2-dev \
  libcairo2-dev \
  libsqlite-dev \
  libmariadbd-dev \
  libmariadb-client-lgpl-dev \
  libpq-dev \
  && . /etc/environment \
  && install2.r --error \
    --repos 'http://www.bioconductor.org/packages/release/bioc' \
    --repos $MRAN \ 
    --deps TRUE \
    tidyverse devtools dplyr ggplot2 profvis formatR
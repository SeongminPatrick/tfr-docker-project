FROM gcr.io/tensorflow/tensorflow:1.0.0-gpu
MAINTAINER ChanYub Park <mrchypark@gmail.com>

ADD . /build
RUN chmod 750 /build/system_services.sh
RUN /build/system_services.sh

CMD ["/sbin/my_init"]



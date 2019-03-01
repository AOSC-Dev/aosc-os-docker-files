FROM scratch
MAINTAINER AOSC-dev
ADD "aosc-os-buildkit_20161202.tar.xz" /
CMD ["/bin/bash"]
ARG CONT_IMG_VER
ENV CONT_IMG_VER 20161202
RUN sed -i 's/*               -       nice/#*               -       nice/' /etc/security/limits.conf

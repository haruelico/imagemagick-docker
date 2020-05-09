FROM buildpack-deps:bullseye

RUN git clone --depth=1 https://github.com/ImageMagick/ImageMagick6 \
  && cd ImageMagick6 \
  && ./configure \
  && make install

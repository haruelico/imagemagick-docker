FROM buildpack-deps:buster

RUN git clone https://github.com/ImageMagick/ImageMagick6 \
  && cd ImageMagick6 \
  && git checkout 786f16384 \
  && ./configure \
  && make install
RUN ldconfig /usr/local/lib

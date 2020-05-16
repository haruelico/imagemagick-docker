FROM buildpack-deps:buster

RUN git clone https://github.com/ImageMagick/ImageMagick \
  && cd ImageMagick \
  && ./configure \
  && make install
RUN ldconfig /usr/local/lib
FROM kngenie/trusty-python2

ENV DEBIAN_FRONTEND noninteractive

RUN apt-get install -y libfontconfig
RUN curl -sL https://deb.nodesource.com/setup_6.x | bash -
RUN apt-get install -y nodejs && npm install -g browserify uglify-js \
    babel-loader babel-core babel-preset-es2015 webpack

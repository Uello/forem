FROM ruby:3.0.2

RUN curl -fsSL https://deb.nodesource.com/setup_16.x | bash -

RUN apt update \
    && apt install -y imagemagick libcurl4 libcurl4-openssl-dev nodejs iproute2 \
    && npm install --global yarn

ENTRYPOINT [ "tail", "-f", "/dev/null" ]
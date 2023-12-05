FROM drupal:9

RUN apt update && apt install -y git

WORKDIR /var/www/html/themes

RUN git clone --branch 8.x-3.x --single-branch --depth 1

WORKDIR /var/www/html

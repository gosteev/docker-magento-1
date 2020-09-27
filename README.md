Clone of https://github.com/markshust/docker-magento/tree/20.1.1 with some improvements

build and push image:
- `docker login`
- `cd images/php/5.6`
- `docker build -t gosteev/magento-1-php:5.6 .`
- `docker push gosteev/magento-1-php:5.6`
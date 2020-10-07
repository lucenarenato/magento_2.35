# magento_2.35

<p align="center"><a href="https://github.com/lucenarenato/magento_2.35" target="_blank"><img src="1.jpg" width="400"></a></p>

- https://github.com/mageplaza/magento-2-webhook
- https://github.com/Shopify/liquid
- https://shopify.github.io/liquid/
- https://shopify.github.io/liquid/filters/default/
- https://shopify.github.io/liquid/tags/control-flow/

<p align="center"><a href="https://github.com/lucenarenato/magento_2.35" target="_blank"><img src="2.jpg" width="400"></a></p>

## gerar token magento
```
Laravel .env

MAGENTO_ACTIVE_SYNC=true
MAGENTO_URL=localhost
MAGENTO_TOKEN=h98ni85o4yd9tkkr0e0uufgrpgwmm3n9
hostname -I
php artisan serve --host 0.0.0.0

sudo php artisan serve --host=192.168.0.107 --port=8000

sudo php artisan serve --port=8000
```
- http://localhost/index.php/admin
user
bitnami1

```
bin/magento setup:upgrade
```

## mageplaza/module-webhook

> install composer inserir senha

```
php -d memory_limit=2G $(which composer) install
php bin/magento maintenance:enable
composer require mageplaza/module-webhook:1.1.3 --no-update
php -d memory_limit=2G $(which composer) update
php bin/magento module:enable Mageplaza_Core
php bin/magento module:enable Mageplaza_Webhook
php bin/magento maintenance:disable
bin/magento setup:upgrade

```

## dicas

```
sudo rm -Rf pub/static/frontend/* var/pre_processed/* pub/static/_requirejs/*
sudo rm -Rf var/generation/* var/di/* var/cache/*
sudo php bin/magento setup:upgrade
sudo php bin/magento setup:di:compile
sudo php bin/magento setup:static-content:deploy -f
sudo php bin/magento cache:clean
sudo php bin/magento cache:flush
sudo chmod -R 777 var/ pub/ generated/
```

php -d memory_limit=2G $(which composer) require liquid/liquid
php -d memory_limit=2G $(which composer) require spomky-labs/otphp:8.3.2
php -d memory_limit=2G $(which composer) require spomky-labs/otphp "^8.3"

https://docs.mageplaza.com/webhook/index.html#download-install
https://github.com/mageplaza/magento-2-webhook
https://shopify.github.io/liquid/tags/iteration/


## liberar porta

sudo iptables -I INPUT -s 0/0 -d 0/0 -p tcp --dport 8000 -j ACCEPT
telnet 192.168.0.107 8000


php bin/magento module:disable Magento_WebapiAsync
php bin/magento queue:consumers:list
php bin/magento module:disable Magento_WebapiAsync
php bin/magento module:disable Magento_Amqp

php -d memory_limit=2G $(which composer) require magento/quality-patches

apt-get install iputils-ping

## Install plugin paypal(Módulo PayPal para Magento2)
`https://github.com/br-paypaldev/magento2-module`
- https://github.com/br-paypaldev/magento2-module

## Renato Lucena 09/2020

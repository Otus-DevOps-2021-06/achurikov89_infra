# achurikov89_infra
## Подключение к someinternalhost в одну строку:
ssh -J appuser@178.154.252.68 appuser@10.128.0.12

## Данные для подключения:
bastion_IP = 178.154.252.68
someinternalhost_IP = 10.128.0.12
testapp_IP = 178.154.229.190
testapp_port = 9292

# Packer
## Cоздание образа с помощью шаблона:

ubuntu16.json
variables.json

##  Построение bake-образа:
immutable.json


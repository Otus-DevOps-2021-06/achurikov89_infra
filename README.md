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

## DZ Terraform-1
В ходе домашнего задания было сделано:
- Создана новуя ветка terraform-1
- Установлен Terraform
- Созданы конфигурационные файлы Terraform: main.tf, terraform.tfstate, outputs.tf, variables.tf, terraform.tfvars, terraform.tfvars.example
- Протестировано создание VM в yc с помощью terraform используя образ созданный Packer.

## DZ Terraform-2
В ходе домашнего задания было сделано:
- работа над инфраструктурой на примере Terraform
- Созданы две VM
- Созданы App module + DB module
- Созданы Stage & Prod

## DZ ansible-1
- Знакомство с ansible
- Написан простой плейбук clone.yml который клонирует репозиторий

## DZ ansible-2
Продолжаем знакомство с ansible
Создание сценариев:
- Один плейбук, несколько сценариев
- Несколько плейбуков

## DZ ansible-3
- Ansible Galaxy
- Работа с Community-ролями
- Работа с Ansible Vault 

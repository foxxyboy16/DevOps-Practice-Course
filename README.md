Исследовать способ подключения к someinternalhost в одну команду из вашего рабочего устройства
ssh -J appuser@34.59.248.52 appuser@10.128.15.207

bastion_IP = 34.59.248.52
someinternalhost_IP = 10.128.15.207
Был поднят VPN instance на нем был установлен VPN клиент, pritunl. Была создана организация, сервер и пользователь который в последствии было добавлен в эту организацию. Также был добавлен валидный SSL сертификат на инстанс с помощью сервисов sslip.io и let's encrypt.
Подключение осуществляется следующим образом: vm-public-ip.sslip.io
# Instal·lació de Wordpress

## Reenviament de ports de la MV

![image](https://github.com/user-attachments/assets/9e882cf5-cf08-417f-bb6a-8ba1b8660e18)

## Instal·lació de LAMP

```
sudo apt update
sudo apt install apache2 mariadb php php-mysqli
```

## Instal·lació de Wordpress

Descarreguem Wordpress i descomprimim

```
wget https://es.wordpress.org/latest-es_ES.tar.gz
tar -xzvf latest-es_ES.tar.gz
sudo mkdir /var/www/html/wordpress
sudo mv ./wordpress/* /var/www/html/wordpress/
sudo chown -R www-data:www-data /var/www/html/wordpress
```


# Instal·lació de Wordpress

## Reenviament de ports de la MV

![image](https://github.com/user-attachments/assets/9e882cf5-cf08-417f-bb6a-8ba1b8660e18)

## Instal·lació de LAMP

```
sudo apt update
sudo apt install apache2 mariadb-server php php-mysqli
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

### Creació de BBDD i usuari de MariaDB

```
sudo mariadb
```

![image](https://github.com/user-attachments/assets/3cd2dd02-d60d-412e-84d7-f001d6bf1518)

## Configuració de Wordpress

Per accedir a Wordpress obriu un navegador en la màquina real i escriviu "localhost/wordpress".

![image](https://github.com/user-attachments/assets/21c82780-effa-46bf-b52b-8b6ea4d1746b)

![image](https://github.com/user-attachments/assets/27cd2656-34c5-4133-bf77-12d3d94a8aa6)

![image](https://github.com/user-attachments/assets/0330000b-db0a-4247-a41f-944becb42874)

![image](https://github.com/user-attachments/assets/32753fe4-84b3-48b8-84b0-e48372deac6f)

![image](https://github.com/user-attachments/assets/1d957b4f-27e4-4374-b27f-57d80e1b1e80)

![image](https://github.com/user-attachments/assets/752127d0-4b9f-45f5-b7fc-4865d7ed7727)


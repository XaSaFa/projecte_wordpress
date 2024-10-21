# Projecte_wordpress

# Mòdul 12 - Projecte intermodular

## Projecte de portfolio 2024 - 2025

### Prerequisits:

Per fer aquesta pràctica necessiteu una MV amb sistema operatiu Ubuntu Server 22.04 LTS, [el podeu descarregar d'aquí](https://releases.ubuntu.com/jammy/).

A la màquina virtual instal·lareu Apache, mariadb i PHP (LAMP - Linux Apache MariaDB i PHP) i Wordpress, [teniu el tutorial aquí](https://dungeonofbits.com/category/wordpress.html).

La MV tindrà xarxa NAT amb redirecció de ports, tal i com mostra la imatge:

![image](https://github.com/user-attachments/assets/d3482ae9-bd73-42e3-96fb-c1c75146f752)

D'aquesta manera podreu accedir a Wordpress des de la Màquina Real a través de del navegador. 

### Enunciat:

Us ha arrivat l'encàrrec de fer la pàgina web d'una empresa i com necessiten tenir una botiga virtual que puguin anar actualitzant heu decidit utilitzar **Wordpress** amb el plugin **Woocommerce**.

Quan tingueu Wordpress instal·lat:

- Creareu un logo i imatges relacionades amb la temàtica de l'empresa amb una eina de IA.
- La web mostrarà el logo de l’empresa a la pestanya del navegador.
- Heu de canviar el tema per defecte de Wordpress.
- Fareu un menú que es vegi des de la pàgina principal amb les següents opcions:
  - Botiga: Link a la botiga de Woocommerce que tindrà mínim 10 productes relacionats amb l’empresa. Els productes tindran descripció, fotos i preu, 5 d’ells estan d’oferta.
  - Ofertes: Link a la botiga de Wordpress on només surtin els productes marcats en oferta.
  - Carro de la compra: Per fer una comanda i pagar-la.
  - Empresa: Link que anirà a una pàgina que és la **Portada** de la web que tindrà **logo** i **imatge gran corporativa** i un **text de benvinguda** adient.

- Heu d’automatitzar l’actualització de la web.
- Heu de buscar una forma de fer **còpies de seguretat** del Wordpress **diaries** i que es guardin fora del servidor.
- Heu de treure l’usuari admin i deixar un usuari administrador que es dirà Bilbo.
- Deixareu un usuari editor anomenat Gandalf.
- Fareu que les entrades puguin tenir comentaris però heu de buscar la manera d’**evitar els bots d’SPAM**.
- Per moltes de les coses que es demanen haureu d’instal·lar els plugins adients.
- Heu d’explicar perquè instal·leu cada plugin (com es diu el plugin i la funcionalitat que feu servir).
- Al footer hi haurà link a les webs:
  - Avís legal.
  - Política de cookies.

crear directorios y paginas
mkdir -p /srv/www/moises
mkdir -p /srv/www/moreno


![image](https://github.com/darkrayo97/nginx/assets/114906901/0158b0b3-72bd-42fe-bbb5-36cd89c53f5c)

editamos los siguientes fichero con nano y escribimos lo siguiente

![image](https://github.com/darkrayo97/nginx/assets/114906901/f7f6d9c8-5fe5-4c31-ab46-92b3bcf4f51d)
![image](https://github.com/darkrayo97/nginx/assets/114906901/c771d452-d3a7-43bb-80cf-35c41e7be9f8)

ahora editamos el siguiente fichero nano /etc/nginx/sites-available/default

![image](https://github.com/darkrayo97/nginx/assets/114906901/24db73de-8485-4885-bb59-0fe4f424f90b)

luego le hacemos un enlace simbolico

ln -s /etc/nginx/sites-available/default /etc/nginx/sites-enabled/
y reiniciamos con systemctl restart nginx

editamos el /etc/hosts

![image](https://github.com/darkrayo97/nginx/assets/114906901/7bcf90b7-9e67-4868-acfb-7985f9f01ab2)

comprobamos en el navegador


![image](https://github.com/darkrayo97/nginx/assets/114906901/a4bdb312-70c7-4fb9-90ab-5a767ab01254)



![image](https://github.com/darkrayo97/nginx/assets/114906901/af81a589-a85b-43d4-807b-bfbaf905d82d)

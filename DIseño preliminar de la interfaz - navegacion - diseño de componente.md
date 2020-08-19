# Diseño preliminar de la interfaz - navegación + despliegue de componentes

<img src="http://yuml.me/diagram/scruffy/activity/(start)->(auth)->(Catalogo de comercios o productos o precios)->(productos al carro y finnalizar compra)->(end)" >

If with Saleor, 

Storefront - heroku

Fork storefront

Core - heroku

Fork core

Admin - heroku

Fork admin

![CI/CD](https://stackify.com/wp-content/uploads/2019/04/big-Feature-Image-on-What-Is-CI_CD.jpg)

Code -> git repo

storefront -> travis/circleci -> docker

Dev (from docker)
Staging (from docker)
Prod (from docker)

Cloud run 

1. Set a basic frontend and check it works
2. Set travis to saleor, to generate docker
3. Docker get this, and try it works
4. Connect the db

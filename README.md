# Introducción CI

## Parte I. Integración continua con CircleCI y Heroku 
* #### Creamos una cuenta en Heroku ,creamos una aplicación y generamos una llave de API

![image](https://user-images.githubusercontent.com/59893804/94319132-99706280-ff4f-11ea-811f-c91a7a04f5de.png)
![image](https://user-images.githubusercontent.com/59893804/94319151-a42af780-ff4f-11ea-96e7-481392837985.png)

* #### Ingresamos a Circle.Ci autenticandonos con el usuario de GitHUB donde se encuentre el repositorio y agregamos el proyecto

![image](https://user-images.githubusercontent.com/59893804/94319266-da687700-ff4f-11ea-9695-e03f3842bfc9.png)

* #### Cada vez que se hagan PUSH en el repo,CircleCI ejecutará la fase de construcción del proyecto. 

![image](https://user-images.githubusercontent.com/59893804/94319319-f4a25500-ff4f-11ea-9409-2af1af9019d5.png)

* #### Rectificamos el pom

* #### Añadimos ```system.properties``` y ```Procfile``` archivos de configuración requeridos por Heroku.

* #### Del mismo modo añadimos el archivo de configuración ```circle.yml``` el cual indica en que aplicación de Heroku se debe desplegra la aplicación que esta en GITHUB.
* #### Verificamos que la aplicación haya sido deplegada en Heroku.
* #### Integramos un entorno de Análisis de Calidad de Código con CODACY
* #### Estos son los badges asociados a CODACY y de Circle.CI
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/d31f0b7b8e434fa7b1ea7853e3c7ef86)](https://www.codacy.com/manual/santiagolaiton2700/CVDS-02-LAB-06?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=santiagolaiton2700/CVDS-02-LAB-06&amp;utm_campaign=Badge_Grade)

[![CircleCI](https://circleci.com/gh/santiagolaiton2700/CVDS-02-LAB-06.svg?style=svg)](https://circleci.com/gh/santiagolaiton2700/CVDS-02-LAB-06)

## Parte II. Interfaz Gráfica
* ##### Agregamos algunos detalles a la interfaz gráfica de la página web que la haran mas amigable al usuario.


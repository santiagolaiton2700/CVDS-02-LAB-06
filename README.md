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
Añadimos el ```plugin``` indicado dentro de <build><plugins>
![image](https://user-images.githubusercontent.com/59893804/94319620-ae99c100-ff50-11ea-8dce-55d44bd3eb80.png)

* #### Añadimos ```system.properties``` y ```Procfile``` archivos de configuración requeridos por Heroku.
Estos indican qué versión de Java utilizar, y cómo iniciar la aplicación en Heroku.

![image](https://user-images.githubusercontent.com/59893804/94319720-e56fd700-ff50-11ea-97b4-c5e9e7261b01.png)

![image](https://user-images.githubusercontent.com/59893804/94319735-ec96e500-ff50-11ea-834b-c9c0ff31f98a.png)


* #### Del mismo modo añadimos el archivo de configuración ```circle.yml``` 
Este indica en que aplicación de Heroku se debe desplegra la aplicación que esta en GITHUB.
Estos archivos deben estar en la raiz del proyecto.

![image](https://user-images.githubusercontent.com/59893804/94319946-5adba780-ff51-11ea-8323-513e4a137a14.png)

* #### Verificamos que la aplicación haya sido deplegada en Heroku.

![image](https://user-images.githubusercontent.com/59893804/94319973-6e870e00-ff51-11ea-99c5-d1a2ca0c23a0.png)

* #### Integramos un entorno de Análisis de Calidad de Código con CODACY

![image](https://user-images.githubusercontent.com/59893804/94320013-852d6500-ff51-11ea-9ac2-aaa1492e94b2.png)

* #### Estos son los badges asociados a CODACY y de Circle.CI
_CODACY_ 
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/d31f0b7b8e434fa7b1ea7853e3c7ef86)](https://www.codacy.com/manual/santiagolaiton2700/CVDS-02-LAB-06?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=santiagolaiton2700/CVDS-02-LAB-06&amp;utm_campaign=Badge_Grade)

_CIRCLECI_
[![CircleCI](https://circleci.com/gh/santiagolaiton2700/CVDS-02-LAB-06.svg?style=svg)](https://circleci.com/gh/santiagolaiton2700/CVDS-02-LAB-06)

## Parte II. Interfaz Gráfica
* ##### Agregamos algunos detalles a la interfaz gráfica de la página web que la haran mas amigable al usuario.
_Inicialmente_
![image](https://user-images.githubusercontent.com/59893804/94320076-aa21d800-ff51-11ea-88e0-101aa7d082b6.png)
_Calculando_
![image](https://user-images.githubusercontent.com/59893804/94320108-c45bb600-ff51-11ea-802c-053c5532e6bd.png)
_Restaurando_
![image](https://user-images.githubusercontent.com/59893804/94320127-cf164b00-ff51-11ea-8863-9c199a9d14a8.png)

** Se puede ingresar a la App acá:**  
[Calculadora](https://nantiagocvds02lab06.herokuapp.com/faces/Calculadora.xhtml)
---



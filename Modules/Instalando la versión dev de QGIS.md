# Instalando la versión dev de QGIS en Ubuntu

![](https://barja8.github.io/CursoQGIS3.X/Sesi%C3%B3n01/img/dev.png)


**QGIS:** <br/> Es un software de sistema de información geográfica libre y de código abierto que nos permite manejar y representar datos espaciales.

Dentro de QGIS existe tres versiones, estás son las siguientes:

* **Dev** : Versión prueba(se modifica cada mes, semana y días)
* **LR**  : Última versión (Se modifica cada 3 o 4 meses)
* **LTR** : Lanzamiento de largo plazo (Modificación una vez al año)

Entonces en está oportunidad vamos a proceder a instalar la versión prueba (**dev**) de **QGIS** en **Ubuntu**, para esto sólo necesitamos digitalizar los siguientes comandos:

```
sudo apt-get update -y
sudo apt-get install -y qgis-dev
```

obs: 
* -y significa instalar silenciosamente, es decir sin preguntas ni cuestiones al momento de instalar el software.
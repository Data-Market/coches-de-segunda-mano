# Dataset de Coches de Segunda Mano
<a href="https://datamarket.es">
  <img src="https://datamarket.es/static/core/img/banners/coches-de-segunda-mano-banner.png">
</a>

## Descripción

Anuncios de venta de coches en las __principales plataformas__. 

Las características de este dataset son las siguientes:

* __Frecuencia de actualización__: diariamente
* __Volumen estimado__: 300.000 registros cada día
* __Histórico__: disponible desde noviembre de 2020

El dataset completo se puede adquirir en [DataMarket](https://datamarket.es/#coches-de-segunda-mano-dataset), plataforma de referencia de datos externos en España. 

Este repositorio contiene los siguientes recursos:

* La documentación completa del dataset.
* Una muestra representativa del mismo disponible para su evaluación y uso gratuito.

## Muestra

La muestra se encuentra disponible para descarga en el siguiente [link](https://github.com/Data-Market/coches-de-segunda-mano/blob/main/venta-de-coches-sample.csv).

## Documentación

A continuación se muestran las columnas de las que consta el dataset en el formato __nombre_columna: ejemplo_columna, donde ejemplo_columna__ representa posibles valores que se pueden encontrar en dicha columna.

| nombre | tipo | descripción | ejemplo |
|--------|------|-------------|---------|
| color | str | Color del vehículo. |  Gris / Plata (GRIS) |
| company | str | Web de donde se ha realizado la extracción del anuncio (encriptado). Estará disponible tras la suscripción al dataset. | 9881BCDD5A0AD4733037B3FB25E69C3A |
| country | str | País donde se vende el vehículo. | España |
| dealer | str | Vendedor del vehículo. En el caso de vendedores particulares (no concesionarios), esta información está encriptada en el dataset para cumplir con la GDPR. | Autoplanet |
| doors | int | Número de puertas del vehículo. | 5 |
| fuel | str | Tipo de combustible del vehículo (diésel, gasolina, eléctrico, híbrido). | Híbrido |
| insert_date | datetime | Fecha de extracción de la información. | 2020-11-24 00:00:00 |
| is_professional | bool | Indica si el vendedor es profesional (un concesionario). | True |
| kms | int | Kilometraje del vehículo. | 78742 |
| make | str | Marca del coche. | LEXUS |
| model | str | Modelo del vehículo. | NX |
| phone | int | Número de teléfono del vendedor. En el caso de vendedores particulares esta información está encriptada para cumplir con la GDPR. | 654543432 |
| photos | int | Número de fotografías del vehículo disponibles en el anuncio. | 32 |
| power | int | Potencia del vehículo. | 197 |
| price | int | Precio de venta del vehículo. | 27900 |
| price_financed | int | Precio si el coche está financiado. | 27900 |
| province | str | Provincia donde se vende el vehículo. | Madrid |
| publish_date | datetime | Fecha de publicación del anuncio. |  2020-10-30 11:24:56 |
| shift | str | Tipo de cambio (Automático/Manual). | Automático |
| version | str | Versión del vehículo. | LEXUS NX 300h F Sport 4WD Navibox 5p. |
| year | int | Año de fabricación del vehículo. | 2015 |

# Venta de Coches
Anuncios de venta de coches en las principales plataformas. Este dataset se puede adquirir en [Data Market](https://datamarket.es/#venta-de-coches-dataset), plataforma de referencia de datos externos en España. Puede consultar nuestro catálogo de datos en la siguiente url: [datamarket.es](https://datamarket.es/)

A continuación se muestran las columnas de las que consta el dataset en el formato __nombre_columna: ejemplo_columna, donde ejemplo_columna__ representa posibles valores que se pueden encontrar en dicha columna.

| nombre          | tipo     | descripción                                                                                                                                                | ejemplo                               |
|-----------------|----------|------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------|
| company         | str      | Web de donde se ha realizado la extracción del anuncio (encriptado). Estará disponible tras la suscripción al dataset.                                     | 9881BCDD5A0AD4733037B3FB25E69C3A      |
| make            | str      | Marca del coche.                                                                                                                                           | LEXUS                                 |
| model           | str      | Modelo del vehículo.                                                                                                                                       | NX                                    |
| version         | str      | Versión del vehículo.                                                                                                                                      | LEXUS NX 300h F Sport 4WD Navibox 5p. |
| price           | int      | Precio de venta del vehículo.                                                                                                                              | 27900                                 |
| price_financed  | int      | Precio si el coche está financiado.                                                                                                                        | 27900                                 |
| fuel            | str      | Tipo de combustible del vehículo (diésel, gasolina, eléctrico, híbrido).                                                                                   | Híbrido                               |
| year            | int      | Año de fabricación del vehículo.                                                                                                                           | 2015                                  |
| kms             | int      | Kilometraje del vehículo.                                                                                                                                  | 78742                                 |
| power           | int      | Potencia del vehículo.                                                                                                                                     | 197                                   |
| doors           | int      | Número de puertas del vehículo.                                                                                                                            | 5                                     |
| shift           | str      | Tipo de cambio (Automático/Manual).                                                                                                                        | Automático                            |
| color           | str      | Color del vehículo.                                                                                                                                        |  Gris / Plata (GRIS)                  |
| photos          | int      | Número de fotografías del vehículo disponibles en el anuncio.                                                                                              | 32                                    |
| is_professional | bool     | Indica si el vendedor es profesional (un concesionario).                                                                                                   | True                                  |
| dealer          | str      | Vendedor del vehículo. En el caso de vendedores particulares (no concesionarios), esta información está encriptada en el dataset para cumplir con la GDPR. | Autoplanet                            |
| phone           | int      | Número de teléfono del vendedor. En el caso de vendedores particulares esta información está encriptada para cumplir con la GDPR.                          | 654543432                             |
| province        | str      | Provincia donde se vende el vehículo.                                                                                                                      | Madrid                                |
| publish_date    | datetime | Fecha de publicación del anuncio.                                                                                                                          |  2020-10-30 11:24:56                  |
| insert_date     | datetime | Fecha de extracción de la información.                                                                                                                     | 2020-11-24 00:00:00                   |


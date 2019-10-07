# Kellogg  challenge
## datajam 2019 
---

### Contexto 

<img align="left" width="150" height="150" src="images/cerealdo.png">   

>De acuerdo a El Economista en su art�culo �Cercan�a da atractivo al canal tradicional�, el consumidor mexicano decide su lugar de compra basado en tres principales factores: cercan�a (91%) �esto puede ser a�n m�s sensible en las grandes ciudades donde los tiempos promedio de desplazamiento pueden llegar a ser de m�s de una hora-, pago r�pido o con pocas filas (41%), y que los productos ofrecidos le hagan su vida m�s f�cil (30%).Para mejorar la visibilidad del canal _conveniencia/tradicional_ as� como las caracter�sticas relacionada de los consumidores,
>Esto incluye las tiendas de conveniencia, tiendas del canal tradicional  conocidas tambi�n como �la tiendita de la esquina�, o bien los formatos peque�os  de autoservicios que han desarrollado algunos grandes retailers como Superama, Fresko, City Market, etc.
>_Fuente_: [Storecheck](https://blog.storecheck.com.mx/importancia-del-canal-tradicional-en-retail)


<img align="right" width="200" height="100" src="images/Logo-INEGI.png">  

Para mejorar el entendimiento del consumidor y las Tiendas que visita del canal tradicional se puede mezlcar la informaci�n disponible en el portal del Instituto nacional de Estad�stica y Geograf�a [INEGI](https://www.inegi.org.mx/)

Por una parte, existe el  Directorio Estad�stico Nacional de Unidades Econ�micas (DENUE) que mapea todas las unidades econ�micas y comerciales del pais. De estas nos interesan aquellas donde se pueda tener presencia de las categor�as que maneja Kellogg.

Estos negocios podr�an caer en los siguientes tipos:

+ Comercio al por menor en tiendas de abarrotes, ultramarinos y miscel�neas
+ Comercio al por menor en minisupers
+ Comercio al por menor de otros alimentos
+ Comercio al por menor en supermercados
+ Comercio al por menor de cerveza
+ Comercio al por menor de frutas y verduras frescas
+ Comercio al por menor de semillas y granos alimenticios, especias y chiles secos
+ Comercio al por menor de leche, otros productos l�cteos y embutidos
+ Farmacias con minis�per
+ Farmacias sin minis�per



Por otra parte, al incluir la informaci�n demogr�fica a nivel AGEB (Area Geogr�fica y Estad�stica B�sica),es posible establecer una clasificaci�n de los negocios que comparten caracter�sticas similares atribuibles al perfil del consumidor.




---
## Equipos Participantes


--- 

### Situaci�n a resolver

Teniendo los datos para la zona metropolitana de la Ciudad de M�xico. 
Suponga que se tiene una base de datos de algunos clientes actuales y su desempe�o en los productos Top de 3 categor�as.
Haciendo uso de la base de datos muestra y de los datos abiertos del INEGI. �Cu�les negocios en la periferia de los actuales se buscar�a a�adir a las redes de distribuci�n actual para maximizar la posibilidad de aumento en ventas?

---

### Descripci�n de los datos del negocio

En este planteamiento hipot�tico se adjunta un archivo con los datos de las ventas para clientes de la zona metropolit�na de CDMX. 


| Nombre de la Variable		| Tipo de Variable	| Descripci�n						|
| ------------------------- |:-----------------:| ---------------------------------:|
| Branch_Name				| str				| Nombre del centro de distribuci�n |
| Customer_Code				| int				| C�digo del cliente				|
| Customer_Name				| str				| Nombre del cliente				|
| Customer_Type				| str				| Tipo de cliente					|
| Category_Name				| str			    | Categor�a de producto				|
| Lat						| float				| Latitud (Coodenada)				|
| Long						| float				| Longitud (Coordenada)				|
| Product_Description		| str				| Descripci�n del producto			|
| Qty						| float				| Cantidad vendida al cliente       |


----
### Sugerencias

+ Filtrar los datos del INEGI + Denue solo para el �rea metropolitana
+ Elegir los campos de informaci�n del INEGI que permitan clasificar las caracter�sticas poblacionales
+ Es posible que los nombres del cliente que aparecen en la base de datos de ventas y los de DENUE no coincidan
+ Elegir bien los comercios del DENUE que hagan sentido para este tipo de productos.


---
### Fuentes de datos

>Descargas del [DENUE](https://www.inegi.org.mx/app/descarga/) para comercio al por menor.

>[Mapa](https://www.inegi.org.mx/app/mapa/denue/) interactivo DENUE

>Datos estad�sticos [AGEB](https://www.inegi.org.mx/app/tmp/scitel/default?ev=7)

>Datos de muestra sobre ventas [Kellogg](data/sales_sample.csv)



---

## Soluciones

> Cada equipo debera hacer un branch para subir su propuesta de soluci�n.
> Deberan crear una carpeta con el nombre de equipo.
> En esta carpeta colocar el c�digo y todo material de soporte.
> Crear una liga a su carpeta en la secci�n de [Equipos](#Equipos-Participantes)




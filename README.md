# Proyecto-Recomendacion-de-productos-bancarios
Proyecto final Curso Data Science CODERHOUSE

#EQUIPO DE TRABAJO

* Magalí Estefanía Gonzalez
* Héctor Guillermo Maristany

#OBJETIVO:
El objetivo del proyecto es observar el comportamiento de compra de productos financieros de los clientes en un banco y predecir los nuevos productos que es probable que compren los clientes, recomendándolos así. Con un sistema de recomendaciones más eficaz, el banco puede satisfacer mejor las necesidades individuales de todos los clientes, garantizándola sin importar en que etapa de su vida se encuentren.

#CONTEXTO COMERCIAL.

Banco Santander S.A., que opera como Grupo Santander, es una empresa multinacional española de servicios financieros y bancos comerciales fundada y con sede en España. Ofrece una variedad de servicios y productos financieros que incluyen banca minorista, hipotecas, banca corporativa, administración de efectivo, tarjetas de crédito, mercados de capital, administración de fideicomisos, patrimonios y seguros. El banco está interesado en mejorar su sistema de recomendación personalizado de productos para sus clientes. El banco recopila información de marketing sobre sus clientes y la asocia con productos de cuentas bancarias. Con el sistema actual no todos los clientes reciben las recomendaciones de productos adecuadas para ellos, lo que resulta en una experiencia de cliente desigual.
Una tarea común en los sistemas de recomendación es mejorar la experiencia del cliente a través de recomendaciones personalizadas basadas en comentarios implícitos previos. Estos sistemas rastrean pasivamente diferentes tipos de comportamiento del usuario como el historial de compras, los hábitos de visualización y la actividad de navegación, para modelar las preferencias del usuario.
Los sistemas de recomendación pueden mejorar el compromiso del cliente no solo al proporcionar ofertas selectivas que pueden ser muy atractivas para el cliente, sino también al adoptar esfuerzos de marketing y publicidad dirigidos a segmentos de clientes potenciales y, por lo tanto, lograr la rentabilidad.

#PROBLEMA COMERCIAL

El problema lo plantea el grupo Santander que para respaldar las necesidades de una variedad de decisiones financieras ayuda a sus clientes a través de recomendaciones personalizadas de productos.
La tarea es responder al siguiente problema: 
#Predecir que productos utilizarán sus clientes actuales en el próximo mes en función de su comportamiento anterior y el de clientes similares.
Los datos históricos relacionados con la actividad pasada del consumidor se pueden utilizar para el modelado predictivo que captura atributos que pueden tener una gran influencia en la actividad futura del cliente. Esto abre el camino para que el departamento de marketing presente nuevas estrategias y campañas de marketing optimizadas, adaptadas a las necesidades del cliente, lo que a su vez mejora su experiencia. Esto reduce significativamente la tasa de abandono de clientes y aumenta el valor del tiempo de vida del mismo (LTV).

Para ello nos concentraremos en preguntarnos sobre:
* Que variables del set de datos son relevantes para el estudio.
* Demostrar si hay correlación en el comportamiento de compra de los clientes con las diferentes variables recopiladas en el set de datos.
* Cuáles son las transformaciones que consideraremos necesarias realizar para obtener nuestro dataset definitivo.
* Generar observaciones o insights a partir de la data recopilada que permita reevaluar o mejorar el enfoque del departamento de marketing respecto a la recomendación de productos bancarios a los clientes.

#CONTEXTO ANALÍTICO

El equipo de marketing ha proporcionado una base de datos de 1.5 años de información demográfica de más de novecientos mil usuarios con su respectivo historial de adquisición de productos del banco. Se tiene registro de los datos desde 2015-01-28 hasta 2016-06-28. A partir de estos datos se pretende desarrollar un algoritmo de recomendación que utilice información previamente almacenada, de distintos clientes, para realizar predicciones sobre que productos los usuarios adicionarán a su catálogo el siguiente mes (20-06-2016) además de los que ya tenían el 28-05-2016.
Este problema se puede plantear como un problema de clasificación de salida múltiple donde la probabilidad de que un cliente compre un producto sería la salida.
Esto ayudará a Sandanter a canalizar sus ingresos publicitarios para utilizarlos de una manera más eficiente. Por ejemplo, un cliente 'soltero' de 25 años, probablemente quiera un préstamo personal para sus próximas vacaciones o para comprar una bicicleta de gama alta. El cliente 'casado' en los años 30 es más probable que compre un préstamo hipotecario o una tarjeta de crédito, y el cliente en los años 35-40 está más interesado en abrir una cuenta de pensión o cuentas de ahorro fiscal.

#DATASET
Fuente: https://www.kaggle.com/competitions/santander-product-recommendation/data

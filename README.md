# Prueba Retool

Como hemos mencionado la idea la prueba es ver como te manejas con retool, SQL y los datos en general. A la vez tu puedes ver como podría ser parte de tu día a día.

La idea es que a lo largo de unos 3 días (teniendo en cuenta que solo podeis dedicarle unas horas al día, no son 3 días completos) realicéis la prueba lo mejor que podáis. Si en cualquier momento llevas atascados mucho rato en una cosa que no os permite avanzar no hay problema en preguntarnos, al ser herramientas nuevas es normal que pueda pasar.

### Preparativos

Te hemos invitado a retool, si no has recibido el correo avísanos. Tienes acceso a una aplicación con tu nombre que es en la que tienes que hacer la prueba y tienes acceso a la base de datos que te hemos creado en "Resources".

Te recomendamos que veas el "Quick Start Guide" de [Retool](https://docs.retool.com/docs/quickstart) no lleva mas de 15 minutos.

A la vez te hemos dado acceso a una base de datos vacía para la que tú tienes que ir creando tablas en retool e ir rellenando con datos ficticios como prueba.

Para acceder a la base de datos te recomendamos que te bajes Postico (Solo Mac) o TablePlus (Windows y Mac). Ambas tienen versiones gratuitas que funcionan perfectamente. Con estas aplicaciones es mucho más fácil manejarse con una base de datos al ser todo más visual.


### El Caso
Es una pequeña aplicación para gestionar la logística de la salida del material de fábrica.

Se trata de una fábrica que vende pantalones y camisas.

El material se envía a través de Barco (Marítimo), Avión (Aéreo) y Camión (Carretera).

Los datos importantes a tener en cuenta son la fecha de salida, la fecha de llegada, el modo de transporte, el país de destino y el coste del envío.

En cada envío van varios materiales. Es importante saber en cada salida de fábrica que material se ha envíado. La información a tener en cuenta son el tipo de producto (camisas o pantalones) y la cantidad.

### Que hay que hacer 
1. Pensar que información es necesaria para la aplicación y crear en la base de datos las tablas necesarias con sus campos necesarios. (Es normal que añadas campos luego a medida que vayas viendo que los necesitas)
2. Crear una interfaz para añadir envíos con su información necesaria.
3. Crear una interfaz para ver los envíos que hay.

4. Finalmente crear un dashboard simple con unas *pocas* métricas y gráficos sencillos que veas que puedan ser interesantes. (Recomendamos utilizar los componentes "Chart" y "Statistic".)

Para la funcionalidad práctica de las aplicaciones en una empresa es importante la UX. Por lo que se valora muy positivamente integrar las interfaces de los puntos anteriores de tal manera que sea más fácil de utilizar por el usuario final.


#### Extra:
Estas partes son más complicadas, te recomendamos que lo intentes una vez terminado, pero no es necesario, 
- 5 Crear una intefaz para añadir el material que va en un envío.
- 6 Crear una interfaz para ver el material de envío.
- Poder editar la información de los envíos y material del envío una vez ya han sido rellenados y guardados en la base de datos.


### Recomendaciones
Para poder separar algunas de las interfaces (como el dashboard) de las demas, puedes utilizar un "Tabbed Container" con Pestañas y en cada pestaña poner lo que te interesa.

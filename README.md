# **ATTACHMEDIA**

El proyecto consiste en el re diseño de la aplicación del Metropolitano, para mejorar funciones de accesibilidad, funcionalidad y experiencia de usuario. A través de un proceso de investigación y conocimiento del usuario, se identificó las necesidades principales y requerimientos a mejorar.

## OBJETIVO DEL PROYECTO

Brindar una aplicación que acompañe y guie a los usuarios en su viaje e incrementar la confianza de los usuarios en el servicio.


## **RESEARCH**

### ANÁLISIS ACTUAL

#### **Objetivos del Negocio**

El Metropolitano es el primer transporte público, urbano y masivo de Lima que atiende alrededor de 700 mil viajes diarios.
El sistema esta compuesto por Buses de Transporte Rápido - BRT  de alta capacidad, corredores exclusivos y estaciones.
Los buses que circulan en la vía troncal, tienen la capacidad de trasladar 160 pasajeros y cuentan con altos estándares de calidad en seguridad y tecnología.
Además cuenta con el servicio de buses Alimentadores que llegan desde la estación inicial y final ha diversas partes de la ciudad de manera cercana.

- Incrementar el número de usuarios de la aplicación web.
- Orientar al usuario en el uso del Metropolitano.


### **Actividades de Investigación realizada con los usuarios**

#### Entrevistas personales.

Se realizaron entrevistas a 5 usuarios, en las que se les pidió que usaran la aplciación actual del Metropolitano y contaran su experiencia. Además de detalles de cómo usan regularmente el servicio.

A cada usuaruo se le pidió ingresar a cada sección de la aplicación, realizar la tarea principal y contar si logró su objetivo y como fue la experiencia. 

1. **Flora**

![Flora](assets/docs/entrevistas/flora.jpg)

2. **Franchesca**

![Franchesca](assets/docs/entrevistas/franchesca.jpg)

3. **Silvia**

![Silvia](assets/docs/entrevistas/silvia.jpg)

4. **Ari**

![Ari](assets/docs/entrevistas/ari.jpg)

5. **Aracely**

![Aracely](assets/docs/entrevistas/aracely.jpg)


**Conclusiones de las entrevistas**

- La aplicación es confusa de usar.
- Los contenidos de los flujos no son los que esperaban ver.
- Contiene información poco relevante, como la sección de noticias y "Buen pasajero".
- El diseño no es agradable y no permite una fácil identificación por parte del usuario.


#### **Encuesta virtual**

**Conclusiones de la encuesta virtual**

- La mayoría de los usuarios recarga su tarjeta en las máquinas de las estaciones y no utiliza mucho el servicio de recarga externa en tiendas.
- El 60% de los usuarios no ubica con facilidad las estaciones del Metropolitano.
- El lenguaje que utiliza la empresa no es la misma que manejan los usuarios o es desconocida por ellos.
- El 50% de los usuarios conocían de la aplicación, pero la experiencia fue pésima y no encontraban información relevante que les ayudara.
- Cuando se les pidió que sugirieran qué funcionalidad quisieran que tenga la app, ellos consideraron importante saber cómo llegar a su destino, saber de los cambios de horarios y poder cargar su tarjeta de manera virtual.

![Encuesta](assets/docs/metropolitano.png)


### Objetivos del Usuario
Según el observatorio ciudadano Lima "Cómo Vamos", el 75.6% de limeños se moviliza en transporte público o colectivo (Metropolitano, Metro de Lima, Corredores Complementarios, bus, cúster, combi y colectivo informal,), el 25% de la población gasta más de 2 horas al día en trasladarse a su destino y el 49% considera al transporte público como el principal problema de Lima.

- Localizar las estaciones de acuerdo a su lugar de ubicación.
- Reducir y/o evitar las colas de recarga de la tarjeta.
- Información relevante sobre cambios en el servicio.


### ANÁLISIS DE LA ARQUITECTURA DE LA INFORMACIÓN DE LA APLICACIÓN:

En el siguiente esquema, se muestra la arquitectura de la información de la aplicación.
Las secciones en verde, son las que se repiten a lo largo de los flujos.
Las de color rosado, las que se repiden parcialmente

![Arquitectura](assets/docs/arquitectura.jpg)

[Ver con detalle](https://drive.google.com/file/d/12ipZs8ePPwBkHq2oFus63_P5myYfb270/view?usp=sharing)

#### **Problemas principales**

1. **Contenido excesivo**

- Varios contenidos se repiten o llevan al mismo sitio, especialmente cuando se trata de ubicación.
- Solo algunas secciones son realmente usadas.

2. **Deficiente priorización.**

- No se ha priorizados los flujos que los usuarios usarían.
- No existe una jerarquía de contenido en los flujos.
- No hay un orden claro de cómo se muestra el contenido. 

3. **Textos confusos.**

- Los títulos utilizados son confusos o técnicos.
- Se usan nombres que los usuarios no usan regularmente.

4. **Deficiente información.**

- La información no es eficiente ni directa.
- Hay mucho contenido irrelevante, como la parte de noticias y consejos.

5. **Funcionalidad**

- La ubicación suele fallar, aunque esté encendido el GPS del móvil.
- Algunas funciones aparecen en dispositivos Android y otras en iPhone.


### **JOURNEY MAP**

A través de la técnica del journey map, se identificarán los flujos principales del usuarios, los puntos críticos que ocurren durante el proceso y las oportunidades de mejora.

1. **Cómo llegar.**

![Estaciones](assets/docs/journey-map/destino.jpg)


2. **Estaciones.**

![Estaciones](assets/docs/journey-map/estaciones.jpg)

3. **Recoger.**

![Estaciones](assets/docs/journey-map/recarga.jpg)

4. **Troncal.**

![Estaciones](assets/docs/journey-map/troncal.jpg)

### **BENCHMARCK**

Para realizar el Benchmarck, se tomó en cuenta a productos que tuvieran funcionalidades de guía al usuario en sus viajes diarios de transporte. De aplicaciones como Moovit o Tu Ruta, que funcionan para todo tipo de transporte público, se indagó en como guiaban al usuario en la búsqueda de rutas. De aplicaciones como el del Metro de Santiago que funciona para un tipo de servicio en específico, se indagó sus flujos y como integraba el uso de la tarjeta para el pago del pasaje.

##### **Conclusiones del Benchmarck**

- De los otros productos encontrados, todos tienen la funcionalidad de guiar al usuario desde su localización, el Metropolitano tiene una restricción de que la ubicación es a partir de las estaciones.

- Solo dos de los productos tienen un sistemas de alertas o nitificaciones al usuario sobre la ruta elegida. 

- Dos de los productos tienen una bonificación al usuario por el uso de la aplicación.

![Benchmarck](assets/docs/benchmarck.jpg)


## **SÍNTESIS DE INFORMACIÓN**

### **User persona.**

Representa al usuario que utiliza de manera frecuente el servicio del Metropolitano.

![User persona](assets/docs/user/user-persona.jpg)

### **User secundario**

Representa al usuario que utiliza de manera esporádica el servicio del Metropolitano y no tiene mucho conocimiento de ello.

![User secundario](assets/docs/user/user-secundaria.jpg)


## **PROPUESTA DE PRODUCTO**

### Propuesta de arquitectura de la información

Se redujo el flujo de la aplicación anterior a 4 flujos principales, que integren las principales tareas que realiza el usuario: búsqueda de rutas, información sobre los horarios y servicios, recarga de tarjeta virtual y notifiaciones sobre los servicios que el usuario usa con frecuencia. 

![Propuesta](assets/docs/arquitecture-dos.jpg)

### **Card Sorting**

Luego de analizar los problemas en la arquiectura de contenido de la aplicación actual, se propuso una nueva forma de organización en cuatro items principales: "Perfil", "Rutas", "Mi tarjeta" y "Cómo llegar". 
Se utilizó el card sorting mixto para que los usuarios propusieran nuevos contenidos de los ofrecidos o nuevas secciones.
En los siguientes resultados, los cuadros con color naranja, son los añadidos por el usuario.

![Imágenes del card sorting](assets/docs/card-sorting/card-sorting.jpg)

1. **Franchesca**

![Franchesca](assets/docs/card-sorting/franchesca.jpg)

2. **María Teresa**

![Maria Teresa](assets/docs/card-sorting/maria-teresa.jpg)

3. **Ari**

![Ari](assets/docs/card-sorting/ari.jpg)

4. **Silvia**

![Silvia](assets/docs/card-sorting/silvia.jpg)

5. **Aracely**

![Aracely](assets/docs/card-sorting/aracely.jpg)

6. **Betsy**

![Betsy](assets/docs/card-sorting/betsy.jpg)

#### Conclusiones del Card Sorting.

- Eliminar los flujos innecesarios.
- Reducir los pasos para realizar una tarea.
- Conectar flujos y tareas comunes. 

Este es el esquema que se obtuvo como resultado. Solo se han puesto los contenidos donde hubo una mayor coincidencia. 

![Resultado](assets/docs/card-sorting/resultado.jpg)



### **Business Model Canvas de la propuesta de producto**

![Business Model Canvas](assets/docs/model-canvas.jpg)


### **Paper prototyping**

[Ver con detalle](https://drive.google.com/file/d/12ipZs8ePPwBkHq2oFus63_P5myYfb270/view?usp=sharing)


#### **Resultados del testing del Paper Prototyping**

Se realizó el test con 3 personas. Los usuarios tenían las siguientes tareas:

1. Recargar la tarjeta.

- Les pareció util, pero preguntaron como sería la vinculación con la tarjeta. Se respondió que habría un trámite anterior con el banco.

2. Establecer una ruta de destino.

- Se tenían dos opciones para la sección de "Mis rutas": "Cómo llegar" y "Planificar mi ruta". Esta segunda opción no era entendida por los usuarios, el nombre les causaba confusión. En cambio, cómo llegar sí significaba para ellos que descubrirían como llegar a su destino.

- Les pareció útil la opción de ingresar un origen diferente al que detectaba el GPS, porque no siempre buscan una ruta desde el sitio actual donde están.

3. Programar sus notificaciones.

- Les pareció una opción interesante, pero cuestionaron que querían poder programar alarmas de varios servicios a la vez. 


## **Feedback e iteración**

### Feature List

- Registro de usuario nuevo
- Inicio de sesión
- Mis servicios: Regulares, Expresos y Alimentadores; para ver los horarios de servicio y estaciones.
- Mi tarjeta: recarga virtual a través de una cuenta en el Banco de la Nación o el BCP, previo acuerdo con el banco.
- Mis rutas: Guía al usuario de acuerdo a su origen y destino y ofrece las diversas rutas que puede tomar.
- Mis notificaciones: Alarmas programables para el usuario que desee saber posibles cambios de horario o problemas que surjan con los servicios que utiliza.


### **Iteración de arquitectura de la información**

Teniendo en cuenta los resultados del paper prototyping, se decidió no dividir el flujo de "Cómo llegar" y "Planificar mi ruta", y en cambio unirlos como una opción extra para usuario al momento de realizar el flujo. 
También se decidió que el flujo de servios y estaciones estén juntos.
Además, debido a sugerencias de usuarios, la programación de notificaciones se puede hacer seleccionando varios servicios a la vez, pero luego se deben responder los detalles de cada uno.


### **User Flow**

El usuario puede realizar los siguientes flujos:

- Inicio de sesión y registro.
- Búsqueda de rutas.
- Información sobre servicios y horarios.
- Recarga de su tarjeta.
- Programación de notificaciones según los servicios que utiliza.

[Detalle del user flow](https://docs.google.com/presentation/d/1A1Ju_Ly4ovMlHSL7YFyOqQF-3vnYLSmipUaP-e4Ui78/edit?usp=sharing)


## **Prototipo de alta fidelidad**

[Metropolitano app](https://marvelapp.com/31gjhd0/screen/39881989)

## **Herramientas utilizadas**

- Figma
- Marvel
- Adobe Ilustrator
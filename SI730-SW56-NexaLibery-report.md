---

---
---
# Universidad Peruana de Ciencias Aplicadas
# INGENIERÍA DE SISTEMAS DE SOFTWARE
## CURSO: SI730 Aplicacioes Web | SECCIÓN SW56
 Profesor: Efrain Ricardo Bautista Ubillus
# Informe de TB1
"Startup"
NexLibery
### Integrantes:
- Quispe Erasmo, Raúl Ronaldo - U20211B682
- Ramirez Ramirez, Marcelo Sebastian - U202210582
- Javier Murillo, Mathias - U202022211
- Leon Rioja Carlos Andres - U202111451

---
# Registro de Versiones del Informe
| Version | Fecha | Autor | Descripcion de Modificacion |
| ----------- | ----------- | ----------- | ----------- |
| 0.0 | 24/03/2024 |Grupo 8 |Se crea el documento |

# Project Report Collaboration Insights
[URL del repositorio](xxx)

(Imagenes de los commits cada entrega)


# Student Outcome
|Criterio Especifico|Acciones Realizadas|Conclusiones|
|-|-|-|
|Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software.|Compañero1:<br> *TB1:*  Su texto *TB2:* texto etc.. |Su texto de conclusion|
|Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software.|Compañero1:<br> *TB1:*  Su texto<br> *TB2:* texto etc.. |Su texto de conclusion|
# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
#### NexaLibery

- **Misión:**
 Dar acceco a las personas que neseciten o quieran contenido multimedia esto incluye libros electrónicos, audiolibros, música, podcasts, etc.
- **Visión:**
 Diseñar una plataforma que da acceso a los usuarios a una gran biblioteca de contenido multimedia, ademas de la opcion de tener un perfil para personalizar el contenido que deseas y poder elegir los planes de membresia para poder desbloquear mas beneficios, contenido y funciones.
#### 1.1.2. Perfiles de integrantes del equipo
|Miembros del equipo | Codigo Estudiante | Carrera | Conocimientos / Habilidades |
|-|-|-|-| 
|Rodriguez Vargas, Arian Martin <img src="/assets/members-profile/arigeimpleis.jpg" alt="Imagen del compañero" style="width:60%;">|U202212096|Ingenieria de software|C++, Python, persistente y amigable|
|Ramirez Ramirez, Marcelo Sebastian <img src="/assets/members-profile/ramirez.jpeg" alt="Imagen del compañero" style="width:60%">|U202212096|Ingenieria de software|C++, HTML5,JavaScript,SQL|
|Quispe Erasmo, Raúl Ronaldo <img src="/assets/members-profile/QuispeErasmo.jpeg" alt="Imagen del compañero" style="width:60%">|U20211B682|Ingenieria de software|C++, python, HTML5, CSS3, Javascript|
|Javier Murillo, Mathias <img src="/assets/members-profile/Mathias Javier Murillo.jpg" alt="Imagen del compañero" style="width:60%">|U202022211|Ingenieria de software|C++, SQL, React, Python, Javascript|
|Leon Rioja, Carlos Andres <img src="/assets/members-profile/carlos.jpg" alt="Imagen del compañero" style="width:60%">|U202111451|Ingenieria de software|C++, Python, HTML, CSS|
|Rodriguez Vargas, Arian Martin <img src="/assets/members-profile/arigeimpleis.jpg" alt="Imagen del compañero" style="width:60%">|U202212096|Ingenieria de software|C++, Python, persistente y amigable|
<!--cambien la url e info, se agrego estilos para evitar errores en las dimensiones -->
## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática

- 

### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements.
##### Problem Statement:
Nuestra visión con NexaLibery, la plataforma de Biblioteca Digital de Contenidos Multimedia, es ofrecer a los usuarios una experiencia completa para acceder y disfrutar de una amplia variedad de contenido digital, que incluye libros electrónicos, audiolibros, música y podcasts. Sin embargo, nos enfrentamos a un desafío importante: los usuarios de la suscripción básica se encuentran limitados en la creación de listas de reproducción personalizadas, lo que dificulta su capacidad para organizar y acceder fácilmente al contenido multimedia. Esta restricción, junto con la falta de recomendaciones personalizadas basadas en el historial de consumo del usuario, limita la exploración de nuevo contenido relevante.
Estas limitaciones en la experiencia del usuario pueden conducir a la insatisfacción de los clientes en la suscripción básica. Además, la ausencia de interacción social, como la falta de comunidades o grupos de discusión, puede disminuir el compromiso del usuario con la plataforma y limitar su potencial de crecimiento.
Por lo tanto, nos enfrentamos a la pregunta de cómo podemos mejorar la experiencia del usuario en NexaLibrary, especialmente para los usuarios de la suscripción básica y los estudiantes, proporcionando opciones de personalización, promoviendo la interacción social y ofreciendo herramientas educativas y de investigación efectivas.
#### 1.2.2.2. Lean UX Assumptions.
|Business Assumptions|User Assumptions|
|-|-|
| 1. Creemos que los usuarios de NexaLibrary, especialmente aquellos que utilizan la suscripción básica, necesitan una forma más eficiente de descubrir y acceder al contenido multimedia relevante, como libros electrónicos, audiolibros, música y podcasts.| 1. ¿Quién es el usuario? Los usuarios son, en primera parte, aquellos que utilizan la suscripción básica de NexaLibrary, buscando acceder a una amplia variedad de contenido digital. Además, estudiantes que buscan apoyo en su aprendizaje e investigación podrían beneficiarse de características específicas.|
| 2. Estamos asumiendo que estas necesidades pueden satisfacerse mediante el desarrollo de características adicionales, como recomendaciones personalizadas basadas en el historial de consumo del usuario y una mayor capacidad de personalización en la creación de listas de reproducción.| 2. ¿Qué problemas tiene NexaLibrary? ¿Resolver? Un problema que enfrenta actualmente NexaLibrary es la dificultad para los usuarios de la suscripción básica de descubrir nuevo contenido y acceder a él de manera eficiente.|
| 3. Inicialmente, nuestros clientes principales serán los suscriptores de la suscripción básica de NexaLibrary, así como los estudiantes que buscan acceder a contenido educativo y de entretenimiento.| 3. ¿Qué características son importantes? Las características más importantes de NexaLibrary incluyen recomendaciones personalizadas, mayor capacidad de personalización en la creación de listas de reproducción y acceso a contenido educativo relevante para los estudiantes.|
| 4. Suponemos que el valor más importante que un cliente espera de nuestros servicios es la capacidad de descubrir nuevo contenido relevante de manera eficiente y personalizada, así como acceder a herramientas de estudio integradas para apoyar su aprendizaje e investigación. | 4. ¿Dónde encaja NexaLibrary en su trabajo o vida? NexaLibrary encaja en la vida de los usuarios al proporcionarles una plataforma centralizada para acceder y disfrutar de una amplia variedad de contenido digital, tanto para su entretenimiento como para su desarrollo académico.|
| 5. Asumimos que los clientes también valorarán la capacidad de participar en comunidades o grupos de discusión en la plataforma, lo que les permitirá conectarse con otros usuarios con intereses similares y compartir recomendaciones y opiniones sobre el contenido.| 5. ¿Cuándo y cómo es NexaLibrary? ¿Usado? NexaLibrary se utiliza cuando los usuarios buscan acceder a contenido digital, ya sea para su entretenimiento personal, estudio o investigación, en cualquier momento y lugar a través de dispositivos conectados a Internet.|
#### 1.2.2.3. Lean UX Hypothesis Statements.
- **Hypothesis Statement 01**:
Creemos que los usuarios de la suscripción básica estarán más dispuestos a actualizar a una suscripción premium si se les ofrece acceso exclusivo a lanzamientos anticipados de contenido multimedia y eventos en vivo. Sabremos que hemos tenido éxito cuando veamos un aumento del 20% en las conversiones de la suscripción básica a la suscripción premium en los primeros seis meses de implementación de esta característica.
- **Hypothesis Statement 02**:
Creemos que la integración de herramientas de estudio y la capacidad de formar grupos de estudio virtuales aumentará el compromiso de los usuarios de la suscripción para estudiantes con la plataforma.
Sabremos que hemos tenido éxito cuando veamos un aumento del 30% en el tiempo dedicado al estudio y la interacción en grupos de estudio dentro de la plataforma por parte de los usuarios de la suscripción para estudiantes en los primeros tres meses después de la implementación de estas características.
- **Hypothesis Statement 03**:
Creemos que la personalización de recomendaciones de contenido basadas en el historial de consumo del usuario aumentará la satisfacción y retención de los usuarios en la plataforma.
Sabremos que hemos tenido éxito cuando veamos una disminución del 15% en la tasa de abandono de la plataforma entre los usuarios de la suscripción básica después de implementar esta funcionalidad y realizar una encuesta de satisfacción del usuario seis meses después.
- **Hypothesis Statement 04**:
Creemos que la introducción de comunidades y grupos de discusión en la plataforma aumentará la interacción social entre los usuarios y promoverá un sentido de comunidad en torno a temas específicos.
Sabremos que hemos tenido éxito cuando veamos un aumento del 25% en la participación activa en grupos de discusión y una mayor retención de usuarios en la plataforma después de seis meses de implementar estas funciones.
#### 1.2.2.4. Lean UX Canvas.
El Lean UX Canvas es usado como un diseño para el usuario y de acuerdo a la medotología "Lean" sería para crear, desarrollar y generar elaboraciones de manera ordenada, eficiente y efectiva. Acá dejamos una visualización directa del Lean UX Canvas trabajad por el equipo con la herramienta Mural:
(imagen)
Si quieres ver más a detalle, acceder a [Canvas](https://app.mural.co/t/nexalibery5875/m/nexalibery5875/1711531230304/9cae9888df00da29e0a5dc996ce0e7484ff9da3d?sender=ud5867274f6e0f4e990f88500).
## 1.3. Segmentos objetivo.
Nos dimos cuenta que el estrés académico según Universidad de Chile (2023), es ocasionado por las pruebas, trabajos, exámenes, presentaciones, etc. Pueden ser subsanados por la música que según dice Campus Home (2020) puede ayudar a muchos estudiantes a superar el estrés y la ansiedad mientras estudian.
### 1.3.1. Stakeholders:
- **Stakelholder Internos**: Equipo de desarrollo y tecnología, equipo de contenido y curación, equipo de Marketing y ventas y equipo de soporte y atención al cliente.
- **Stakelholder Externos**: Usuarios Finales, sroveedores de contenido, socios comerciales, reguladores y autoridades.

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores.
### 2.1.1. Análisis competitivo.

| Competitive Analysis Landscape                          |  |
| ------------------------------------------------------- | -|
| ¿Por qué llevar a cabo este análisis?                   | -- |


| |  | (Nosotros) | Competidor  | Comptdor |
|-|-|-|-|-|
| PERFIL| Overview | lorem | ipsum | lorem |
|| Ventaja competitiva ¿Qué valor ofrece a los clientes? |  ipsu | impuz |
|| Mercado Objetivo                                        | Jeda | asa | asa2 |
| Perfil de marketing                                     | Estrategia de Marketing | Redes Sociales | Redes Sociales | Televisión, Redes Sociales |
| Perfil del producto                                     | Productos y servicios | Elementos Gráficos Interactivos Enseñanza de Matemáticas Lúdica y Autodidacta Educación matemática interactiva Ámbito Freemium | Educación matemática interactiva Mas de 100 cursos en 28 idiomas diferentes | Educación general interactiva Contratos con Movistar |
|| Precios y costos                                        | Freemium (Cuenta Premium permite personalizar los juegos) Gratis | Gratuito | Gratuito |
|| Canales de distribución (Web y/o Móvil)                 | Web y Móvil Web | Móvil Web | Web y móvil Web |
### 2.1.2. Estrategias y tácticas frente a competidores.


|Competidores ->|  | Nosotros | Competidor2| Competidor3|
|-|-|-|-|-|
| Análisis SWOT | Fortalezas | lorem | Lorem | lorem |
|| Debilidades   | lorem | lorem | lorem | lorem | 
|| Oportunidades | lorem | lorem | lorem | lorem | 
|| Amenazas      | lorem | lorem | lorem | lorem |

## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.
**Preguntas generales:**

1. ¿Cuál es su nombre? 
2. ¿Qué edad tiene? 
3. ¿A qué se dedica? 
4. ¿[Opinion de idea de propuesta]? 

**Entrevistas usuario segmento 2**
1. ¿Lorem?
2. ¿Lorem?
3. ¿Lorem?
4. ¿Lorem?  
   
**Entrevistas usuario segmento 2**
1. ¿Lorem? 
2. ¿Lorem?
3. ¿Lorem?
4. ¿Lorem? 
### 2.2.2. Registro de entrevistas.
**Segmento 1**  
Nombre: _____
Edad: _ años 
Ocupación: _____  
![Imagen de entrevista](image.jpg)  
{texto mucho}

**Segmento 2**  
Nombre: _____
Edad: _ años 
Ocupación: _____  
![Imagen de entrevista](image.jpg)
{texto}

### 2.2.3. Análisis de entrevistas.
**Segmento 1:**
{texto}
**Segmento 2:**
{texto}
## 2.3. Needfinding.
### 2.3.1. User Personas. 
<img src="assets/User Persona 1.png" alt="Mapa de impacto" style="width:100%;">

<img src="assets/User Persona 2.png" alt="Mapa de impacto" style="width:100%;">

### 2.3.2. User Task Matrix.
**Estudiantes colegiales, universitarios o tecnicos:** 
|  |  User 1  | User 2 | User 3  | User 4 |
| --- | ----------- | ------------ | ----------- | ---------- |
| Es un estudiante universitario  | <span style="color:#90D26D; font-weight:bold">SI</span>   | <span style="color:#FFC700; font-weight:bold">NO</span>| <span style="color:#90D26D; font-weight:bold">SI</span>   | <span style="color:#90D26D; font-weight:bold">SI</span> |
| Conoce alguna plataforma en la cual pueda tener acceso a multimedia sobre temas variados | <span style="color:#FFC700; font-weight:bold">NO</span> | <span style="color:#E72929; font-weight:bold">NO</span>        | <span style="color:#FFC700; font-weight:bold">SI</span>         | <span style="color:#E72929; font-weight:bold">NO</span>       |
| Esta interesado en descargar libros, podcasts, etc | <span style="color:#90D26D; font-weight:bold">SI</span> | <span style="color:#90D26D; font-weight:bold">SI</span>        | <span style="color:#FFC700; font-weight:bold">POCO</span>         | <span style="color:#90D26D; font-weight:bold">SI</span>       | 
| Le interesan temas variados fuera de su campo de estudio | <span style="color:#FFC700; font-weight:bold">SI</span> | <span style="color:#FFC700; font-weight:bold">POCO</span>        | <span style="color:#FFC700; font-weight:bold">POCO</span>         | <span style="color:#E72929; font-weight:bold">SI</span>       |

**Egresados de carreras universitarias y/o tecnicas:** 
|  |  User 1  | User 2 | User 3  | User 4 |
| --- | ----------- | ------------ | ----------- | ---------- |
| Ha culminado alguna carrera universitaria y/o tecnica  | <span style="color:#90D26D; font-weight:bold">SI</span>   | <span style="color:#90D26D; font-weight:bold">SI</span>| <span style="color:#90D26D; font-weight:bold">SI</span>   | <span style="color:#90D26D; font-weight:bold">SI</span> |
| Le interesa expandir su conocimiento sobre su campo | <span style="color:#E72929; font-weight:bold">SI</span> | <span style="color:#E72929; font-weight:bold">NO</span>        | <span style="color:#FFC700; font-weight:bold">POCO</span>         | <span style="color:#E72929; font-weight:bold">SI</span>       |
| Conoce alguna plataforma para tener acceso a multimedia sobre temas variados | <span style="color:#90D26D; font-weight:bold">SI</span> | <span style="color:#90D26D; font-weight:bold">SI</span>        | <span style="color:#FFC700; font-weight:bold">NO</span>         | <span style="color:#90D26D; font-weight:bold">SI</span>       | 
| Esta interesado en descargar libros, podcasts, etc | <span style="color:#90D26D; font-weight:bold">SI</span> | <span style="color:#90D26D; font-weight:bold">SI</span>        | <span style="color:#90D26D; font-weight:bold">SI</span>         | <span style="color:#90D26D; font-weight:bold">SI</span>       |
### 2.3.3. User Journey Mapping.
**Registration:**
Why would they trust us?
- Investiga sobre la reputacion y confiabilidad de la plataforma
- Lee reseñas o testimonios
- Revisa politicas de privacidad y medidas de seguridad de la plataforma
  
**Onboarding and first use:**
How can they feel successful?
- Completa el proceso de registro sin problemas
- Navega por la plataforma facilmente y encuentra contenido de manera facil y eficiente
- Recibe orientacion sobre como usar diferentes caracteristicas
  
**Sharing:**
Why would they invite others?
- Encuentra valor sobre las caracteristicas que ofrecemos y el contenido publicado
- Recibe incentivos o recompensas por invitar a otros
- Participa en discusiones o grupos comunitarios

### 2.3.4. Empathy Mapping.
**Estudiante Universitario:**
<img src="assets/Empathy Map Estudiante.png" alt="Mapa de empatia" style="width:100%;">

**Egresado Universitario:**
<img src="assets/Empathy Map Estudiante.png" alt="Mapa de empatia" style="width:100%;">
### 2.3.5. As-is Scenario Mapping.

**Segmento 1**  
Escenario: Un estudiante universitario se inscribe en la aplicacion de contenido multimedia para acceder a una extensa variedad de recursos educativos y de entretenimiento 

As Is:
| Fases| Fase 1 | Fase 2| Fase 3| Fase 4|
| -------- | --------- | --------- | ------- | --------- |
| Doing | Explora la interfaz de la aplicacion| Busca contenido relevante en la seccion de libros | Intenta crea su propia lista de reproduccion | Proporciona una reseña de la app |
| Thinking | "¿Como puedo encontrar lo que necesito?" | "¿Por que no puedo crear una lista de reproduccion?" | "¿Hay alguna forma de organizar mejor mi contenido?" | "¿Mi reseña será considerada?"  |
| Feeling  | Curiosidad por explorar las caracteristicas de la app | Frustracion por la limitacion de crear listas | Confusion sobre como organizar mi contenido | Esperando que sus comentarios mejoren la aplicacion |

**Segmento 2**  
Escenario: Un egresado universitario utiliza la aplicacion para acceder a recursos educativos y de entretenimiento mientras busca oportunidades de crecimiento profesional

As Is:
| Fases| Fase 1 | Fase 2| Fase 3| Fase 4|
| -------- | --------- | --------- | ------- | --------- |
| Doing | Explora la interfaz de la aplicacion| Busca contenido relevante en la seccion de libros | Intenta crea su propia lista de reproduccion | Proporciona una reseña de la app |
| Thinking | "¿Como puedo encontrar lo que necesito?" | "¿Por que no puedo crear una lista de reproduccion?" | "¿Hay alguna forma de organizar mejor mi contenido?" | "¿Mi reseña será considerada?"  |
| Feeling  | Curiosidad por explorar las caracteristicas de la app | Frustracion por la limitacion de crear listas | Confusion sobre como organizar mi contenido | Esperando que sus comentarios mejoren la aplicacion |
## 2.4. Ubiquitous Language.
```
Estudiante colegial, universitario y/o tecnico:

Persona la cual busca nuestra aplicacion por medio de la suscripcion para estudiantes, la cual les genera un descuento especial sobre la suscripcion estandar o premium, todo esto mediante una verificacion de que sea estudiante. En el cual tendra acceso a material educativo y contenido especifico para apoyar su aprendizaje.

Egresado universitario y/o tecnico:

Persona la cual nos busca por medio de cualquiera de nuestras suscripciones, en las cuales les proporcionará diferentes beneficios dependiendo de que suscripcion haya elegido. 
```

---

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping.

| Fases    | Descubrimiento  | Evaluación    | Suscripción    |  Uso Intensivo   | Participación Comunitaria |
|----------|--------------------------|-----------------------|------------------------|-------------------------|-----------------------------------|
| Doing    | Los usuarios exploran la oferta inicial de contenidos y las funcionalidades básicas de la plataforma. | Los usuarios comparan las opciones de suscripción y evalúan los beneficios. | Los usuarios se suscriben al nivel que mejor se ajusta a sus necesidades, completando el registro y la configuración de preferencias. | Los usuarios consumen contenido, crean listas de reproducción y utilizan herramientas de estudio. | Los usuarios participan en comunidades, eventos en vivo, y crean grupos de estudio o discusión. |
| Thinking | "¿Qué tipo de contenido puedo encontrar aquí?" | "¿Qué plan de suscripción ofrece el mejor valor para mí?" | "Espero que el proceso de suscripción sea sencillo." | "Hay tanto contenido interesante; ¿por dónde empiezo?" | "Quiero compartir mis ideas y obtener nuevas perspectivas de otros usuarios." |
| Feeling  | Curiosidad por la nueva plataforma y sus ofertas. | Consideración cuidadosa y tal vez algo de indecisión sobre las opciones. | Satisfacción al unirse fácilmente y anticipación por explorar el contenido. | Entusiasmo y placer al descubrir y consumir contenido que les gusta. | Sentido de comunidad y conexión al interactuar con otros usuarios con intereses similares. |


## 3.2. User Stories.

| USER STORY ID | TITULO | DESCRIPCION|
|------|----------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| HU01 | Acceso a contenido básico | "Como usuario con suscripción básica, deseo tener acceso a una selección limitada de contenidos multimedia para disfrutar de variedad sin un costo elevado." |
| HU02 | Publicidad a cambio de premium | "Como usuario de suscripción básica, deseo la opción de ver o escuchar anuncios a cambio de acceso ocasional a contenido premium, para explorar contenido de mayor valor sin costo adicional." |
| HU03 | Crear listas de reproducción personalizadas | "Como usuario, deseo crear listas de reproducción personalizadas para organizar mis contenidos favoritos y acceder a ellos fácilmente." |
| HU04 | Acceder a comunidades | "Como usuario con suscripción estándar o premium, deseo acceder a comunidades y grupos de discusión para conectar con otros usuarios con intereses similares." |
| HU05 | Recibir recomendaciones personalizadas | "Como usuario, deseo recibir recomendaciones basadas en mi historial de consumo para descubrir nuevos contenidos que se ajusten a mis gustos." |
| HU06 | Acceso exclusivo a lanzamientos anticipados | "Como usuario con suscripción premium, deseo tener acceso exclusivo a lanzamientos anticipados para disfrutar del contenido antes que nadie." |
| HU07 | Descargar contenido para consumo sin conexión | "Como usuario premium, deseo descargar contenido para consumirlo sin necesidad de una conexión a internet, ideal para viajes o zonas sin cobertura." |
| HU08 | Participar en eventos en vivo | "Como usuario premium, deseo participar en eventos en vivo con creadores de contenido para enriquecer mi experiencia con la plataforma." |
| HU09 | Beneficios de suscripción para estudiantes | "Como estudiante, deseo acceder a un descuento en la suscripción estándar o premium para aprovechar al máximo los recursos educativos ofrecidos." |
| HU10 | Herramientas de estudio integradas | "Como usuario estudiante, deseo herramientas de estudio integradas en la plataforma para mejorar mi aprendizaje y organización." |
| HU11 | Acceso familiar bajo una sola suscripción | "Como cabeza de familia, deseo adquirir una suscripción familiar que permita a varios miembros acceder a contenido con perfiles individuales, para satisfacer los gustos de todos en casa." |
| HU12 | Controles parentales | "Como padre/madre, deseo establecer controles parentales para asegurar que mis hijos accedan solo a contenido apropiado para su edad." |
| HU13 | Listas de reproducción familiares | "Como usuario con suscripción familiar, deseo crear listas de reproducción que reflejen los gustos de toda la familia, para disfrutar juntos." |
| HU14 | Explorar contenido premium ocasionalmente | "Como usuario de suscripción básica, deseo la opción de explorar contenido premium ocasionalmente para conocer la oferta completa de la plataforma." |
| HU15 | Crear grupos de estudio virtuales | "Como estudiante, deseo la capacidad de formar grupos de estudio virtuales con otros usuarios, para colaborar y aprender juntos de manera más eficaz." |


## 3.3. Impact Mapping.

<img src="/assets/IM.jpg" alt="Mapa de impacto" style="width:80%;">

## 3.4. Product Backlog.

| #Orden | User Story ID | Titulo  | Descripción | Story Points (1/2/3/5/8) |
| ------ | ------------- | -------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- | ------------------------|
| 1 | HU01 | Acceso a contenido básico  | "Como usuario con suscripción básica, deseo tener acceso a una selección limitada de contenidos multimedia." | 2 |
| 2 | HU02 | Publicidad a cambio de premium               | "Como usuario de suscripción básica, deseo la opción de ver o escuchar anuncios a cambio de acceso ocasional a contenido premium." | 3 |
| 3 | HU03 | Crear listas de reproducción personalizadas | "Como usuario, deseo crear listas de reproducción personalizadas para organizar mis contenidos favoritos."              | 3 |
| 4 | HU04 | Acceder a comunidades                        | "Como usuario con suscripción estándar o premium, deseo acceder a comunidades y grupos de discusión."                   | 4 |
| 5 | HU05 | Recibir recomendaciones personalizadas      | "Como usuario, deseo recibir recomendaciones basadas en mi historial de consumo."                                       | 5 |
| 6 | HU06 | Acceso exclusivo a lanzamientos anticipados | "Como usuario con suscripción premium, deseo tener acceso exclusivo a lanzamientos anticipados."                        | 2 |
| 7 | HU07 | Descargar contenido para consumo sin conexión | "Como usuario premium, deseo descargar contenido para consumirlo sin conexión a internet."                              | 4 |
| 8 | HU08 | Participar en eventos en vivo               | "Como usuario premium, deseo participar en eventos en vivo con creadores de contenido."                                 | 4 |
| 9 | HU09 | Beneficios de suscripción para estudiantes  | "Como estudiante, deseo acceder a un descuento en la suscripción estándar o premium."                                   | 3 |
| 10 | HU10 | Herramientas de estudio integradas          | "Como usuario estudiante, deseo herramientas de estudio integradas en la plataforma."                                   | 4 |
| 11 | HU11 | Acceso familiar bajo una sola suscripción   | "Como cabeza de familia, deseo adquirir una suscripción familiar que permita a varios miembros acceder con perfiles individuales." | 3 |
| 12 | HU12 | Controles parentales                        | "Como padre/madre, deseo establecer controles parentales para asegurar que mis hijos accedan solo a contenido apropiado."| 3 |
| 13 | HU13 | Listas de reproducción familiares           | "Como usuario con suscripción familiar, deseo crear listas de reproducción que reflejen los gustos de toda la familia." | 2 |
| 14 | HU14 | Explorar contenido premium ocasionalmente   | "Como usuario de suscripción básica, deseo la opción de explorar contenido premium ocasionalmente."                     | 3 |
| 15 | HU15 | Crear grupos de estudio virtuales           | "Como estudiante, deseo la capacidad de formar grupos de estudio virtuales con otros usuarios."                         | 4 |

# Capítulo IV: Product Design
## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines.
Descripcion del porque estos elementos seran importantes

**Color:** (Descripcion de los colores escogidos y porque)  
![Colores generales](image.jpg)

**Tipografia:** (Descripcion de la tipografia escogida para el proyecto y porque)
![Tipografias generales](image.jpg)
**Branding** (Describir logotipo y porque)
![Branding general](image.jpg)
### 4.1.2. Web Style Guidelines.
Descripcion de los elementos que se utilizaran en el web app

**Background:** (primary, secondary, terniary)  
![Background Preview web](image.jpg)
**Text Styles:** (H1, H2, p, a,)  
![Text Style Preview web](image.jpg)
**Button Styles:** (Button, dropdowns, Switches)
![Button Preview web](image.jpg)
**Icons:** (Fondo blanco con los iconos que vamos a usar)
![Icons Preview web](image.jpg)
**Misc** (Cosas como nav var o slideshows que pensemos usar)
![Miscellaneos preview web](image.jpg)
## 4.2. Information Architecture.
### 4.2.1. Organization Systems.
Descripcion corta respecto a los sistemas de organizacion que usaremos  (Escoger)
"Hierarchical. This structures advices to present the content in a way to distinguish the level of importance by making use of physical differences, such as size, colour, contrast, alignment etc.

Sequential. Guide users to follow a specific path towards their goal and provide content step-by-step based on the current step. 

Matrix. You can always give the users the option to choose the type of navigation they prefer, i.e. Alphabetical, Chronological, by topic."
### 4.2.2. Labeling Systems.
The labeling system aims at uniting the data effectively and represent them in simple way and avoid confusing great amount of information. A widely adopted way to achieve this is by creating the labels which represent loads of data in few words. 

Como decir "home, about us, etc" basicamente lo que iria en un nav var y asi
### 4.2.3. SEO Tags and Meta Tags

**Meta & SEO (Search Engine Optimization) Tags:**  sirven para que la pagina web sea encontrada facilmente es lo que sale al encontrar la pagina en el buscador (se ponen en el <"head">)
* Titulo: ```<title> ___ </title> ```
* Descripcion: ```<meta name = "description" content = "texto descipcion"/> ```
* Palabras Clave: ```<meta name = "keyword" content = "keyword1, 2 3"/> ```

### 4.2.4. Searching Systems.
**Que se busca?:** Que buscara el usuario  
**Que resultados se mostraran?:** Que se mostrara  
**Interface de busqueda:** Descripcion de como ayuda a encontrar lo deseado 
![Search interface preview web](image.jpg)

### 4.2.5. Navigation Systems.
Basicamente aqui definimos como funciona la navegacion del web app
**Hierarchical Navigation System:** Main page a destination pages.
**Global Navigation Systems** (Complemento del Hierachical) Movimiento vertical (te mueves por la pagina)con nav(debe poder regresar a la principal)
**Local Navigation Systems** (vas a otras paginas) (complemento del global nav sistem sub-site) Usas otras paginas
## 4.3. Landing Page UI Design.
### 4.3.1. Landing Page Wireframe.
la pagina donde te registras y ves info del web app (te manda al web app)

Wireframe es todo lo funcional de la pagina
![Landing page Wireframe](image.jpg)
### 4.3.2. Landing Page Mock-up.
Mockup es todo lo relacionado al diseño de la pagina
![Landing page mockup](image.jpg)
## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.
lo funcional de cada aspecto del wireframe 
![Web Aplication Wireframe](image.jpg)
### 4.4.2. Web Applications Wireflow Diagrams.
Wireflow es como se va a navegar por la pagina (boton me lleva a esta pagina y este me regresa)
![Web Aplication Wireflow](image.jpg)
### 4.4.2. Web Applications Mock-ups.
Diseño en todo aspecto
![Web Aplication Mockup](image.jpg)
### 4.4.3. Web Applications User Flow Diagrams.
un flow diagram de como el usuario utilizara la pagina **[PARA CADA USER GOAL]** 
![Web Aplication User Flow Diagram](image.jpg)
## 4.5. Web Applications Prototyping.
[URL del Prototipo (Hecho en figma)](https://www.example.com)
## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Software Architecture Context Diagram.
1. System Context Diagram: Diagrama que muestra la relacion del aplicativo con los usuarios
se incluyen servicios externos (si hay pocos bounded context se incluyen ahi)

2. Bounded Context Map: Muestra la relacion entre bounded contexts (los bounded context son como una burbuja que encapsula palabras clave en los procesos para poder diferenciarlos [Ej. Bounded context enfocado en las ventas(ventas), otro en revisar el stock(gestion) y otro enfocado en los proveedores (suministros)]) Se hace como un brainstorm y se ve en que pueden conectarse o comunicarse [se usa un circulo entre conexiones lineales (upstream o downstream) para definir comunicacion, algunos context se pueden integrar para representar por ejemplo un share model por database, tambien se mencionan los (third party context para definir los restful apis)]
   
### 4.6.2. Software Architecture Container Diagrams.
1. Bounded Context Deployable / Container Diagrams. Sirve para entender como funciona y el proceso, Se especifican DB's, indexers, Search engine, las Apis que usen los bounded context y se conectan por flechas, las cuales tienen como objetivo explicar la direcion y relacion junto a que se esta enviando/comunicando (TCP) 

### 4.6.3. Software Architecture Components Diagrams.
1. Component diagrams: Estos van a mostrar las ordenes, procesos, mensajes y componentes utilizados en el uso del aplicativo, claro se deben hacer diferentes de estos para cada bounded o USER GOALS
## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.
Esta yaselasaben (diagrama de clases)
Clases(name), objetos(nombre-objeto [como objeto]), metodos("Accion") y atributos(Correo, edad,nombre como valor, ID)
### 4.7.2. Class Dictionary.
Inherit (ave(superclase) -> (subclase)canario )
Polymorphism (Ej. funcion de persona hablar() -> Peruano hablar() , Gringo hablar() todos tienen una funcion que contiene persona y van cambiando sus formas)
Abstraction (Ej. Solo muestra el usuario, pero esta su edad, correo y veces usada que uso app en la base de datos (fuera de vista))
Encapsulation (cuando tienes tus variables y metodos en la misma clase las estas encapsulando, aun mas se encapsulan en Private y Public )
## 4.8. Database Design.
### 4.8.1. Database Diagram.
Diagrama de base de datos (la relacion entre clases PK FK el Normalizar tmbn, isiyisi 🕸)
# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.
Especificaciones de donde vamos a hacer el proyecto (vscode supongo)
extensiones tmbn? nose bn q quieren aca
### 5.1.2. Source Code Management.
El gitjab donde tengamos el proyecto
### 5.1.3. Source Code Style Guide & Conventions.
Que usamos con css (en caso usemos software para SASS)
supongo q tmbn cositas de como hacemo el code capas algun tipo de codigo para comunicarse entre comments
### 5.1.4. Software Deployment Configuration.
Configuraciones de donde y como deployeamos el proyecto
## 5.2. Landing Page, Services & Applications Implementation.
### 5.2.X. Sprint n
#### 5.2.X.1. Sprint Planning n.
Explicar como vamos a plannear el sprint?
#### 5.2.X.2. Sprint Backlog n.
![SprintBacklog n](image.jpg) Nica hago la tabla 
#### 5.2.X.3. Development Evidence for Sprint Review.
![Sprint review development Evidence](image.jpg)
#### 5.2.X.4. Testing Suite Evidence for Sprint Review.
![Sprint review Testing suite Evidence](image.jpg)
#### 5.2.X.5. Execution Evidence for Sprint Review.
![Sprint review Execution Evidence](image.jpg)
#### 5.2.X.6. Services Documentation Evidence for Sprint Review.
![Sprint review Services Documentation Evidence](image.jpg)
#### 5.2.X.7. Software Deployment Evidence for Sprint Review.
![Sprint review Software Deployment Evidence](image.jpg)
#### 5.2.X.8. Team Collaboration Insights during Sprint.
![Sprint review Team Collaboration Insights](image.jpg) imagenes de colaboraciones github

## 5.3. Validation Interviews.
### 5.3.1. Diseño de Entrevistas.
**Preguntas generales:**

1. ¿Cuál es su nombre? 
2. ¿Qué edad tiene? 
3. ¿A qué se dedica? 
4. ¿[Opinion de idea de propuesta]? 

**Entrevistas usuario segmento 2**
1. ¿Lorem?
2. ¿Lorem?
3. ¿Lorem?
4. ¿Lorem?  
   
**Entrevistas usuario segmento 2**
1. ¿Lorem? 
2. ¿Lorem?
3. ¿Lorem?
4. ¿Lorem? 
### 5.3.2. Registro de Entrevistas.
**Segmento 1**  
Nombre: _____
Edad: _ años 
Ocupación: _____  
![Imagen de entrevista](image.jpg)  
{texto mucho}

**Segmento 2**  
Nombre: _____
Edad: _ años 
Ocupación: _____  
![Imagen de entrevista](image.jpg)
{texto}
### 5.3.3. Evaluaciones según heurísticas.
| HEURÍSTICA   | EVALUACIÓN ✅❌ | NOTA      |
| --------------------------------------------- | ---------- | --------- |
| Visibilidad del estado del sistema            |            | {texto}   |
| Coincidencia entre el sistema y el mundo real |            | {texto}   |
| Control y libertad del usuario                |            | {texto}   |
| Consistencia y estándares                     |            | {texto}   |
| Prevención de errores                         |            | {texto}   |
| Mostrar antes que recordar                    |            | {texto}   |
| Flexibilidad y eficiencia de uso              |            | {texto}   |
| Diseño estético y minimalista                 |            | {texto}   |
| Comunicar errores con facilidad               |            | {texto}   |
| Ayuda y documentación                         |            | {texto}   |
## 5.4. Video About-the-Product.
[URL del video about the product](https://www.example.com)
# Conclusiones
{texto}
# Conclusiones y recomendaciones.
{texto}
# Video About-the-Team.
[URL del video about the team](https://www.example.com)
# Bibliografía
``` 
formato

"Apellido", Ini.Ciales. & "otroAutor", O.A. (año). titulo del articulo.
        "nombre del articulo o lo q sea, Volumen(si es que tiene), numero  de pagina"#-#. https//link.org/eeeseneko

```
# Anexos

datos, gráficos, imágenes, esquemas, mapas o referencias de otros autores

![Imagen de algo no nuestro lol](image.jpg)

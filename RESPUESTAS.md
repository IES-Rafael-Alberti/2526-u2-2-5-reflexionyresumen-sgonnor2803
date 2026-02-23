# RESPUESTAS — Reflexión y Resumen (Plantilla genérica)

> **Actividad / ID:**  2.a..e <br>
> **Unidad / Tema:**  Unidad 2: Análisis de incidentes <br>
> **Alumno/a:**  Sergio González Noria <br>
> **Fecha:**  23/02/2026

---

## 1) Reflexión crítica (preguntas)
Responde con **lenguaje técnico** y **argumentos** (no solo opiniones). Si procede, usa ejemplos, riesgos y decisiones justificadas.

### 1.1) ¿Qué te han parecido los temas tratados en la unidad?

Me ha parecido una unidad bastante interesante. Aunque ha tenido bastante teoría, creo que era necesaria para entender bien los conceptos antes de pasar a la práctica, sobre todo en temas como la gestión de incidentes o los SIEM. La parte de OSINT me ha gustado bastante, porque al usar herramientas reales se entiende mejor cómo funciona todo en un caso más cercano a la realidad.

### 1.2) ¿Qué ha sido más útil para tu futuro puesto de trabajo? ¿Por qué?

Para mí lo más útil ha sido la parte de OSINT, porque me quiero orientar a red team o pentesting y estas técnicas son clave en la fase de reconocimiento y recopilación de información. Creo que es algo que voy a usar bastante en el futuro. También me ha servido entender mejor cómo funcionan los SIEM, ya que aunque no sea a lo que me quiera dedicar directamente, es importante saber cómo detecta y monitoriza una empresa los incidentes.

### 1.3) ¿Qué partes ya conocías y cuáles han sido nuevas para ti?

Antes ya sabía más o menos qué era un SIEM y también me sonaba el concepto de OSINT, pero de forma bastante básica. No tenía un conocimiento técnico ni había trabajado realmente con ello. La parte de documentación de incidentes y la elaboración de informes técnicos sí que era algo nuevo para mí, y me ha servido para entender mejor cómo se gestiona un incidente de forma más profesional y estructurada.

### 1.4) ¿Qué concepto/idea te ha llamado más la atención y por qué? 

Lo que más me ha llamado la atención ha sido el tema de OSINT y los distintos tipos de técnicas que existen, tanto pasivas como activas. Me parece algo muy importante para el perfil al que quiero orientarme (red team / pentesting). Además, me ha resultado interesante ver cómo se puede obtener tanta información solo a partir de fuentes abiertas.

### 1.5) ¿Qué parte recortarías o simplificarías si hubiera menos tiempo? Justifica.

En principio no quitaría nada, porque creo que todo lo que hemos visto aporta algo. Pero si hubiera que simplificar algo, quizá reduciría un poco los retos de OSINT, ya que ese contenido también lo trabajamos en otras actividades. A lo mejor se podrían hacer ejercicios más pequeños en clase en lugar de un proyecto completo, así se aprovecha mejor el tiempo sin dejar de ver el contenido.

### 1.6) ¿Qué tema has echado en falta o ampliarías? Justifica.

La verdad es que no he echado en falta ningún tema, porque creo que para ser una primera toma de contacto está bastante bien. Es cierto que algunos contenidos se han trabajado más que otros, pero lo veo normal por el tiempo que hay. Si tuviera que ampliar algo, quizá sería la parte de OSINT porque es la que más me interesa, pero en general creo que la unidad está bien planteada.

### 1.7) ¿Qué aplicarías “mañana” en un entorno real con recursos limitados?

Si tuviera que aplicarlo mañana en un entorno real con pocos recursos, me centraría en mejorar la documentación y en usar técnicas básicas de OSINT para analizar la superficie de exposición. Creo que son cosas que aportan bastante y no necesitan una infraestructura complicada. Un SIEM en ese contexto lo veo más difícil por los costes y la arquitectura que requiere, así que primero trabajaría en lo más básico y después ya valoraría herramientas más avanzadas.

### 1.8) ¿Qué duda, riesgo o punto crítico te queda abierto tras la unidad?

La duda que me queda es cómo se podría automatizar la respuesta ante ciertas alertas. Por ejemplo, si el SIEM detecta un intento de conexión SSH sospechoso, me gustaría saber cómo se podría configurar para que se bloquee automáticamente o se aisle el equipo sin que tenga que hacerlo alguien manualmente. Imagino que esto tendría que ver con herramientas como SOAR, EDR o la integración entre sistemas, pero no hemos visto en profundidad cómo se hace esa automatización en un entorno real.

## 2) Resumen esquematizado (obligatorio)

| Bloque principal | Qué hemos visto |
|-----------------|---------------|
| Clasificación y taxonomía de incidentes | Cómo se clasifican los incidentes según INCIBE-CERT y los tipos que existen |
| Documentación e informes | Cómo registrar un incidente y cómo hacer un informe bien estructurado |
| OSINT | Uso de información pública para analizar casos y entender mejor la exposición |
| SOC | Qué es, cómo funciona y cómo está organizado |
| SIEM | Qué es y cómo ayuda a recopilar y analizar los eventos de seguridad |
| Implantación práctica del SIEM | Montaje con ELK, Filebeat y detección con Snort en un entorno práctico |

En esta unidad hemos visto la clasificación de incidentes, la documentación, el OSINT y el funcionamiento del SOC y el SIEM. También hemos hecho prácticas y la implantación del SIEM con ELK, Filebeat y Snort, lo que nos ha ayudado a entender mejor cómo se relaciona todo y cómo funciona en conjunto.

### 2.1) Mapa/índice de la unidad (visión global)

- Clasificación y taxonomía de incidentes
- Documentación e informes técnicos
- OSINT y prácticas relacionadas
- SOC y cómo funciona dentro de una organización
- SIEM y su uso para la monitorización
- Implantación práctica del SIEM con ELK, Filebeat y Snort

### 2.2) Conceptos clave (lista breve)

- SOC
- SIEM
- OSINT (pasivo y activo)
- Threat Intelligence
- Threat Hunting
- Incident Response
- Forensics
- IDS / IPS
- Taxonomía de incidentes
- Reporting
- CSIRT / CERT / CIRT

### 2.3) Procesos / procedimientos (pasos o checklist)

#### Clasificación y gestión de un incidente

- Ver a qué agrupación y tipo pertenece
- Entender cómo funciona y qué impacto tiene
- Ver la prioridad y el nivel de riesgo
- Clasificarlo dentro de la taxonomía
- Añadir un caso real o ejemplo con datos
- Apuntar las medidas de protección y recomendaciones
- Dejar todo bien registrado y organizado

#### Aplicación de OSINT

- Definir qué entidad o empresa se va a analizar
- Buscar dominios, subdominios y servidores públicos
- Revisar información en buscadores y herramientas OSINT
- Analizar certificados, DNS y metadatos de archivos
- Buscar empleados y datos de contacto expuestos
- Identificar información sensible publicada
- Clasificar los hallazgos según el riesgo
- Guardar evidencias y documentar todo
- Proponer mejoras para reducir la exposición

#### Implantación práctica del SIEM con IDS

- Crear el entorno con contenedores Docker
- Configurar la red interna para que los contenedores se comuniquen
- Desplegar los servicios: cliente, servidor, Snort, Filebeat, Logstash, Elasticsearch y Kibana
- Configurar Filebeat para recoger los logs de Snort y del servidor nginx
- Configurar Snort con reglas para detectar tráfico sospechoso (SSH, fuerza bruta, etc.)
- Procesar los logs con Logstash y enviarlos a Elasticsearch
- Verificar que las alertas aparecen correctamente en Kibana
- Realizar pruebas simulando ataques y comprobar la generación de alertas
- Ajustar configuraciones y resolver errores si algo no funciona

### 2.4) Herramientas / técnicas (si aplica)

#### Herramientas usadas en el entorno SIEM

- ***Docker***, para montar todo el entorno virtualizado
- ***ELK Stack*** (Elasticsearch, Logstash y Kibana), para almacenar y visualizar los logs
- ***Filebeat***, para recoger los registros de los sistemas
- ***Snort***, como sistema de detección de intrusos (IDS)

#### Herramientas usadas en OSINT

- ***WHOIS***, para consultar información sobre dominios
- ***DNSDumpster***, para ver subdominios y registros DNS
- ***crt.sh***, para revisar certificados SSL públicos
- ***SpiderFoot***, para automatizar el análisis de dominios, subdominios y datos públicos
- ***HaveIBeenPwned***, para comprobar si correos aparecen en filtraciones
- ***Wayback Machine***, para mirar versiones antiguas de páginas web
- ***Epieos***, para analizar correos y perfiles vinculados
- ***TinEye***, para hacer búsqueda inversa de imágenes
- ***Webmii***, para encontrar información pública sobre personas
- ***PeekYou***, para localizar datos públicos de identidades
- ***Sherlock***, para buscar usuarios y nicks en distintas plataformas

### 2.5) Buenas prácticas y errores típicos

#### Buenas prácticas

- Clasificar bien cada incidente y ponerle la prioridad correcta
- Documentar todo y guardar las evidencias de lo que se encuentra
- Configurar bien las reglas del IDS para evitar falsas alarmas
- Usar las herramientas OSINT siempre de forma pasiva y respetando la privacidad
- Revisar que no queden subdominios o servicios expuestos sin necesidad
- Mantener actualizado el entorno y las herramientas
- Quitar metadatos sensibles antes de publicar documentos

#### Errores típicos

- Clasificar mal un incidente y asignar una prioridad que no corresponde
- Configurar mal las reglas y generar demasiados falsos positivos
- Usar herramientas OSINT de forma activa cuando no toca
- Dejar páginas de prueba o servicios abiertos públicamente
- No documentar bien lo que se ha hecho ni guardar evidencias

### 2.6) Glosario mínimo (términos y definiciones cortas)

- ***Taxonomía de incidentes***: Forma de clasificar los incidentes según su tipo, impacto y características para organizarlos mejor.
- ***SOC***: Centro donde se monitorizan y analizan los eventos de seguridad de una organización.
- ***CSIRT***: Equipo que responde y gestiona incidentes de seguridad dentro de una organización.
- ***CERT***: Equipo parecido al CSIRT, pero más enfocado a nivel nacional o institucional.
- ***CIRT***: Grupo que se encarga de la respuesta y coordinación ante incidentes de seguridad.
- ***SIEM***: Sistema que recoge y centraliza los logs para analizar alertas y detectar incidentes.
- ***IDS***: Herramienta que analiza el tráfico de red y avisa cuando detecta actividad sospechosa.
- ***OSINT***: Uso de información pública para investigar personas, empresas o infraestructuras.
- ***Threat Intelligence***: Información sobre amenazas y atacantes que ayuda a mejorar la detección y prevención.
- ***Incident Response***: Proceso que se sigue para gestionar y resolver un incidente de seguridad.
- ***Forensics***: Análisis forense de evidencias digitales después de que ocurre un incidente.
- ***Docker***: Plataforma para crear y ejecutar contenedores donde se montó todo el entorno de la práctica.
- ***ELK Stack***: Conjunto de herramientas (Elasticsearch, Logstash y Kibana) que usamos para almacenar y visualizar los logs.
- ***Filebeat***: Agente que recoge los registros y los envía al SIEM.
- ***Snort***: Sistema de detección de intrusos que analiza el tráfico y genera alertas.
- ***Logstash***: Herramienta que procesa y transforma los datos antes de enviarlos a Elasticsearch.
- ***Elasticsearch***: Motor donde se guardan los eventos y los logs.
- ***Kibana***: Interfaz que usamos para ver y analizar las alertas y los datos almacenados.

## 3) (Opcional) Evidencias y recursos usados

No se incluyen evidencias adicionales.

## 4) Conclusión (cierre)

En esta unidad hemos trabajado la parte teórica y práctica sobre la detección y análisis de incidentes. Hemos aprendido cómo clasificar incidentes, cómo darles prioridad y cómo documentarlos correctamente.

La parte de OSINT me ha servido para entender cómo analizar la información pública de una entidad y ver cómo esos datos pueden suponer un riesgo si están expuestos. Con las prácticas vimos cómo buscar dominios, subdominios y empleados, y cómo valorar el impacto de lo que encontramos.

En la práctica montamos un entorno con Docker usando un SIEM con ELK y un IDS como Snort. Gracias a eso vimos cómo se recopilan los logs, cómo se procesan y cómo aparecen las alertas en Kibana. También entendimos mejor cómo funcionan las reglas de detección y cómo se generan las alertas cuando hay tráfico sospechoso.

En general, me ha ayudado a entender cómo se conecta todo: la clasificación de incidentes, la monitorización con el SIEM y la detección con el IDS.

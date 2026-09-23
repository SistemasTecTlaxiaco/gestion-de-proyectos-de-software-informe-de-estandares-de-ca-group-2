# INFORME DE ESTÁNDARES DE CALIDAD ESPERADOS POR STELLAR/DRIPS

## Sistema de Gestión Comercial para Artesanías de Olla de Barro y Canastas Tejidas a Mano

**Instituto Tecnológico de Tlaxiaco**
**Carrera:** Ingeniería en Sistemas Computacionales
**Asignatura:** Gestión de proyectos de software
**Docente:** Ing. Roman Cruz Jose Alfredo
**Grupo:** 7US

### Presentan

* Sandoval Hernández Edgar Axel – 22620093
* Adriana Hernández Martínez – 22620083

**Tlaxiaco, Oaxaca, septiembre de 2026**

---

# Contenido

1. [Introducción](#introducción)
2. [Objetivo](#objetivo)
3. [Descripción del proyecto Open Hub Tec – Mixteca](#descripción-del-proyecto-open-hub-tec--mixteca)
4. [Análisis de Stellar](#análisis-de-stellar)

   * [¿Qué es Stellar?](#qué-es-stellar)
   * [Calidad técnica relacionada con Stellar](#calidad-técnica-relacionada-con-stellar)
5. [Análisis de Drips](#análisis-de-drips)

   * [¿Qué es Drips?](#qué-es-drips)
   * [Código abierto y calidad del software](#código-abierto-y-calidad-del-software)
6. [Adaptación al contexto de la región Mixteca](#adaptación-al-contexto-de-la-región-mixteca)

   * [Propuesta de adaptación](#propuesta-de-adaptación)
   * [Aplicación de Stellar al contexto del proyecto](#aplicación-de-stellar-al-contexto-del-proyecto)
   * [Aplicación de Drips al proyecto](#aplicación-de-drips-al-proyecto)
7. [Pensamiento crítico y riesgos tecnológicos](#pensamiento-crítico-y-riesgos-tecnológicos)

   * [Seguridad](#seguridad)
   * [Transparencia](#transparencia)
   * [Código abierto](#código-abierto)
   * [Transparencia del financiamiento mediante Drips](#transparencia-del-financiamiento-mediante-drips)
8. [Relación entre calidad de software y economía Web3](#relación-entre-calidad-de-software-y-economía-web3)
9. [Propuesta de métricas para Open Hub Tec – Mixteca](#propuesta-de-métricas-para-open-hub-tec--mixteca)
10. [Propuesta de integración al tablero eduScrum](#propuesta-de-integración-al-tablero-eduscrum)
11. [Resultados del análisis](#resultados-del-análisis)
12. [Conclusiones](#conclusiones)
13. [Bibliografía](#bibliografía)

---

# Introducción

El presente informe analiza las características de Stellar y Drips desde la perspectiva de la calidad del software y su posible relación con el proyecto **Open Hub Tec – Mixteca**, cuyo objetivo es desarrollar un sistema de gestión comercial para apoyar a productores de artesanías de olla de barro y canastas tejidas a mano de la región Mixteca.

El proyecto busca facilitar la organización de productos, inventario, información comercial y operaciones relacionadas con los talleres artesanales. Debido a las características de la región, también se considera importante tomar en cuenta las limitaciones de conectividad, el acceso a tecnologías digitales y la necesidad de utilizar herramientas que sean comprensibles y confiables para los usuarios.

Stellar es una red blockchain de código abierto y descentralizada que permite desarrollar aplicaciones, emitir activos y crear contratos inteligentes. Su plataforma de contratos inteligentes proporciona herramientas como SDK, CLI, RPC y ambientes de prueba para el desarrollo de aplicaciones.

Por otra parte, Drips es una plataforma orientada al financiamiento de proyectos de código abierto mediante flujos programables de fondos. Permite financiar repositorios de GitHub y distribuir recursos hacia proyectos y sus dependencias.

El análisis de ambas tecnologías permite identificar prácticas que pueden ser consideradas para mejorar la calidad, seguridad, transparencia y sostenibilidad del proyecto Open Hub Tec – Mixteca.

# Objetivo

Analizar las características técnicas, de calidad, seguridad y financiamiento relacionadas con Stellar y Drips para identificar cómo sus principios pueden adaptarse al proyecto Open Hub Tec – Mixteca, considerando las necesidades de los productores artesanales de la región Mixteca y las limitaciones de conectividad existentes.

# Descripción del proyecto Open Hub Tec – Mixteca

Open Hub Tec – Mixteca es un proyecto enfocado en apoyar a talleres y productores artesanales mediante una solución tecnológica que permita organizar y gestionar información relacionada con sus productos.

El proyecto se enfoca principalmente en:

* Artesanías de ollas de barro.
* Canastas tejidas a mano.
* Información de productos.
* Control de inventario.
* Registro de operaciones.
* Organización de información de los talleres.
* Facilitar la relación entre productores y posibles compradores.
* Considerar mecanismos de pagos transparentes y adaptados a las condiciones de la región.

El proyecto también busca que la solución sea accesible para usuarios que pueden tener diferentes niveles de experiencia tecnológica.

Por esta razón, la calidad del software no debe medirse únicamente por el funcionamiento técnico del sistema, sino también por su facilidad de uso, seguridad, confiabilidad, accesibilidad y capacidad de funcionar adecuadamente bajo condiciones de conectividad limitada.

# Análisis de Stellar

## ¿Qué es Stellar?

Stellar es una red blockchain de código abierto, descentralizada y de tipo peer-to-peer. Su infraestructura permite desarrollar aplicaciones, emitir activos, utilizar contratos inteligentes y conectar aplicaciones con diferentes servicios financieros.

La plataforma proporciona documentación para desarrollar aplicaciones, utilizar tokens, crear contratos inteligentes, trabajar con redes de prueba y acceder a diferentes herramientas de infraestructura.

Para el proyecto Open Hub Tec – Mixteca, Stellar puede estudiarse como una posible tecnología para implementar posteriormente mecanismos relacionados con activos digitales, pagos o registros verificables.

Sin embargo, su incorporación no debería realizarse únicamente por utilizar blockchain. Primero tendría que comprobarse que la tecnología resuelve una necesidad real del proyecto y que puede utilizarse de forma sencilla y segura por los usuarios.

## Calidad técnica relacionada con Stellar

Uno de los aspectos importantes de Stellar es la disponibilidad de herramientas y documentación para los desarrolladores.

Entre las herramientas disponibles se encuentran los SDK, Stellar CLI, herramientas para pruebas y servicios de infraestructura. El Stellar CLI permite construir, desplegar e interactuar con contratos inteligentes, así como configurar identidades y redes.

Además, los SDK relacionados con los contratos inteligentes son de código abierto y cuentan con sus respectivos repositorios y documentación.

Para Open Hub Tec – Mixteca, estas características pueden relacionarse con las siguientes prácticas de calidad:

| Característica           | Aplicación al proyecto                                                              |
| ------------------------ | ----------------------------------------------------------------------------------- |
| **Documentación**        | Mantener instrucciones claras para la instalación, configuración y uso del sistema. |
| **Código abierto**       | Facilitar la revisión del código y la colaboración del equipo.                      |
| **Pruebas**              | Probar las funciones antes de incorporarlas al sistema.                             |
| **Seguridad**            | Validar permisos, usuarios y operaciones antes de registrar información.            |
| **Trazabilidad**         | Mantener registros de las operaciones importantes.                                  |
| **Mantenibilidad**       | Organizar el código para facilitar futuras modificaciones.                          |
| **Control de versiones** | Utilizar GitHub para registrar cambios y evitar la pérdida de avances.              |

De esta manera, el análisis de Stellar permite relacionar las características de una plataforma Web3 con prácticas concretas de calidad de software.

# Análisis de Drips

## ¿Qué es Drips?

Drips es una plataforma enfocada en financiar proyectos y dependencias de código abierto mediante flujos de fondos programables.

Una de sus funciones consiste en permitir que los recursos se distribuyan hacia proyectos de software de código abierto y que los fondos puedan continuar hacia las dependencias utilizadas por esos proyectos.

También permite utilizar listas de proyectos y mecanismos de distribución para apoyar diferentes iniciativas dentro de un ecosistema.

Este concepto resulta relevante para Open Hub Tec – Mixteca porque el proyecto también depende de herramientas, bibliotecas y componentes de software que pueden ser desarrollados y mantenidos por comunidades de código abierto.

## Código abierto y calidad del software

El código abierto permite que otras personas puedan revisar, modificar y contribuir al software. Esto puede favorecer la detección de errores y la colaboración, pero también requiere mecanismos adecuados de control.

En el caso de Drips, su documentación legal indica que el software utiliza diferentes licencias de código abierto, incluyendo GPLv3, Apache 2.0 y MIT. También señala que, debido a su naturaleza experimental, pueden existir errores o defectos que afecten el funcionamiento del software.

Este punto es importante para nuestro proyecto porque demuestra que utilizar software de código abierto no significa que el software sea automáticamente seguro o libre de errores.

Por lo tanto, Open Hub Tec – Mixteca debe mantener procesos de:

* Revisión del código.
* Pruebas funcionales.
* Pruebas de seguridad.
* Control de versiones.
* Revisión de dependencias.
* Documentación.
* Registro de errores.
* Validación antes de publicar cambios.

# Adaptación al contexto de la región Mixteca

Una de las principales características del proyecto es que debe considerar las condiciones reales de la región Mixteca.

No todos los usuarios tendrán necesariamente una conexión rápida y estable a Internet ni el mismo nivel de conocimientos tecnológicos. Por esta razón, una solución diseñada únicamente pensando en un entorno urbano con conectividad constante podría presentar problemas durante su utilización.

Por ello, las métricas tradicionales de calidad deben adaptarse al contexto.

## Propuesta de adaptación

| Métrica de calidad | Adaptación para Open Hub Tec – Mixteca                                  |
| ------------------ | ----------------------------------------------------------------------- |
| **Usabilidad**     | Interfaces sencillas y fáciles de comprender.                           |
| **Rendimiento**    | Reducir el tamaño de archivos e información innecesaria.                |
| **Disponibilidad** | Considerar qué funciones pueden utilizarse ante problemas de conexión.  |
| **Seguridad**      | Proteger información de productores, productos y operaciones.           |
| **Confiabilidad**  | Evitar pérdida de registros cuando exista una interrupción de conexión. |
| **Accesibilidad**  | Utilizar textos claros y elementos fáciles de identificar.              |
| **Mantenibilidad** | Mantener el código organizado y documentado.                            |
| **Portabilidad**   | Considerar dispositivos de diferentes capacidades.                      |

La calidad debe evaluarse considerando no solamente si el sistema funciona en condiciones ideales, sino también si continúa siendo útil cuando existen restricciones de conectividad.

# Aplicación de Stellar al contexto del proyecto

Una posible aplicación futura de Stellar sería utilizar mecanismos de activos digitales o pagos verificables relacionados con las operaciones comerciales del proyecto.

Sin embargo, esta integración debe considerarse como una posibilidad técnica y no como una función obligatoria del sistema actual.

Antes de implementar blockchain sería necesario evaluar:

1. Si los productores realmente necesitan este mecanismo.
2. Si los usuarios pueden utilizarlo fácilmente.
3. Si existe conectividad suficiente.
4. Qué costos tendría su implementación.
5. Qué información debería registrarse en blockchain.
6. Qué información debería permanecer fuera de blockchain.
7. Cómo se protegerían las cuentas y credenciales.
8. Qué procedimiento existiría para recuperar el acceso a una cuenta.

Stellar proporciona mecanismos de autorización para controlar qué operaciones pueden realizarse mediante contratos inteligentes, lo cual es relevante para diseñar controles de seguridad.

# Aplicación de Drips al proyecto

Drips puede relacionarse principalmente con el aspecto de financiamiento y sostenibilidad del desarrollo de software.

El proyecto Open Hub Tec – Mixteca podría utilizar el concepto de financiamiento transparente como referencia para una futura estrategia de apoyo al desarrollo y mantenimiento de la plataforma.

Por ejemplo, si el proyecto llegara a convertirse en una iniciativa de código abierto, podría establecerse un mecanismo para recibir aportaciones destinadas a:

* Mantenimiento del sistema.
* Corrección de errores.
* Mejoras de seguridad.
* Desarrollo de nuevas funciones.
* Infraestructura tecnológica.
* Documentación.
* Apoyo a colaboradores.

Drips demuestra que el financiamiento puede dirigirse no solamente al proyecto principal, sino también a las dependencias de software que forman parte de su infraestructura.

# Pensamiento crítico y riesgos tecnológicos

El uso de blockchain y herramientas de código abierto presenta beneficios, pero también riesgos que deben analizarse antes de incorporarlos.

## Seguridad

Una aplicación que maneje operaciones financieras o activos digitales debe contar con controles adecuados de autorización y protección de cuentas.

Un error en un contrato inteligente puede tener consecuencias importantes porque las operaciones registradas en una blockchain pueden ser difíciles de modificar posteriormente.

Por esta razón, el proyecto debe considerar pruebas y auditorías antes de utilizar contratos inteligentes en producción.

Stellar cuenta incluso con un programa de apoyo para auditorías de seguridad de proyectos elegibles desarrollados con su plataforma de contratos inteligentes.

## Transparencia

La transparencia puede ser una ventaja cuando permite verificar determinadas operaciones. Sin embargo, también puede generar problemas de privacidad si se registra información que permita identificar innecesariamente a una persona.

Por lo tanto, Open Hub Tec – Mixteca debe diferenciar entre:

* Información pública.
* Información interna.
* Información personal.
* Información comercial.
* Información que puede registrarse de forma verificable.

## Código abierto

El código abierto facilita la colaboración y revisión, pero también puede introducir riesgos relacionados con dependencias vulnerables, errores de programación o modificaciones no revisadas.

Por ello, el equipo debe aplicar controles de calidad independientemente de que una herramienta sea de código abierto.

# Transparencia del financiamiento mediante Drips

Uno de los aspectos relevantes de Drips es la posibilidad de crear flujos de financiamiento que pueden distribuir recursos entre diferentes proyectos.

Esto permite plantear una reflexión para Open Hub Tec – Mixteca:

> Si el proyecto recibe financiamiento para desarrollar una plataforma de código abierto, ¿cómo se podría demostrar que los recursos realmente se utilizan para mantener y mejorar el software?

Una posible respuesta consiste en combinar:

* Repositorios públicos.
* Registro de cambios.
* Issues.
* Pull Requests.
* Documentación.
* Evidencias de pruebas.
* Registro de versiones.
* Reportes de actividades.
* Mecanismos transparentes de financiamiento.

De esta forma, la calidad técnica y la transparencia financiera pueden complementarse.

# Relación entre calidad de software y economía Web3

La calidad del software y el financiamiento Web3 pueden considerarse áreas diferentes, pero tienen una relación importante dentro de un proyecto tecnológico.

Un software que administra información comercial debe ser confiable y seguro. Si además incorpora mecanismos de pagos o activos digitales, los errores pueden tener consecuencias económicas.

Por ello, la calidad deja de ser solamente una característica técnica y también se convierte en una condición para proteger los recursos de los usuarios.

La relación puede representarse de la siguiente manera:

**Calidad del software → Seguridad → Confianza del usuario → Uso del sistema → Sostenibilidad del proyecto**

En este contexto, Stellar puede aportar infraestructura blockchain para determinadas funciones y Drips puede servir como referencia para mecanismos de financiamiento de proyectos y dependencias de código abierto.

# Propuesta de métricas para Open Hub Tec – Mixteca

Para evaluar la calidad del proyecto se propone utilizar las siguientes métricas:

| Área               | Indicador propuesto                            | Objetivo                        |
| ------------------ | ---------------------------------------------- | ------------------------------- |
| **Usabilidad**     | Porcentaje de tareas completadas correctamente | Verificar facilidad de uso.     |
| **Rendimiento**    | Tiempo de respuesta                            | Mantener respuestas aceptables. |
| **Seguridad**      | Vulnerabilidades detectadas                    | Reducir riesgos.                |
| **Confiabilidad**  | Errores durante las pruebas                    | Disminuir fallos.               |
| **Disponibilidad** | Funcionamiento ante interrupciones             | Reducir pérdida de información. |
| **Mantenibilidad** | Tiempo para corregir errores                   | Facilitar mantenimiento.        |
| **Código**         | Pull Requests revisadas                        | Mejorar control de cambios.     |
| **Documentación**  | Funciones documentadas                         | Facilitar mantenimiento.        |
| **Conectividad**   | Funciones disponibles con conexión limitada    | Adaptarse al contexto regional. |
| **Financiamiento** | Registro transparente de recursos              | Mejorar trazabilidad.           |

# Propuesta de integración al tablero eduScrum

El análisis también puede incorporarse al flujo de trabajo del equipo mediante el tablero eduScrum utilizado para el proyecto.

Las actividades pueden organizarse de la siguiente manera:

### Propuestas

* Investigar características de Stellar.
* Investigar características de Drips.
* Identificar necesidades de calidad del proyecto.

↓

### Revisión por IA

* Comparar los requisitos encontrados con el proyecto.
* Identificar riesgos técnicos.
* Revisar posibles aplicaciones.

↓

### Aprobada por el equipo

* Seleccionar las propuestas que tienen relación con Open Hub Tec – Mixteca.
* Definir cuáles pueden incorporarse al informe.

↓

### En desarrollo

* Elaborar el análisis técnico.
* Adaptar las métricas de calidad.
* Analizar seguridad y transparencia.
* Relacionar Web3 con el financiamiento del proyecto.

↓

### Terminada

* Integrar el informe.
* Revisar las evidencias.
* Corregir redacción.
* Verificar que se cumplan los criterios de la rúbrica.

# Resultados del análisis

A partir de la investigación realizada se identificó que Stellar proporciona una infraestructura de código abierto orientada al desarrollo de aplicaciones blockchain y contratos inteligentes, mientras que Drips se enfoca en mecanismos de financiamiento programable y apoyo a proyectos de código abierto.

Para Open Hub Tec – Mixteca, las dos tecnologías pueden estudiarse desde perspectivas diferentes:

* **Stellar** puede relacionarse con pagos, activos digitales y contratos inteligentes.
* **Drips** puede relacionarse con financiamiento y sostenibilidad de proyectos de código abierto.
* Ambas permiten analizar la importancia de la transparencia.
* Ambas muestran la necesidad de considerar la seguridad.
* El código abierto requiere procesos de revisión y mantenimiento.
* La tecnología debe adaptarse a las condiciones reales de los usuarios.

También se identificó que no sería adecuado incorporar una tecnología Web3 solamente por ser innovadora. La decisión debe depender de las necesidades reales del proyecto, los costos, la conectividad, la facilidad de uso, la seguridad y los conocimientos de los usuarios.

# Conclusiones

El análisis de Stellar y Drips permitió comprender que la calidad de un proyecto tecnológico no depende únicamente de que sus funciones sean desarrolladas correctamente, sino también de la seguridad, documentación, mantenimiento, transparencia y adaptación al contexto donde será utilizado.

Stellar presenta herramientas para desarrollar aplicaciones y contratos inteligentes sobre una red blockchain de código abierto. Estas características pueden ser consideradas en futuras etapas de Open Hub Tec – Mixteca si se identifica una necesidad real relacionada con pagos, activos digitales o registros verificables.

Drips, por su parte, muestra una forma de relacionar el código abierto con mecanismos de financiamiento programable. Su modelo permite observar cómo los recursos pueden distribuirse entre proyectos y dependencias, lo cual proporciona una referencia para pensar en la sostenibilidad económica de proyectos de software abiertos.

Desde el punto de vista crítico, también se concluye que blockchain y código abierto no eliminan los riesgos de seguridad. Es necesario realizar pruebas, revisar dependencias, controlar cambios, proteger las cuentas y analizar cuidadosamente qué información debe hacerse pública.

# Bibliografía

Drips. (2026). *Drips: Fund open source in your ecosystem*. https://www.drips.network/

Drips. (2026). *Dependency funding*. https://www.drips.network/solutions/dependency-funding

Drips. (2026). *Disclaimer*. https://www.drips.network/legal/disclaimer

Stellar Development Foundation. (2026). *Stellar developer documentation*. https://developers.stellar.org/

Stellar Development Foundation. (2026). *Stellar smart contracts*. https://stellar.org/soroban

Stellar Development Foundation. (2026). *Grants and funding*. https://stellar.org/grants-and-funding

Stellar Development Foundation. (2026). *Smart contract security audit support*. https://stellar.org/grants-and-funding/soroban-audit-bank

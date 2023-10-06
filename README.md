
Herramientas-de-Desarrollo-en-Linux

Z shell, abreviada como zsh, es un potente intérprete de comandos para sistemas operativos de tipo Unix, como los sistemas BSD o GNU/Linux. Fue escrito por Paul Falstad en 1990 cuando era estudiante en la Universidad de Princeton.
Zsh se diseñó para ser utilizado de forma interactiva y ha incorporado muchas de las características principales de otras shells de Unix, como bash, ksh y tcsh, además de tener características propias, que incluyen:

Completar la línea de comandos programable que ayuda al usuario a escribir tanto las opciones como los argumentos de la mayoría de los comandos utilizados, con soporte inmediato para varios cientos de comandos.
Compartir el historial entre todos los shells en funcionamiento.
El globbing de archivos extendido permite la especificación de archivos sin necesidad de ejecutar un programa externo como find.
Mejora del manejo de variables/arreglos.
Edición de comandos multilínea en una sola memoria intermedia.
Corrección ortográfica y relleno automático de los nombres de los comandos (y opcionalmente de los argumentos, que se asumen como nombres de archivo).
Varios modos de compatibilidad, por ejemplo, Zsh puede fingir ser una Bourne Shell cuando se ejecuta como /bin/sh.

¿Qué es Git?
Git es un software de control de versiones diseñado por Linus Torvalds. Fue creado pensando en la eficiencia, la confiabilidad y la compatibilidad del mantenimiento de versiones de aplicaciones que tienen un gran número de archivos de código fuente. Su propósito principal es llevar un registro de los cambios en archivos de computadora, incluyendo coordinar el trabajo que varias personas realizan sobre archivos compartidos en un repositorio de código.

¿Qué es OhMyZsh?
Oh My Zsh es una herramienta muy útil que se puede utilizar en el terminal de Windows cuando se ejecuta una distribución de Linux bajo WSL (Windows Subsystem for Linux). Puede instalarse mediante comandos como wsl -l -v y git --version. Oh My Zsh mejora la experiencia del usuario en el terminal y ofrece una variedad de temas y complementos para personalizarlo.

Para instalar Oh My Zsh en una distribución de Linux bajo WSL, puedes seguir estos pasos:

´sudo apt update´
sudo apt install git zsh -y
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
Luego, puedes personalizar el tema de Oh My Zsh editando el archivo ~/.zshrc.
Pero si algo tiene Oh My ZSH, es la personalización, para ello solo tendremos que abrir nuestro editor preferido, editar el fichero de configuración alojado en ~/.zshrc y establecer el tema que más nos guste
nano ~/.zshrc
Uno de los temas más famosos sin lugar a dudas es "agnoster" y es que este tema nos permite ver muy fácilmente la rama en la que estamos trabajando, si tenemos un cambio pendiente 

¿Qué es Docker?
Docker es una plataforma de código abierto que permite a los desarrolladores crear, implementar, ejecutar, actualizar y gestionar contenedores. Estos contenedores son componentes estandarizados y ejecutables que combinan el código fuente de la aplicación con las bibliotecas y dependencias del sistema operativo necesarias para ejecutar esa aplicación en cualquier entorno.

¿Qué es Docker Compose?
Docker Compose es una herramienta para definir y ejecutar aplicaciones de Docker que consisten en varios contenedores. Utiliza un archivo YAML para configurar los servicios de la aplicación y permite crear e iniciar todos los servicios con un solo comando. Es útil para administrar aplicaciones complejas que constan de varios contenedores interconectados.

SDKMAN! es una herramienta que se utiliza para gestionar múltiples versiones de SDKs en sistemas Unix. Proporciona una interfaz de línea de comandos y un API para instalar, cambiar, eliminar y listar candidatos. Es especialmente útil para el desarrollo de aplicaciones que requieren versiones específicas de lenguajes o herramientas, como Java o Groovy.

Para instalar SDKMAN!:

curl -s "https://get.sdkman.io" | bash
Luego, puedes usarlo para instalar SDKs y gestionar versiones según tus necesidades.

Java 8 y Java 11
Java 8 es la versión más reciente de Java que incluye nuevas características, mejoras y correcciones de errores para mejorar la eficacia en el desarrollo y la ejecución de programas Java. Java 11, por otro lado, es la primera versión LTS (soporte a largo plazo) oficial de Java.
Java 17 es la última versión de soporte a largo plazo (LTS, por sus siglas en inglés) dentro de la cadencia de lanzamiento semestral de Java y es el resultado de una amplia colaboración entre los ingenieros de Oracle y otros miembros de la comunidad global de desarrolladores.

¿Qué es Maven?
Maven es una herramienta de software utilizada para la gestión y construcción de proyectos Java. Utiliza un Project Object Model (POM) para describir el proyecto de software, sus dependencias y el orden de construcción de los elementos. Maven simplifica tareas como la compilación, el empaquetado y la gestión de dependencias en proyectos Java.

Eclipse es una plataforma de software de código abierto que se utiliza para desarrollar aplicaciones "de Cliente Enriquecido". Ofrece un entorno de desarrollo integrado (IDE) para escribir, compilar y depurar código en varios lenguajes de programación, incluido Java.

Visual Studio Code (VS Code) es un editor de código fuente independiente desarrollado por Microsoft. Es multiplataforma y admite una amplia variedad de lenguajes de programación. VS Code se integra bien con Git, ofrece funciones de depuración y se puede personalizar con extensiones.

NVM (Node Version Manager) y Node.js
NVM, o Node Version Manager, es un script utilizado para administrar múltiples versiones de Node.js en sistemas Unix.

Node.js Es un entorno de tiempo de ejecución de JavaScript que permite ejecutar código JavaScript en el servidor. Con NVM, puedes cambiar y gestionar fácilmente las versiones de Node.js según tus necesidades.

NPM Es un gestor de paquetes para proyectos de Node.js. Permite instalar, actualizar y administrar las dependencias de un proyecto Node.js de manera eficiente. npm es ampliamente utilizado en el ecosistema de desarrollo de Node.js.

Vue.js, pronunciado "view," es un framework progresivo para construir interfaces de usuario. A diferencia de otros frameworks monolíticos, Vue.js se puede utilizar incrementalmente y es fácil de integrar con otros proyectos. Es especialmente adecuado para la construcción de aplicaciones de una sola página (SPA).

Postman es una aplicación que se utiliza para probar colecciones o catálogos de APIs, organizar servicios web en carpetas, generar documentación de APIs y trabajar con entornos de desarrollo. Es una herramienta útil para los desarrolladores que trabajan con APIs RESTful.

Para qué sirve Postman
Postman sirve para múltiples tareas dentro de las cuales destacaremos en esta oportunidad las siguientes:

Testear colecciones o catálogos de APIs tanto para Frontend como para Backend.
Organizar en carpetas, funcionalidades y módulos los servicios web.
Permite gestionar el ciclo de vida (conceptualización y definición, desarrollo, monitoreo y mantenimiento) de nuestra API.
Generar documentación de nuestras APIs.
Trabajar con entornos (calidad, desarrollo, producción) y de este modo es posible compartir a través de un entorno cloud la información con el resto del equipo involucrado en el desarrollo.
Métodos más utilizados y posibles errores
Postman cuenta con una serie de métodos que nos permiten tomar acción ante nuestras peticiones, a continuación, te dejamos los más utilizados:

GET: Obtener información
POST: Agregar información
PUT: Reemplazar la información
PATCH: Actualizar alguna información
DELETE: Borrar información
En cuanto a los posibles errores que podemos apreciar en la respuesta que nos ofrece la herramienta, lo resumiremos en que si la respuesta dada se encuentra en el rango de “200” quiere decir que toda la petición ha salido sin inconvenientes; mientras que el rango de los códigos de error “400” hacen referencia a errores con el cliente y aquellos errores en la línea de los “500” tienen que ver con fallos en el servidor.

Utilerias Linux
Telnet y Curl
Telnet es un protocolo que permite conectarse a otros sistemas a través de la red y acceder a ellos de forma remota. Puede ser útil para administrar sistemas de forma remota, aunque es menos seguro que otras opciones como SSH.

Curl es una herramienta de línea de comandos que permite realizar transferencias de datos con URL. Se utiliza comúnmente para descargar archivos desde la web y realizar solicitudes HTTP y FTP.

Grep, Sed y Awk
Grep es una utilería que busca patrones de texto en archivos. Se utiliza para buscar y filtrar información en archivos de texto.

Sed es un editor de flujo que se utiliza para realizar transformaciones de texto en archivos o secuencias de texto.

Awk es un lenguaje de programación diseñado para el procesamiento de texto. Se utiliza para realizar tareas de manipulación de datos en archivos de texto estructurados.

Estos son algunos de los comandos y herramientas que se utilizan en sistemas Unix y Linux para realizar tareas comunes de administración y desarrollo. Puedes explorar y aprender más sobre cada uno de ellos según tus necesidades específicas.

MySQL Workbench: Es una herramienta de administración y desarrollo de bases de datos relacionales MySQL. Está diseñada para facilitar la creación, diseño, mantenimiento y administración de bases de datos MySQL. Es una aplicación gráfica que proporciona una interfaz de usuario intuitiva y rica en características para interactuar con bases de datos MySQL.

Algunas de las principales características y funciones de MySQL Workbench son las siguientes:

Diseño de base de datos: Permite diseñar visualmente la estructura de una base de datos utilizando diagramas de entidad-relación (ERD). Los usuarios pueden crear tablas, definir relaciones entre tablas, establecer claves primarias y foráneas, y más.

Consultas SQL: Proporciona un editor de consultas SQL con resaltado de sintaxis y autocompletado para facilitar la escritura y ejecución de consultas SQL en la base de datos.

Administración de usuarios y privilegios: Permite gestionar usuarios y asignar privilegios específicos a los usuarios en la base de datos, controlando quién tiene acceso y qué operaciones pueden realizar.

Migración de datos: Facilita la migración de datos desde otras bases de datos hacia MySQL o desde MySQL hacia otros sistemas de gestión de bases de datos.

Generación de informes: Ofrece herramientas para crear informes personalizados basados en datos de la base de datos, lo que puede ser útil para generar informes empresariales.

Rendimiento y ajuste: Proporciona herramientas para supervisar y ajustar el rendimiento de la base de datos, lo que incluye la visualización de estadísticas y la optimización de consultas.

Modelado de datos: Permite realizar ingeniería inversa de bases de datos existentes para generar un modelo visual que represente la estructura de la base de datos.

Control de versiones: Facilita la integración con sistemas de control de versiones como Git, lo que permite a los equipos de desarrollo colaborar en el diseño y desarrollo de la base de datos.

MySQL Workbench es una herramienta muy útil para administradores de bases de datos, desarrolladores de aplicaciones y cualquier persona que trabaje con bases de datos MySQL. Proporciona una forma eficiente y visual de interactuar con la base de datos, lo que facilita tareas como el diseño de esquemas, la escritura de consultas y la administración de usuarios y permisos.

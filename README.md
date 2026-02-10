#Práctica 1 - Flujo Básico de git y github
practica 2:

1 ¿Qué es una Base De Datos Relacional?
Es básicamente un conjunto de información organizada en tablas que se conectan entre sí mediante datos compartidos. La idea principal es que no tienes la info regada por todos lados, sino que usas un modelo basado en la lógica de conjuntos para que todo esté estructurado, sea fácil de encontrar y no se repita innecesariamente.

2 ¿Qué es una Tabla?
Imagina que es como una hoja de cálculo de Excel. Es la unidad básica donde guardas los datos; tiene un nombre específico (como "Clientes" o "Ventas") y está formada por columnas que definen qué tipo de dato vas a meter y renglones que son los registros reales.

3 ¿Qué es una relación?
Es el "vínculo" o la conexión que existe entre dos tablas. Se logra cuando una tabla usa una clave de otra (como el ID de un usuario) para conectar la información. Gracias a esto, puedes saber qué cliente hizo qué compra sin tener que escribir el nombre del cliente veinte veces en la tabla de ventas.


4 ¿Qué representa una columna?
Representa un atributo o una característica específica de lo que estás guardando. Si tu tabla es de "Libros", las columnas serían cosas como el Título, el Autor o el ISBN. Básicamente, definen la estructura y el tipo de dato que va en esa sección.

5 ¿Qué representa un renglón?
Un renglón (o fila) es un registro único e individual. Es donde vive la información real de un solo objeto. Por ejemplo, en una tabla de usuarios, un renglón completo serían todos los datos de "Juan Pérez": su nombre, su correo y su fecha de nacimiento.

6 ¿Qué es un motor de base de datos relacional?
Es el software (o el "cerebro") que se encarga de gestionar todo. Es el que realmente guarda los datos en el disco duro, controla quién puede verlos, asegura que no se corrompan y procesa todas las consultas que le pides. Se le conoce formalmente como RDBMS (Relational Database Management System).

7 ¿Cuáles son los motores más populares?
Hoy en día, los que mandan en el mercado son:

MySQL: Súper común para web.
PostgreSQL: Muy potente y de código abierto.
Microsoft SQL Server: El estándar para empresas que usan Windows.

8 ¿Cuál es el motor ligero que no necesita servidor?
Ese es SQLite. Es genial porque toda la base de datos es un solo archivo y no necesitas instalar un proceso que esté corriendo de fondo. Se usa muchísimo en apps de celular (Android/iOS) y en programas de escritorio sencillos.

9 ¿Qué significa SQL?
Significa Structured Query Language (Lenguaje de Consulta Estructurado). Es el idioma universal que usamos para hablarle a la base de datos. Con SQL le decimos "oye, búscame esto", "inserta este dato" o "borra aquello".

10 ¿Cuáles son los elementos de un sistema de información basado en BD relacionales?
Para que todo esto funcione, necesito varios componentes clave que trabajen en equipo. Primero están los datos, que son la materia prima, y el motor de base de datos (software) que los administra.

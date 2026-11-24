🦷 Cariño Dental Studio
Sistema Integral de Gestión Odontológica

<p align="center">
Sistema web para la gestión inteligente de pacientes, citas, tratamientos y administración clínica.
</p>

<p align="center">
<img src="https://img.shields.io/badge/Java-17%2B-orange?style=for-the-badge&logo=openjdk" />
<img src="https://img.shields.io/badge/Spring%20Boot-3-green?style=for-the-badge&logo=springboot" />
<img src="https://img.shields.io/badge/MySQL-Database-blue?style=for-the-badge&logo=mysql" />
<img src="https://img.shields.io/badge/Maven-Build-red?style=for-the-badge&logo=apachemaven" />
<img src="https://img.shields.io/badge/JavaScript-ES6-yellow?style=for-the-badge&logo=javascript" />
</p>

📌 Sobre el proyecto

Cariño Dental Studio es un sistema web integral desarrollado para optimizar la gestión médica y administrativa de una clínica odontológica.

El proyecto busca centralizar los procesos de atención, automatizar las reservas de citas y facilitar el seguimiento de los pacientes mediante una plataforma moderna, intuitiva y adaptable a dispositivos móviles.

Desarrollado con una arquitectura basada en Java Spring Boot, MySQL y tecnologías web.

Ubicación del proyecto: Ayacucho, Perú.

✨ Características principales
Módulo	Descripción
🧑‍⚕️ Gestión de pacientes	Registro y administración de pacientes
📅 Agenda y citas	Reservas, confirmaciones y reprogramaciones
🕒 Disponibilidad	Visualización de horarios libres y ocupados
📋 Historial clínico	Seguimiento de diagnósticos y procedimientos
💰 Finanzas y KPIs	Indicadores de ingresos y actividad clínica
🦷 Odontograma	Módulo en desarrollo
👥 Roles del sistema
1. Paciente
Registro de datos personales.
Consulta de disponibilidad.
Reserva de citas.
Consulta de información de atención.
Comprobante digital de reserva.
2. Asistente / Supervisor
Gestión de agenda diaria.
Confirmación y cancelación de citas.
Reprogramación de horarios.
Bloqueo de horarios no disponibles.
Administración de pacientes.
3. Odontólogo / Administrador
Acceso a la gestión de pacientes.
Consulta de historiales clínicos.
Registro de tratamientos.
Seguimiento de pacientes.
Reportes y estadísticas financieras.
🎨 Diseño y experiencia de usuario

El sistema utiliza una identidad visual elegante y minimalista:

Blanco: #FFFFFF
Blanco cálido: #FAFAF8
Oro champán: #C5A059
Oro oscuro: #A37E36
Negro mate: #18181B

Diseño responsive con enfoque Mobile First.

🛠️ Tecnologías utilizadas
Tecnología	Uso
Java	Lenguaje principal
Spring Boot 3	Backend y API REST
Spring Data JPA	Persistencia de datos
MySQL	Base de datos relacional
Maven	Gestión de dependencias
HTML5	Estructura web
CSS3	Diseño e interfaces
JavaScript	Interactividad
Node.js	Servidor local auxiliar
🏗️ Arquitectura del proyecto
text
carino-dental-studio/
│
├── database/
│   ├── schema.sql
│   └── data.sql
│
├── src/
│   └── main/
│       ├── java/com/clinica/odontologia/
│       │   ├── config/
│       │   ├── controller/
│       │   ├── dto/
│       │   ├── entity/
│       │   ├── repository/
│       │   └── service/
│       │
│       └── resources/
│           ├── application.properties
│           ├── application-mysql.properties
│           └── static/
│               ├── css/
│               ├── img/
│               ├── js/
│               ├── index.html
│               ├── admin.html
│               └── paciente.html
│
├── pom.xml
├── server.js
├── .gitignore
└── README.md

🚀 Instalación y ejecución local
Requisitos previos
Java JDK compatible con el proyecto.
Maven.
MySQL 8.
Node.js (para el servidor auxiliar).
Git.
1. Clonar el repositorio
bash
git clone https://github.com/MasterYHONATAN/carino-dental-studio.git

bash
cd carino-dental-studio

2. Configurar la base de datos

Crear la base de datos y ejecutar los scripts:

sql
source database/schema.sql;
source database/data.sql;

3. Configurar MySQL

Editar localmente:

src/main/resources/application-mysql.properties

Configurar los datos de conexión correspondientes.

No publicar contraseñas ni credenciales reales.

4. Ejecutar Spring Boot
bash
mvn spring-boot:run -Dspring-boot.run.profiles=mysql

5. Acceder al sistema
Portal del paciente: http://localhost:8080/index.html
Panel administrativo: http://localhost:8080/admin.html
Alternativa: servidor Node.js
bash
node server.js


Esta alternativa permite visualizar el frontend si el servidor está configurado para servir esos archivos. No sustituye el backend Spring Boot ni su base de datos.

📸 Capturas de pantalla

Próximamente se agregarán imágenes de las interfaces principales:

Portal de pacientes.
Panel administrativo.
Agenda de citas.
Historial clínico.
Dashboard financiero.
Odontograma.
🔐 Seguridad

El proyecto contempla la importancia de proteger la información clínica y administrativa.

No publicar contraseñas ni claves API.
Utilizar variables de entorno para credenciales.
No almacenar datos reales de pacientes en archivos públicos.
Implementar controles de acceso por roles.
Utilizar conexiones seguras HTTPS en producción.
Realizar copias de seguridad de la base de datos.

Aviso: antes de utilizar el sistema con pacientes reales, deben verificarse los controles de autenticación, autorización, privacidad, auditoría y protección de datos.

🌐 Despliegue

El proyecto está preparado para trabajar hacia un entorno de producción mediante:

Backend Java Spring Boot.
Base de datos MySQL.
Variables de entorno.
Plataforma de alojamiento en la nube.

El enlace público se agregará cuando el despliegue esté completado y verificado.

🗺️ Próximas mejoras
Despliegue en la nube.
Configuración de dominio personalizado.
Protección avanzada de usuarios y roles.
Notificaciones automáticas.
Odontograma interactivo completo.
Reportes PDF.
Copias de seguridad automatizadas.
Mejoras de experiencia móvil.
👨‍💻 Desarrollador

MasterYHONATAN

GitHub: @MasterYHONATAN

Repositorio: carino-dental-studio

<p align="center">
🦷 <strong>Cariño Dental Studio</strong>
<br/>
Tecnología, innovación y atención odontológica.
<br/>
Ayacucho, Perú 🇵🇪
</p>

<div align="center">

# 🦷 Cariño Dental Studio

### Sistema integral de gestión odontológica

<p>
  <strong>Paciente, citas y administración clínica</strong> en una plataforma moderna, rápida y adaptable.
</p>

[![Java](https://img.shields.io/badge/Java-17+-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.java.com/)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-3-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=1f1f1f)](https://developer.mozilla.org/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/Estado-En%20desarrollo-C5A059?style=for-the-badge)](https://github.com/MasterYHONATAN/carino-dental-studio)

📍 **Ayacucho, Perú** &nbsp; · &nbsp; [Repositorio](https://github.com/MasterYHONATAN/carino-dental-studio)

</div>

---

## ✨ ¿Qué hace diferente a Cariño Dental Studio?

<table>
<tr>
<td width="50%">

### 🧑‍⚕️ Atención organizada
Registro completo de pacientes y seguimiento de diagnósticos, procedimientos e información clínica.

</td>
<td width="50%">

### 📅 Citas sin complicaciones
Consulta de disponibilidad, reservas, confirmaciones, cancelaciones y reprogramaciones.

</td>
</tr>
<tr>
<td>

### 📊 Gestión inteligente
Indicadores financieros, actividad clínica y reportes para una administración más eficiente.

</td>
<td>

### 📱 Experiencia adaptable
Interfaz responsive diseñada para funcionar cómodamente desde computadora y dispositivos móviles.

</td>
</tr>
</table>

## 🧩 Módulos principales

| Área | Funcionalidades |
| :--- | :--- |
| 👤 **Pacientes** | Registro, edición y administración de datos personales |
| 📅 **Agenda** | Disponibilidad, reserva y reprogramación de citas |
| 🕘 **Horarios** | Visualización y bloqueo de horarios disponibles |
| 📋 **Historial clínico** | Seguimiento de diagnósticos y tratamientos |
| 💰 **Administración** | Indicadores financieros y actividad clínica |
| 🦷 **Odontograma** | Planificación visual en desarrollo |

## 👥 Roles del sistema

- **Paciente** — consulta la disponibilidad, reserva citas y conserva su comprobante digital.
- **Asistente / Supervisor** — administra la agenda, confirma citas y gestiona pacientes.
- **Odontólogo / Administrador** — revisa pacientes e historiales, registra tratamientos y consulta estadísticas.

---

## 🛠️ Tecnología

<div align="center">

| Backend | Datos | Frontend | Herramientas |
| :---: | :---: | :---: | :---: |
| Java · Spring Boot 3 | MySQL · JPA | HTML5 · CSS3 · JavaScript | Maven · Node.js |

</div>

### Composición del proyecto

- **JavaScript** — 44.1%
- **HTML** — 34.3%
- **Java** — 18.3%
- **CSS** — 3.3%

## 🏗️ Arquitectura

```text
carino-dental-studio/
├── database/
│   ├── schema.sql
│   └── data.sql
├── src/
│   └── main/
│       ├── java/com/clinica/odontologia/
│       │   ├── config/
│       │   ├── controller/
│       │   ├── dto/
│       │   ├── entity/
│       │   ├── repository/
│       │   └── service/
│       └── resources/
│           ├── application.properties
│           ├── application-mysql.properties
│           └── static/
├── pom.xml
└── server.js
```

---

## 🚀 Ejecutar localmente

### Requisitos

- Java JDK compatible
- Maven
- MySQL 8
- Node.js
- Git

### 1. Clonar

```bash
git clone https://github.com/MasterYHONATAN/carino-dental-studio.git
cd carino-dental-studio
```

### 2. Crear la base de datos

Abre MySQL y ejecuta:

```sql
source database/schema.sql;
source database/data.sql;
```

### 3. Configurar la conexión

Edita `src/main/resources/application-mysql.properties` con tus datos locales.

> ⚠️ Nunca publiques contraseñas, claves privadas o información real de pacientes.

### 4. Iniciar el backend

```bash
mvn spring-boot:run -Dspring-boot.run.profiles=mysql
```

### 5. Abrir el sistema

- Portal del paciente: <http://localhost:8080/index.html>
- Panel administrativo: <http://localhost:8080/admin.html>

También puedes probar el frontend con:

```bash
node server.js
```

> El servidor Node.js es una alternativa auxiliar para el frontend. No reemplaza Spring Boot ni la base de datos.

---

## 📸 Capturas de pantalla

> Próximamente se agregarán imágenes del portal de pacientes, agenda, historial clínico, panel administrativo y odontograma.

## 🔐 Seguridad y privacidad

- Utilizar variables de entorno para credenciales.
- No subir datos reales de pacientes.
- Implementar autenticación y autorización por roles.
- Usar HTTPS en producción.
- Aplicar copias de seguridad periódicas.
- Validar auditoría, privacidad y protección de datos antes de usar el sistema con pacientes reales.

## 🗺️ Próximas mejoras

- [ ] Despliegue en la nube y dominio personalizado
- [ ] Odontograma interactivo completo
- [ ] Notificaciones automáticas
- [ ] Reportes PDF
- [ ] Copias de seguridad automatizadas
- [ ] Seguridad avanzada de usuarios y roles
- [ ] Mejoras adicionales para dispositivos móviles

## 🎨 Identidad visual

| Blanco | Blanco cálido | Oro champán | Oro oscuro | Negro mate |
| :---: | :---: | :---: | :---: | :---: |
| `#FFFFFF` | `#FAFAF8` | `#C5A059` | `#A37E36` | `#18181B` |

---

<div align="center">

## 👨‍💻 Desarrollador

**MasterYHONATAN** · [@MasterYHONATAN](https://github.com/MasterYHONATAN)

🦷 **Cariño Dental Studio**  
Tecnología, innovación y atención odontológica

*Ayacucho, Perú 🇵🇪*

</div>


# HOSKA

_Propuesta para optimizar y escalar AUKA_: **HOSKA**.

HOSKA es una aplicación multiplataforma diseñada para agilizar y mejorar la eficiencia de la comunicación entre todo el personal hospitalario. Su objetivo principal es resolver las diversas barreras comunicacionales que enfrentan los hospitales, como la dispersión de la información, demoras en la respuesta, falta de trazabilidad, sobrecarga de información y errores por comunicación deficiente.

## Características

*   **Multiplataforma**: La aplicación será accesible desde dispositivos móviles (smartphones, tablets) y computadoras de escritorio.
*   **Alertas y Notificaciones Inteligentes**: Incluye un sistema de alertas personalizables para emergencias, códigos internos (ej. "Código Azul"), y eventos críticos, con notificaciones push configurables según roles y responsabilidades.
*   **Directorio de Personal Integrado**: Contará con una base de datos actualizada que incluye información de contacto, rol del personal, función de búsqueda rápida y estado de disponibilidad.
*   **Perfiles de Usuario y Roles**: Permite un acceso diferenciado a funcionalidades y permisos según el rol del usuario (médico, enfermera, administrativo, etc.), con gestión centralizada de usuarios y permisos.
*   **Registro y Trazabilidad**: Ofrece un registro de todas las comunicaciones realizadas dentro de la plataforma para fines de auditoría y mejora continua.
*   **Integración Potencial**: Prevé la integración con sistemas existentes como el historial clínico electrónico (HCE) o sistemas de llamada de enfermería y equipos médicos.

## Tecnologías

**Cliente**: EJS, Javascript
 
**Servidor**: NodeJS, Express, Websockets 

## Variables de Entorno

Variables para la conexión con la base de datos

`BD_USUARIO = "root"`

`BD_CONTRASENA = ""`

`BD_HOST = "localhost"`

`BD_PUERTO = "3306"`

`BD_BASE = "hoska"`

---

`RONDAS = 5`

`PUERTO_API = 3000`

`PUERTO_WEB = 4000`

`API_URL = "http://localhost:3000/api"`

`JWT_SECRET = "OBLIGATORIO_CAMBIAR"`

## Ejecución Local

Clona el proyecto

```bash
  git clone https://github.com/Exaedro/hoska
```

Dirigete a la carpeta del proyecto

```bash
  cd hoska
```

Instala las dependencias

```bash
  npm install
```

Inicia el servidor

```bash
  npm run start
```

## Autores

*   **Sassone Sosa Nahiara**
*   **Leites Thiago**
*   **Grippaldi Julián**
---
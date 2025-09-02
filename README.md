# Temario-de-Aplicaciones-Web
Accede a GitHub y crea un repositorio llamado Temario de Aplicaciones Web con el archivo README en donde investigarás con imágenes los temas propuestos.
# fundamentos del desarrollo de aplicaciones web  
<img width="229" height="155" alt="image" src="https://github.com/user-attachments/assets/dd71825c-a876-4492-aaa3-948ad0ceb486" />  

1. Introducción al desarrollo web  
1.1 Historia y evolución del desarrollo web
Años 90: Nacen las primeras páginas web estáticas (HTML).
Década de 2000: Surgen tecnologías como JavaScript, CSS y PHP, haciendo la web más interactiva.
Actualidad: Proliferan aplicaciones web avanzadas (SPA, PWA) que ofrecen experiencias similares a aplicaciones nativas.  
1.2 Tipos de aplicaciones web
Estáticas: Solo muestran información fija (HTML, CSS).
Dinámicas: El contenido cambia según la interacción del usuario o datos del servidor (PHP, MySQL).
SPA (Single Page Application): Cargan una sola página y actualizan el contenido dinámicamente (React, Angular).
PWA (Progressive Web App): Aplicaciones web que funcionan offline, pueden instalarse y enviar notificaciones push.  
2. Arquitectura de aplicaciones web  
2.1 Cliente-Servidor
Cliente: Navegador del usuario (front-end).
Servidor: Donde se ejecutan procesos y se almacenan datos (back-end).
Comunicación: A través de protocolos como HTTP.  
2.2 Arquitectura de tres capas
Presentación: Interfaz de usuario (HTML, CSS, JS).
Lógica: Procesamiento de datos y reglas de negocio (PHP, Node.js).
Datos: Base de datos y almacenamiento (MySQL, MongoDB).  
2.3 REST y API-first design
REST: Arquitectura para diseñar servicios web que usan HTTP para acceder y manipular datos.
API-first: Primero se diseña la API antes que la interfaz, facilitando el desarrollo en equipos y la integración con otros sistemas.  
3. Lenguajes y tecnologías fundamentales  
HTML: Estructura la información.
CSS: Da estilo y presentación a la web.
JavaScript: Añade interactividad y lógica en el navegador.
PHP: Lenguaje de servidor para crear contenido dinámico.
MySQL: Sistema de gestión de bases de datos relacional.  
4. Control de versiones  
4.1 Git y GitHub
Git: Control de versiones distribuido para gestionar cambios en el código.
GitHub: Plataforma en la nube basada en Git, facilita colaboración y almacenamiento de repositorios.  
4.2 Flujo de trabajo con ramas
Branching: Crear ramas para desarrollar funciones o corregir errores sin afectar la versión principal.
Merge: Unir los cambios de una rama a otra.
Pull Requests: Solicitud para fusionar cambios, permitiendo revisión y colaboración.

# Desarrollar componentes y funcionalidades de una aplicación web  
<img width="228" height="171" alt="image" src="https://github.com/user-attachments/assets/20cc9fd6-d251-4b13-9b26-c981ed915f8a" />  


1. Diseño e implementación del frontend  
a) Maquetación/Wireframe/Mockup  

Actividad: Crear wireframes o mockups en Figma, Adobe XD, o papel.  
Conceptos:  
Diferencia entre wireframe, mockup y prototipo.  
Principios de UX/UI.  
Grid system, responsive design.  
Herramientas sugeridas: Figma, Balsamiq, Adobe XD, Canva.  
b) API  

Actividad: Definir contratos de API (qué datos necesita el frontend del backend).  
Conceptos:  
¿Qué es una API REST?
Métodos HTTP (GET, POST, PUT, DELETE).  
Consumo de API desde el frontend (fetch, axios).  
Herramientas sugeridas: Postman, Swagger, fetch API, Axios.  
2. Diseño e implementación del backend  
a) Servidor  
Actividad: Configurar y levantar un servidor web (ej: Node.js/Express, Django, Flask, etc.).  
Conceptos:  
¿Qué es un servidor web?  
Rutas y controladores.  
Herramientas sugeridas: Node.js/Express, Python/Flask, Django, FastAPI.  
b) Manejo de peticiones y respuestas HTTP  

Actividad: Implementar endpoints que reciban y respondan peticiones.  
Conceptos:  
Status codes HTTP (200, 404, 500, etc).  
Body, headers, params, query.
Herramientas sugeridas: Postman, Insomnia.  
c) Conexión a bases de datos  

Actividad: Conectar el backend a una base de datos (MySQL, PostgreSQL, MongoDB).  
Conceptos:  
Drivers y ORMs.  
Strings de conexión.  
Operaciones básicas (conexión, consulta, inserción).  
3. Bases de datos  
a) Modelado de datos y relaciones  

Actividad: Diseñar el modelo entidad-relación para la aplicación.  
Conceptos:  
Tablas, campos, claves primarias y foráneas.  
Relaciones: uno a uno, uno a muchos, muchos a muchos.  
Herramientas sugeridas: dbdiagram.io, DrawSQL, Lucidchart.  
b) ORM (Object Relational Mapping)  

Actividad: Usar un ORM para interactuar con la base de datos desde el backend.  
Conceptos:  
¿Qué es un ORM?  
Ventajas y desventajas frente a consultas SQL directas.  
Herramientas sugeridas: Sequelize (Node.js), SQLAlchemy (Python), TypeORM (TypeScript), Prisma.  
c) CRUD desde el backend  

Actividad: Implementar operaciones CRUD (Create, Read, Update, Delete) desde el backend.  
Conceptos:  
Rutas RESTful para recursos.  
Manejo de errores.  
4. Seguridad básica en aplicaciones web  
a) Validación de formularios  

Actividad: Validar datos en el frontend y backend.  
Conceptos:  
Validación de tipos, longitudes, formatos.  
Sanitización de entradas.  
Herramientas sugeridas: Yup, Joi, express-validator.  
b) Autenticación y autorización  

Actividad: Implementar autenticación básica (ej: login con usuario/contraseña).  
Conceptos:  
Diferencia entre autenticación y autorización.  
Tokens JWT, sesiones, cookies.  
Rutas protegidas.  
Herramientas sugeridas: JWT, Passport.js, bcrypt, OAuth.  

# Implementar y desplegar una aplicación web funcional  
<img width="293" height="166" alt="image" src="https://github.com/user-attachments/assets/3711b74f-8c96-4697-ac58-978d104e488c" />  


1. Integración de frontend y backend  
a) Interfaz de usuario Frontend  
Elige un framework: React, Angular, Vue.js, o simplemente HTML/CSS/JS.  
Estructura básica: Crea componentes para vistas principales (Home, Login, Dashboard, etc).  
Ejemplo (React):
function App() {  
  return (  
    <div>  
      <h1>Mi Aplicación Web</h1>  
      {/* Otros componentes */}  
    </div>  
  );  
}  

b) Manejo de API  
Usa fetch o axios para consumir APIs.  
Ejemplo:  
// Usando fetch  
fetch('https://mi-backend.com/api/data')  
  .then(res => res.json())  
  .then(data => setData(data));  

c) Proceso de Solicitud y Respuesta de Backend  
Backend: Node.js con Express, Django, Flask, etc.  
Ejemplo (Express):  
const express = require('express');  
const app = express();  
app.get('/api/data', (req, res) => {  
  res.json({ mensaje: '¡Hola desde el backend!' });  
});  
CORS: Asegúrate de permitir peticiones del frontend.  

2. Almacenamiento en Servidor  
a) Tipos de servidores  
Servidor dedicado: Todo el control, más caro.  
Servidor compartido: Más barato, menos control.  
Servidor VPS: Balance entre ambos.

b) Servidores y servicios de hosting  
Heroku: Fácil para apps pequeñas.  
Vercel/Netlify: Ideal para frontend y JAMstack.  
AWS/GCP/Azure: Escalabilidad y control total.  
DigitalOcean: VPS sencillo y económico.  

c) Proveedores de Servicios de Almacenamiento  
Base de datos: MongoDB Atlas, Firebase, PostgreSQL (ElephantSQL), MySQL.  
Almacenamiento de archivos: AWS S3, Google Cloud Storage, Cloudinary.  

3. Optimización y rendimiento  
a) Optimización de recursos  
Imágenes: Usa formatos modernos (WebP), comprime imágenes.  
Scripts: Minifica y combina JS/CSS.  
Lazy loading: Carga imágenes solo cuando se necesiten.

b) Despliegue de aplicaciones web
Frontend:  
Construye y sube los archivos estáticos (npm run build en React).  
Sube a Netlify, Vercel, o tu propio servidor.  
Backend:  
Despliega en Heroku, Render, AWS EC2, etc.  
Usa PM2 para Node.js en VPS.  

c) CI/CD básico  
GitHub Actions: Automatiza pruebas y despliegues.  
Ejemplo (workflow simple para Node.js):  
name: Node.js CI  
on: [push]  
jobs:  
  build:  
    runs-on: ubuntu-latest  
    steps:  
      - uses: actions/checkout@v2  
      - uses: actions/setup-node@v2  
        with:  
          node-version: '16'  
      - run: npm install  
      - run: npm run build  
      - run: npm test  
Puedes agregar pasos para desplegar automáticamente.  

d) Documentación del proyecto  
Crea un archivo README.md:  
Descripción del proyecto.  
Tecnologías usadas.  
Cómo instalar y correr localmente.  
Cómo desplegar.  
Ejemplo de uso/API.  

# Plataforma de Cursos Multi-Idioma

Repositorio central para el proyecto de Desarrollo de Aplicaciones Web en la Nube y Móviles.
**Equipo Líder:** Código Chisme.

## 🛠 Entorno de Desarrollo
- **Backend:** Node.js (v24.x LTS) y Express.
- **Base de Datos:** PostgreSQL.
- **Gestión de Tareas:** Tablero Kanban en GitHub Projects.

## 📂 Estructura del Proyecto
- `/src`: Código fuente (Frontend y Backend).
- `/docs`: Documentación, diccionarios de datos y diagramas.
- `/database`: Scripts de inicialización SQL.
- `/tests`: Pruebas unitarias y de integración.

## 🎯 Asignación de Equipos y Módulos
Cada equipo debe clonar el repositorio y cambiarse a su rama correspondiente antes de trabajar.

* **Equipo 1 (`modulo1/modelo-bd`):** Diseño Conceptual y Lógico (Diagrama ER y diccionario de datos).
* **Equipo 2 (`modulo1/scripts-sql`):** Implementación de la base de datos con scripts SQL (DDL/DML).
* **Equipo 3 (`modulo2/criptografia`):** Motor de inmutabilidad (generación de Hash y sello de tiempo).
* **Equipo 4 (`modulo2/pdf-qr`):** Generación de certificados en PDF con código QR incrustado.
* **Equipo 5 (`modulo3/auth-2fa`):** Autenticación OAuth 2.0 y configuración de Doble Factor (2FA).
* **Equipo 6 (`modulo3/pasarela-pagos`):** Integración de pasarela de pagos simulada.
* **Equipo 7 (`modulo4/diseno-ui`):** Diseño UI/UX, wireframes y prototipos en Figma.
* **Equipo 8 (`modulo4/desarrollo-front`):** Desarrollo del Frontend e integración con las APIs.
* **Equipo 9 (`modulo5/aws-devops`):** Despliegue en servidor AWS y automatización.
* **Equipo 10 (`modulo6/qa-pruebas`):** Pruebas unitarias, de carga y auditoría de seguridad OWASP.

## 📖 Reglas de Trabajo (Git Workflow)

### 1. Nomenclatura de Ramas
Estrictamente prohibido hacer commits directos a las ramas `main` o `profesor`. 

### 2. Convención de Commits
Sus mensajes deben explicar claramente qué hicieron:
- `feat:` Nueva característica (ej. `feat: agrega endpoint de pagos`).
- `fix:` Corrección de error (ej. `fix: resuelve conexión a bd`).
- `docs:` Cambios en documentación (ej. `docs: actualiza diagrama de clases`).
- `test:` Adición de pruebas.
- `refactor:` Mejoras al código sin alterar su funcionamiento.

### 3. Pull Requests (PR) y Revisiones
- Para unir su trabajo a la rama principal, el equipo debe abrir un Pull Request hacia `main`.
- Ningún PR se aprueba automáticamente. Requiere la revisión de calidad y autorización explícita del equipo líder (Código Chisme).
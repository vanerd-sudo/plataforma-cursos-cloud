# Plataforma Global de Cursos

Repositorio central para el proyecto de Desarrollo de Aplicaciones Web en la Nube y Móviles.
**Equipo Líder (Arquitectura y QA):** Código Chisme.

## 🛠 Entorno de Desarrollo
- **Backend:** Node.js (v24.x LTS) y Express.
- **Base de Datos:** PostgreSQL.
- **Gestión de Tareas:** Tablero Kanban en GitHub Projects.

## 📂 Estructura del Proyecto
- `/src`: Código fuente (Frontend, Backend y App Móvil).
- `/docs`: Documentación, diccionarios de datos y diagramas.
- `/database`: Scripts de inicialización SQL.
- `/tests`: Pruebas unitarias, de integración y auditoría de seguridad.

## 🎯 Asignación de Actividades y Módulos
El desarrollo se divide en 12 actividades atómicas. Los equipos responsables de cada actividad serán asignados por el profesor mediante un sistema de ruleta. Cada equipo asignado debe clonar el repositorio y trabajar **exclusivamente** en su rama correspondiente:

* **M1: BD (`modulo1/modelo-bd`):** Diseño conceptual y lógico (Diagrama ER y diccionario de datos).
* **M1: BD (`modulo1/scripts-sql`):** Implementación en PostgreSQL mediante scripts SQL (DDL/DML).
* **M2: Cripto (`modulo2/criptografia`):** Generación de hash SHA-256 y sello de tiempo.
* **M2: Cripto (`modulo2/pdf-qr`):** Generación de certificados en PDF y código QR.
* **M3: Seg (`modulo3/auth-2fa`):** Autenticación OAuth 2.0 y doble factor (2FA).
* **M3: Seg (`modulo3/pasarela-pagos`):** Pasarela de pagos y mitigación de inyección SQL.
* **M4: UI/UX (`modulo4/diseno-ui`):** Diseño UI/UX y prototipos en Figma.
* **M4: Web (`modulo4/desarrollo-front`):** Desarrollo del Frontend Web e integración con APIs.
* **M4: Móvil (`modulo4/desarrollo-movil`):** Desarrollo de la aplicación móvil responsiva.
* **M5: DevOps (`modulo5/aws-devops`):** Infraestructura AWS y automatización CI/CD.
* **M6: Pruebas (`modulo6/pruebas-unitarias`):** Pruebas unitarias y funcionales del sistema.
* **M6: QA (`modulo6/qa-owasp`):** Auditoría de seguridad OWASP y resiliencia.

## 📖 Reglas de Trabajo (Git Workflow)

### 1. Nomenclatura de Ramas
Queda estrictamente prohibido crear ramas con nombres arbitrarios o hacer commits directos a las ramas `main`, `develop` o `profesor`. Todos los equipos deben usar las 12 ramas listadas en la sección anterior.

### 2. Convención de Commits
Sus mensajes deben explicar claramente qué hicieron utilizando los siguientes prefijos:
- `feat:` Nueva característica (ej. `feat: agrega endpoint de pagos`).
- `fix:` Corrección de error (ej. `fix: resuelve conexión a bd`).
- `docs:` Cambios en documentación (ej. `docs: actualiza diagrama de clases`).
- `test:` Adición de pruebas (ej. `test: agrega prueba de auth`).
- `refactor:` Mejoras al código sin alterar su funcionamiento.

### 3. Pull Requests (PR) y Revisiones
- Ningún integrante debe realizar commits directamente en `main` o `develop` (están protegidas por el sistema).
- Cada equipo deberá trabajar exclusivamente en la rama asignada a su actividad.
- Al terminar una actividad, el equipo deberá abrir un **Pull Request** desde su rama de trabajo hacia `develop`.
- Todo Pull Request requiere la **revisión y aprobación (Approve)** de al menos un integrante del equipo líder (Código Chisme) antes del *Merge*.
- Una vez integrados y validados los cambios en `develop`, Código Chisme determinará cuándo están listos para pasar a `main`.
- La rama `main` se reservará para versiones 100% estables y probadas del proyecto.
- La rama `profesor` se utilizará exclusivamente para presentar y revisar avances académicos.

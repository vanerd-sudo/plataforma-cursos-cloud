# Plataforma de Cursos Multi-Idioma

Repositorio central para el proyecto de Desarrollo de Aplicaciones Web en la Nube y Móviles.
**Equipo Líder:** Código Chisme.

## 📂 Estructura del Proyecto
- `/src`: Código fuente (Frontend y Backend).
- `/docs`: Documentación, diccionarios de datos y diagramas.
- `/database`: Scripts de inicialización SQL.
- `/tests`: Pruebas unitarias y de integración.

## 🛠 Entorno de Desarrollo
Este proyecto utiliza **Node.js**. La versión requerida está especificada en el archivo `.nvmrc`.

## 📖 Reglas de Trabajo (Git Workflow)

### 1. Ramas (Branches)
Nadie debe trabajar directamente en `main` o `profesor`. Cada equipo debe trabajar en su rama asignada. 
Formato: `moduloX/nombre-tarea`
*Ejemplo:* `modulo1/modelo-bd`

### 2. Mensajes de Commit
Usaremos Semantic Versioning para entender los cambios:
- `feat:` Nueva característica (ej. `feat: agrega pasarela de pagos`).
- `fix:` Corrección de error (ej. `fix: resuelve error en PDF`).
- `docs:` Cambios en documentación (ej. `docs: actualiza diagrama ER`).
- `test:` Adición de pruebas (ej. `test: agrega prueba unitaria de hash`).
- `refactor:` Mejoras al código (ej. `refactor: optimiza consulta SQL`).

### 3. Pull Requests (PR)
- Todo código debe integrarse a `main` mediante un Pull Request.
- Requiere la revisión y aprobación de al menos 1 integrante de **Código Chisme**.

# 🏛️ Landing Page Política - Campaña Electoral

[![CI Landing Page Politica](https://github.com/juanjosevelasquezgalvis563-gif/devops/actions/workflows/ci.yml/badge.svg)](https://github.com/juanjosevelasquezgalvis563-gif/devops/actions)

##  Descripción
Este proyecto consiste en una Landing Page diseñada para una campaña política. El objetivo principal es captar la atención de los ciudadanos, presentar las propuestas del candidato de manera clara y recolectar datos a través de un formulario de contacto.

##  Documentación Técnica

### Estructura del Proyecto
El proyecto mantiene la siguiente estructura mínima obligatoria validada por el sistema de Integración Continua (CI)[cite: 2]:
* `index.html`: Estructura semántica principal de la Landing Page
* `css/style.css`: Estilos visuales.
* `js/script.js`: Interactividad del sitio.
* `README.md`: Documentación técnica del proyecto.

### Integración Continua (CI)
Se ha implementado un flujo de trabajo automatizado mediante **GitHub Actions** (`.github/workflows/ci.yml`)[cite: 2]. 

#### ¿Qué hace este flujo?
1. Se dispara automáticamente ante cualquier `push` o `pull_request` en la rama `main`[cite: 2].
2. Levanta un entorno virtual de pruebas en la última versión de Ubuntu (`ubuntu-latest`)[cite: 2].
3. Descarga el código actual del repositorio[cite: 2].
4. Verifica de manera estricta que los archivos clave (`index.html`, `css/style.css`, `js/script.js` y `README.md`) existan en las rutas correctas[cite: 2]. Si falta alguno, detiene el despliegue e informa del error[cite: 2].


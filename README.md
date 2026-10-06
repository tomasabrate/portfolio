# Tomas Abrate — Backend & Full Stack Engineering Portfolio

[![Deploy MkDocs to GitHub Pages](https://github.com/tomasabrate/portfolio/actions/workflows/deploy.yml/badge.svg)](https://github.com/tomasabrate/portfolio/actions/workflows/deploy.yml)
[![Sitio de Documentación](https://img.shields.io/badge/Sitio_Web-Material_for_MkDocs-0d9488?logo=materialformkdocs)](https://tomasabrate.github.io/portfolio/)

Estudiante de **5to año de Ingeniería en Sistemas de Información (UTN-FRC)** y Desarrollador Full Stack Jr. enfocado en arquitectura de software, persistencia relacional transaccional, soluciones móviles operativas y pipelines analíticos de datos.

[Ver Curriculum Vitae](./docs/TomasAbrateCV.pdf)

---

### Matriz de Proyectos

| Sistema | Dominio / Industria | Foco Técnico Principal | Stack Persistencia & Backend | Acceso & Código |
| :--- | :--- | :--- | :--- | :--- |
| **Ojo Ciudadano** | GovTech / Emergencias en Tiempo Real | Arquitectura NestJS modular, despacho reactivo con Socket.IO, transacciones `Serializable` y geolocalización | PostgreSQL, Prisma 6, NestJS 11, TypeScript, Socket.IO, Docker | [Caso de Estudio](./docs/ojociudadano-sistema-emergencias.md) · [GitHub](https://github.com/tomasabrate/OjoCuidadano_Tancacha_CBA) |
| **Bites** | Retail / Marketplace de Alimentos | Persistencia transaccional ACID, inventario concurrente, pasarelas de pago y agregaciones SQL | MySQL (`mysql2/promise`), Node.js (Express), Mercado Pago API | [Caso de Estudio](./docs/bites-marketplace.md) · [GitHub](https://github.com/tomasabrate/Bites) |
| **Smart Grid Analytics** | Smart Grids / IoT & Telemetría | Pipeline ETL analítico forense, consultas SQL embebidas en DuckDB, detección de anomalías y cuantiles P95/P99 | DuckDB, Python, Pandas, Matplotlib, Jupyter Notebooks | [Caso de Estudio](./docs/smartgrid-data-analytics.md) · [GitHub](https://github.com/tomasabrate/Pecan_Street_Austin_Smart_Grid) |
| **TS Desarrollos** | B2B Services / Plataforma Web | Arquitectura en capas (Rutas/Servicios/Repositorios), persistencia relacional ORM y containerización cloud | PostgreSQL, Sequelize ORM, Node.js 20, Docker, Oracle Cloud (OCI) | [Caso de Estudio](./docs/ts-desarrollos-web.md) · [GitHub](https://github.com/ts-desarrollos/ts-web) |
| **Recuperación Semántica de Imágenes** | Computer Vision / Information Retrieval (CBIR) | Pipeline multimodal con CLIP, búsqueda vectorial con FAISS y reformulación de consultas negativas con LLM (Phi-3) | PyTorch, CLIP (`ViT-B-32`), FAISS, Phi-3 Mini (4-bit), Python, Pandas | [Caso de Estudio](./docs/recuperacion-imagenes-cbir.md) · [GitHub](https://github.com/tomasabrate/Sistema_Recuperacion_Imagen) |

---

### Competencias de Dominio Aplicadas

- **Backend & Arquitectura de Software:** TypeScript, JavaScript (ES6+), Python, Node.js, NestJS 11 y Express. Arquitectura modular y en capas, diseño de APIs RESTful, DTOs con validación estricta (`class-validator`), WebSockets en tiempo real (**Socket.IO**), Firebase Auth, JWT y control de idempotencia en webhooks.
- **Bases de Datos & Persistencia (SQL & NoSQL):** Modelado relacional (3FN) en **PostgreSQL** y **MySQL**, transacciones ACID y aislamiento `Serializable`. Migraciones reproducibles con **Prisma 6** y Sequelize ORM. Persistencia NoSQL con **Firestore** y almacenamiento de objetos en Cloudflare R2. Motores analíticos columnares (**DuckDB**) e indexación vectorial (**FAISS**).
- **Frontend & Soluciones Móviles:** Desarrollo móvil multiplataforma con **React Native (Expo)** para operarios en campo y ciudadanos. Desarrollo web con **React (18/19), TypeScript, Vite, React Router, TanStack Query y Leaflet**.
- **Inteligencia Artificial & Datos:** Telemetría IoT con detección de nulos semánticos y cuantiles P95/P99. Búsqueda semántica multimodal (CBIR) con **CLIP (ViT-B-32)** y modelos de lenguaje (**Phi-3 Mini**). Especialización en IA (**Digital House**).
- **Metodologías & DevOps:** **Git, GitHub, Jira (Scrum)**, pair programming. Contenerización con Docker / Docker Compose sobre Linux, despliegues en **Oracle Cloud (OCI)**, **Cloudflare Pages/R2** y **Expo EAS Build**.
- **Idiomas:** **Inglés Avanzado** (técnico y conversacional).

---

### Estructura del Repositorio (Patrón Hub & Spoke)

```text
portfolio/
├── README.md                                  # Hub central: Perfil, matriz de proyectos y enlaces directos
├── mkdocs.yml                                 # Configuración del sitio técnico con Material for MkDocs
├── requirements.txt                           # Dependencias para generación de la documentación
├── .github/
│   └── workflows/
│       └── deploy.yml                         # CI/CD: Despliegue automático a GitHub Pages al pushear a main
└── docs/
    ├── TomasAbrateCV.pdf                      # Curriculum Vitae oficial en formato PDF
    ├── index.md                               # Portada del sitio de documentación web
    ├── ojociudadano-sistema-emergencias.md    # Caso de estudio: Plataforma de emergencias (Ojo Ciudadano)
    ├── bites-marketplace.md                   # Caso de estudio: Marketplace transaccional (Bites)
    ├── smartgrid-data-analytics.md            # Caso de estudio: Telemetría residencial IoT (Smart Grid)
    ├── ts-desarrollos-web.md                  # Caso de estudio: Arquitectura en capas y nube (TS Desarrollos)
    ├── recuperacion-imagenes-cbir.md          # Caso de estudio: Búsqueda multimodal CBIR (CLIP + FAISS)
    └── architecture/                          # Directorio para esquemas y diagramas complementarios
```

---

### Canales de Presentación y Despliegue

Este portafolio puede explorarse a través de dos canales:

1. **Repositorio de GitHub (Markdown Nativo):** Navegable directamente desde los enlaces de la tabla anterior. Todos los diagramas de secuencia, entidad-relación y flujo están renderizados nativamente con **Mermaid.js**.
2. **Sitio Web Técnico (Material for MkDocs):** Genera una especificación técnica navegable con buscador de texto completo, temas oscuro/claro y resaltado de sintaxis.

#### Ejecución Local del Sitio de Documentación

```bash
# 1. Instalar dependencias
pip install -r requirements.txt

# 2. Iniciar servidor de desarrollo en vivo
python -m mkdocs serve
```

El sitio estará disponible de inmediato en `http://127.0.0.1:8000`.

#### Despliegue Automatizado a GitHub Pages

El flujo de GitHub Actions configurado en `.github/workflows/deploy.yml` compila automáticamente el sitio ante cada actualización en la rama `main` y lo publica en:

👉 **[tomasabrate.github.io/portfolio](https://tomasabrate.github.io/portfolio/)**

---

### Contacto

* **Curriculum Vitae:** [Descargar TomasAbrateCV.pdf](./docs/TomasAbrateCV.pdf)
* **LinkedIn:** [linkedin.com/in/tomas-abrate](https://www.linkedin.com/in/tomas-abrate)
* **GitHub:** [github.com/tomasabrate](https://github.com/tomasabrate)
* **Correo Electrónico:** [tomaseabrate@gmail.com](mailto:tomaseabrate@gmail.com)
* **Kaggle:** [kaggle.com/tomasabrate](https://www.kaggle.com/tomasabrate)
* **Ubicación:** Córdoba, Argentina

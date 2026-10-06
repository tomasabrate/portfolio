# Tomas Abrate — Portfolio

> **Estudiante de 5to año de Ingeniería en Sistemas de Información (UTN-FRC)** y Desarrollador Full Stack Jr. enfocado en arquitectura de software, persistencia relacional transaccional, soluciones móviles operativas y pipelines analíticos de datos.

<div class="cv-btn-container">
  <a href="./TomasAbrateCV.pdf" target="_blank" class="cv-btn">
    Ver Curriculum Vitae
  </a>
</div>

---

## Matriz de Proyectos

| Sistema | Dominio / Industria | Foco Técnico Principal | Stack Persistencia & Backend | Acceso & Código |
| :--- | :--- | :--- | :--- | :--- |
| **[Ojo Ciudadano](./ojociudadano-sistema-emergencias.md)** | GovTech / Emergencias en Tiempo Real | Arquitectura NestJS modular, despacho reactivo con Socket.IO, transacciones `Serializable`, control de concurrencia y geolocalización | PostgreSQL, Prisma 6, NestJS 11, TypeScript, Socket.IO, Docker, Cloudflare R2 | [Caso de Estudio](./ojociudadano-sistema-emergencias.md) · [GitHub](https://github.com/tomasabrate/OjoCuidadano_Tancacha_CBA) |
| **[Bites](./bites-marketplace.md)** | Retail / Marketplace de Alimentos | Persistencia transaccional ACID, inventario concurrente, integración de pagos (webhooks) y consultas agregadas SQL | MySQL (`mysql2/promise`), Node.js (Express), Mercado Pago API, Cloudinary | [Caso de Estudio](./bites-marketplace.md) · [GitHub](https://github.com/tomasabrate/Bites) |
| **[Smart Grid Analytics](./smartgrid-data-analytics.md)** | Smart Grids / IoT & Telemetría | Pipeline ETL analítico forense, consultas SQL embebidas con DuckDB sin saturar memoria, análisis temporal y métricas P95/P99 | DuckDB, Python, Pandas, Matplotlib, Jupyter Notebooks | [Caso de Estudio](./smartgrid-data-analytics.md) · [GitHub](https://github.com/tomasabrate/Pecan_Street_Austin_Smart_Grid) |
| **[TS Desarrollos](./ts-desarrollos-web.md)** | B2B Services / Plataforma Web | Arquitectura en capas desacopladas (Rutas-Servicios-Repositorios), persistencia ORM, trazabilidad de solicitudes y Docker en cloud | PostgreSQL, Sequelize ORM, Node.js 20, Docker, Oracle Cloud Infrastructure | [Caso de Estudio](./ts-desarrollos-web.md) · [GitHub](https://github.com/ts-desarrollos/ts-web) |
| **[Recuperación Semántica de Imágenes](./recuperacion-imagenes-cbir.md)** | Computer Vision / Information Retrieval (CBIR) | Pipeline multimodal con embeddings CLIP, búsqueda vectorial exacta con FAISS y reformulación de consultas con negación mediante LLM (Phi-3) | PyTorch, CLIP (`ViT-B-32`), FAISS, Phi-3 Mini (4-bit), Python, Pandas | [Caso de Estudio](./recuperacion-imagenes-cbir.md) · [GitHub](https://github.com/tomasabrate/Sistema_Recuperacion_Imagen) |

---

## Competencias de Dominio Aplicadas

### Backend & Arquitectura de Software
- **Lenguajes:** TypeScript, JavaScript (ES6+), Python (con sólida base académica en C# y Java).
- **Entornos y Frameworks:** Node.js, NestJS 11, Express.
- **Diseño de APIs & Integraciones:** Arquitectura en capas y modular (Rutas, Servicios de Dominio, Repositorios), APIs RESTful estructuradas, serialización, DTOs con validación estricta (`class-validator`) e integración de webhooks asíncronos (Mercado Pago).
- **Comunicación en Tiempo Real:** Gateways y WebSockets con **Socket.IO**, gestión de rooms controladas por rol y despacho reactivo de eventos.
- **Seguridad & Autenticación:** Integración de **Firebase Auth**, JWT Bearer tokens, bcrypt y guards de autorización por roles (RBAC).

### Bases de Datos & Persistencia
- **Bases de Datos Relacionales (SQL):** **PostgreSQL** y **MySQL** — modelado entidad-relación (3FN), restricciones de integridad, control transaccional estricto (ACID), niveles de aislamiento `Serializable` y optimización de índices.
- **ORMs y Migraciones:** **Prisma 6** (migraciones versionadas y acceso fuertemente tipado) y **Sequelize ORM**.
- **Persistencia NoSQL e Híbrida:** **Firestore** para catálogos reactivos y sincronización móvil; Cloudflare R2 para almacenamiento de objetos multimedia.
- **Motores Analíticos OLAP & Vectoriales:** Consultas analíticas vectorizadas sobre disco con **DuckDB** para series temporales masivas sin desborde de RAM, e indexación vectorial en memoria con **FAISS** (`IndexFlatIP`).

### Frontend & Soluciones Móviles
- **Desarrollo Móvil Operativo:** **React Native (Expo)** — interfaces móviles para reporte ciudadano, respuesta de operadores de campo y trazabilidad de inventarios logísticos.
- **Desarrollo Web Frontend:** **React (18/19), TypeScript, Vite, React Router, TanStack Query, Axios y Leaflet** (mapas geolocalizados para centros de despacho).

### Inteligencia Artificial & Datos
- **Series Temporales & IoT:** Ingesta y auditoría forense de telemetría de alta frecuencia (15 min), resolución de nulos semánticos vs. caídas de enlace y detección de anomalías con cuantiles percentilares (P95/P99).
- **Recuperación Multimodal (CBIR):** Alineación espacio-vectorial texto-imagen con **CLIP (ViT-B-32)**, re-ranking penalizado y prompting estructurado con modelos de lenguaje pequeños (**Phi-3 Mini 4-bit**). Formación en IA en **Digital House (2025)**.

### Infraestructura, Cloud & DevOps
- **Metodologías Ágiles & Gestión:** **Git, GitHub, Jira (Scrum)**, experiencia en pair programming, diseño colaborativo y refactorización continua.
- **Contenerización & Cloud:** Empaquetado con **Docker** y **Docker Compose** sobre Alpine/Ubuntu, despliegues en **Oracle Cloud Infrastructure (OCI)**, distribución perimetral en **Cloudflare** (Pages, Workers, CDN) y compilaciones móviles con **Expo EAS Build**.
- **Idiomas:** **Inglés Avanzado** (lectura técnica, documentación y comunicación fluida).

---

## Contacto

* **Curriculum Vitae:** [Descargar TomasAbrateCV.pdf](./TomasAbrateCV.pdf)
* **LinkedIn:** [linkedin.com/in/tomas-abrate](https://www.linkedin.com/in/tomas-abrate)
* **GitHub:** [github.com/tomasabrate](https://github.com/tomasabrate)
* **Correo Electrónico:** [tomaseabrate@gmail.com](mailto:tomaseabrate@gmail.com)
* **Kaggle:** [kaggle.com/tomasabrate](https://www.kaggle.com/tomasabrate)
* **Ubicación:** Córdoba, Argentina

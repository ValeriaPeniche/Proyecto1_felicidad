# 🌍 El Pulso de la Felicidad Mundial (2015-2024)

## 📊 Descripción del Proyecto
[cite_start]Este repositorio alberga la **Fase 3: Implementación** del Dashboard interactivo "El Pulso de la Felicidad Mundial"[cite: 6, 18, 84]. [cite_start]El objetivo principal fue transformar el diseño conceptual en una herramienta funcional que permite visualizar y analizar los datos del **World Happiness Report (2015-2024)**[cite: 21].

[cite_start]El proyecto opera bajo una arquitectura **Cliente-Servidor** [cite: 78][cite_start]: el frontend es una aplicación de página única que consume datos filtrados por año y región a través de una API REST que gestiona la conexión con la base de datos[cite: 67, 68].

## 💻 Stack Tecnológico
| Capa | Herramientas Principales | Uso Clave |
| :--- | :--- | :--- |
| **Frontend** | React, Vite, CSS Modules | [cite_start]Interfaz de usuario y componentes reutilizables (KPIs, Gráficos) [cite: 74, 79] |
| **Visualización** | Recharts, React-Leaflet | Gráficos de Dispersión y Líneas (Recharts); [cite_start]Mapa Coroplético geográficamente correcto (React-Leaflet) [cite: 74, 232, 237] |
| **Backend** | Node.js/Express, Axios | [cite_start]API REST para manejar consultas asíncronas y filtradas [cite: 74, 80] |
| **Datos** | MySQL, GeoJSON | [cite_start]Almacenamiento persistente de datos del informe de felicidad y geometrías de países para el mapa [cite: 81, 255] |

## ✨ Visualizaciones y Características Clave
[cite_start]El dashboard respeta la jerarquía de la información al presentar[cite: 306]:
* [cite_start]**Filtros Globales:** Permiten seleccionar Año y Región[cite: 198].
* [cite_start]**KPIs Principales:** Muestran el Índice de Felicidad, PIB per cápita, Apoyo Social, Esperanza de Vida y Libertad[cite: 221, 222, 223, 224, 225, 226].
* [cite_start]**Mapa Coroplético:** Visualiza la distribución geográfica de la felicidad por país[cite: 229, 231].
* [cite_start]**Diagrama de Dispersión:** Identifica la correlación entre el Logaritmo del PIB per cápita y el Índice de Felicidad[cite: 235, 236].
* [cite_start]**Análisis Detallado:** Incluye la Evolución temporal de la Esperanza de Vida por región y comparativas de los Top/Bottom 10 países en Apoyo Social[cite: 239, 245].

---

## 🔗 Dashboard en vivo

[Dashboard El Pulso de la Felicidad Mundial](https://proyecto1felicidad.vercel.app/)
```

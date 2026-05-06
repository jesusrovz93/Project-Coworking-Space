

# Coworking Space Landing Page

## Descripción

Proyecto frontend de una landing page moderna para un espacio de coworking llamado **Cozy Corner**. El objetivo principal es presentar un entorno de trabajo atractivo, profesional y visualmente limpio para promocionar espacios colaborativos.

El proyecto fue construido utilizando tecnologías base del desarrollo web:

* HTML5
* CSS3
* JavaScript
* Webpack

La interfaz está enfocada en:

* Diseño moderno y minimalista
* Distribución responsive
* Buena jerarquía visual
* Experiencia de usuario clara y elegante

---

# Vista General

La landing page incluye:

* Header de navegación
* Hero section principal
* Beneficios del coworking
* Estadísticas rápidas
* Assets gráficos personalizados
* Integración de Google Fonts

---

# Tecnologías Utilizadas

| Tecnología   | Descripción                       |
| ------------ | --------------------------------- |
| HTML5        | Estructura semántica del proyecto |
| CSS3         | Estilos y diseño visual           |
| JavaScript   | Scripts y comportamiento dinámico |
| Webpack      | Bundling y entorno de desarrollo  |
| Google Fonts | Tipografías Playfair y Poppins    |

---

# Estructura del Proyecto

```bash
coworking-space/
│
├── css/
│   └── style.css
│
├── img/
│   ├── cozy_corner_logo.svg
│   ├── check.png
│   ├── location.svg
│   ├── room.svg
│   └── wifi.svg
│
├── js/
│   └── app.js
│
├── index.html
├── package.json
├── webpack.config.dev.js
├── webpack.config.prod.js
└── webpack.common.js
```

---

# Instalación

## 1. Clonar el repositorio

```bash
git clone https://github.com/tu-usuario/coworking-space.git
```

---

## 2. Entrar al proyecto

```bash
cd coworking-space
```

---

## 3. Instalar dependencias

```bash
npm install
```

---

# Ejecutar el Proyecto

## Modo desarrollo

```bash
npm start
```

Esto iniciará el servidor de desarrollo usando Webpack Dev Server.

---

## Build de producción

```bash
npm run build
```

Webpack generará la versión optimizada del proyecto.

---

# Características del Proyecto

## Diseño Responsive

La interfaz está diseñada para adaptarse a:

* Desktop
* Tablet
* Mobile

---

## Organización Visual

El proyecto utiliza:

* Layout limpio
* Espaciados consistentes
* Jerarquía tipográfica clara
* Componentes reutilizables

---

## Optimización

Webpack se utiliza para:

* Compilar assets
* Optimizar archivos
* Servir el entorno de desarrollo
* Preparar builds de producción

---

# Dependencias Principales

```json
{
  "webpack": "^5.101.3",
  "webpack-cli": "^6.0.1",
  "webpack-dev-server": "^5.2.2",
  "webpack-merge": "^6.0.1",
  "copy-webpack-plugin": "^13.0.1",
  "html-webpack-plugin": "^5.6.4"
}
```

---

# Mejoras Futuras

Posibles mejoras para escalar el proyecto:

* Dark Mode
* Animaciones con GSAP
* Integración con React
* Sistema de reservas
* Backend con Node.js
* Autenticación de usuarios
* Dashboard administrativo
* Integración con Firebase

---

# Autor

Desarrollado por Jesús Restrepo.

---

# Licencia

Este proyecto está bajo licencia MIT.

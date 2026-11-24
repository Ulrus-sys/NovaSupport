# NovaSupport | Soluciones Tecnológicas

**NovaSupport** es un proyecto web orientado a presentar servicios de soporte informático, soluciones digitales e innovación tecnológica para pequeñas y medianas empresas (PYMES).

El sitio busca transmitir una imagen moderna y profesional, destacando cómo la tecnología puede contribuir a optimizar procesos, mejorar la productividad y fortalecer el crecimiento empresarial.

🌐 Sitio web publicado: https://novasupport-9jv.pages.dev/
Repositorio: [NovaSupport en GitHub](https://github.com/Ulrus-sys/NovaSupport)

## 📌 Secciones del sitio

El proyecto cuenta con tres páginas principales:

- **Inicio:** presentación de NovaSupport, servicios tecnológicos, proyectos y contenido audiovisual relacionado con la transformación digital.
- **Nosotros:** información institucional, historia, misión, visión y valores.
- **Tecnología:** contenido informativo sobre transformación digital, ciberseguridad y automatización.

## 🛠️ Tecnologías utilizadas

- **Astro:** framework utilizado para el desarrollo del sitio web.
- **HTML5:** estructura semántica del contenido.
- **CSS3:** diseño visual, estilos y adaptación responsive.
- **JavaScript:** entorno de ejecución del proyecto mediante Node.js.
- **Poppins y Roboto:** tipografías utilizadas para la identidad visual.
- **Astro Image:** optimización y procesamiento de imágenes.
- **Git y GitHub:** control de versiones y alojamiento del repositorio.

## 🎨 Características principales

- Diseño moderno con identidad visual basada en tonos azul oscuro y verde.
- Diseño responsive para dispositivos móviles, tablets y computadores.
- Componentes reutilizables para mantener una estructura organizada.
- Layout principal compartido entre las páginas.
- Implementación de CSS Grid y Flexbox.
- Imágenes optimizadas mediante Astro.
- Contenido audiovisual integrado mediante un reproductor de YouTube.
- Navegación entre páginas y secciones del sitio.

## 📂 Estructura del proyecto

```text
NovaSupport/
├── public/
├── src/
│   ├── assets/
│   │   └── images/
│   ├── components/
│   │   ├── About.astro
│   │   ├── Contact.astro
│   │   ├── Header.astro
│   │   ├── Projects.astro
│   │   ├── Services.astro
│   │   └── Video.astro
│   ├── layouts/
│   │   └── MainLayout.astro
│   ├── pages/
│   │   ├── index.astro
│   │   ├── nosotros.astro
│   │   └── tecnologia.astro
│   └── styles/
│       └── global.css
├── .gitignore
├── astro.config.mjs
├── package.json
└── README.md
```

## 💻 Instalación y ejecución local

Para ejecutar el proyecto en un entorno local, se requiere tener instalado Node.js y Git.

**1. Clonar el repositorio**

```bash
git clone https://github.com/Ulrus-sys/NovaSupport.git
```

**2. Ingresar a la carpeta del proyecto**

```bash
cd NovaSupport
```

**3. Instalar las dependencias**

```bash
npm install
```

**4. Iniciar el servidor de desarrollo**

```bash
npm run dev
```

El sitio estará disponible en:

`http://localhost:4321/`

## 🏗️ Compilación para producción

Para generar la versión optimizada del sitio:

```bash
npm run build
```

Los archivos generados se almacenan en la carpeta `dist/`.

Para revisar localmente la versión de producción:

```bash
npm run preview
```

## 👨‍💻 Autoría

**Proyecto académico: NovaSupport**

Desarrollado como parte de la asignatura de Interfaz de Usuario, Ingeniería en Informática.

---

*NovaSupport — Tecnología, innovación y soluciones para impulsar tu empresa.*

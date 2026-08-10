# Portafolio Personal — HTML5 y CSS Flexbox

## 📌 Descripción

Portafolio personal desarrollado como parte de la asignatura **Ingeniería Web I**.

El proyecto aplica los conceptos de **HTML5 semántico**, **CSS Flexbox**, 
**diseño responsive** y **accesibilidad web**, siguiendo los requerimientos 
establecidos en la Guía de Laboratorio 1.

El portafolio presenta información personal, habilidades, proyectos y un 
formulario de contacto accesible.

---

## 🎯 Objetivos

- Utilizar correctamente elementos semánticos de HTML5.
- Implementar un diseño adaptable a diferentes tamaños de pantalla.
- Aplicar CSS Flexbox para organizar los contenidos.
- Implementar un formulario de contacto accesible.
- Mantener una estructura organizada del proyecto.
- Verificar la estructura mediante herramientas de validación y accesibilidad.

---

## 🛠️ Tecnologías utilizadas

- **HTML5**
- **CSS3**
- **CSS Flexbox**
- **Media Queries**

No se utilizan frameworks externos como Bootstrap o Tailwind CSS.

---

## 🧩 Estructura semántica

El proyecto utiliza los principales elementos semánticos de HTML5:

- `<header>` — Cabecera del portafolio.
- `<nav>` — Navegación principal.
- `<main>` — Contenido principal.
- `<section>` — Secciones de contenido.
- `<article>` — Contenido independiente dentro de las secciones.
- `<footer>` — Pie de página.

También se utiliza `aria-label` en la navegación para facilitar su 
identificación mediante tecnologías de asistencia.

---

## 📱 Diseño Responsive

El diseño utiliza CSS Flexbox y se adapta a diferentes tamaños de pantalla 
mediante tres breakpoints:

### 📱 Móvil
Pantallas de hasta **600px**.

El contenido se reorganiza principalmente en una columna.

### 📲 Tableta
Pantallas entre **601px y 1024px**.

Las habilidades y proyectos se organizan utilizando una distribución 
adaptada al tamaño intermedio.

### 🖥️ Escritorio
Pantallas de **1025px o más**.

Los elementos pueden distribuirse horizontalmente aprovechando el espacio 
disponible.

---

## ♿ Accesibilidad

El formulario de contacto utiliza etiquetas `<label>` asociadas correctamente 
con los campos mediante los atributos `for` e `id`.

También se utilizan textos alternativos (`alt`) para las imágenes y elementos 
semánticos de HTML5 para facilitar la navegación mediante tecnologías de 
asistencia.

---

## 📂 Estructura del proyecto

```text
portafolio-html5-flexbox/
│
├── css/
│   └── style.css
│
├── img/
│   ├── Perfil1.jpg
│   ├── Captura1.png
│   ├── Captura2.png
│   └── Captura3.png
│
├── index.html
└── README.md

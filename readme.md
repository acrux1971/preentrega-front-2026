# 📷 InFocus Fotografía

## 👩‍💻 Autora del proyecto: Natalia Castagnetto


## 📌 Descripción del proyecto

**InFocus Fotografía** es un sitio web desarrollado para presentar y promocionar fotografías de autor destinadas a la decoración de espacios.

El proyecto busca combinar una estética moderna y minimalista con una navegación sencilla, permitiendo al usuario conocer la propuesta, visualizar fotografías, consultar servicios, leer reseñas y ponerse en contacto.

El diseño utiliza principalmente los colores **negro, blanco y amarillo**, buscando generar una identidad visual relacionada con la fotografía y la creatividad.


## 🛠️ Tecnologías utilizadas

El proyecto fue desarrollado utilizando:

- **HTML5**
- **CSS3**
- **Flexbox**
- **CSS Grid**
- **Media Queries**
- **Font Awesome**
- **Google Fonts**
- **Google Maps**
- **Formspree**


## 🌐 Estructura del sitio

El sitio está organizado en diferentes secciones:

### 🏠 Inicio

La sección principal presenta el nombre de **InFocus Fotografía**, una frase de bienvenida y la barra de menú

---

### 👤 Sobre nosotros

Esta sección presenta información sobre el proyecto, su propuesta y la idea detrás de las fotografías de autor.

---

### 🎨 Servicios

La sección de servicios utiliza una combinación de imágenes y textos para presentar las diferentes propuestas de InFocus Fotografía.

Se utilizan bloques combinados de **texto e imágenes** para mejorar la presentación visual.

---

### 🖼️ Productos

La sección de productos presenta diferentes fotografías mediante tarjetas.

Cada tarjeta incluye:

- Imagen.
- Autor.
- Frase del autor.
- Precio.
- Botón de acción.

Las tarjetas están organizadas utilizando **Flexbox** y se adaptan automáticamente al tamaño de la pantalla.

---

## ⭐ Reseñas

El sitio cuenta con una sección de **reseñas de clientes**, diseñada para mostrar diferentes opiniones sobre los productos y servicios de InFocus Fotografía.

Las reseñas se presentan mediante tarjetas independientes, permitiendo visualizar de forma clara:

- Nombre del cliente.
- Valoración mediante estrellas.
- Opinión o comentario.
- Separación visual entre las diferentes reseñas.

### 📐 Distribución de las reseñas

La sección utiliza **CSS Grid** para organizar las opiniones de manera responsive.

---

### 📩 Formulario de contacto

El sitio web incluye una sección de Formulario de Contacto que permite a los visitantes enviar consultas de manera sencilla y rápida.

El formulario está diseñado de manera responsive, adaptándose correctamente a computadoras, tablets y dispositivos móviles.

El formulario contiene:

- Nombre: permite ingresar el nombre del visitante.
- Correo electrónico: permite ingresar una dirección de email válida.
- Mensaje: permite escribir la consulta o comentario.
- Botón Enviar: permite enviar la información ingresada.

Características
- Utiliza etiquetas <label> asociadas a cada campo.
- Utiliza required para validar que los campos obligatorios no estén vacíos.
- El campo de correo utiliza type="email" para validar el formato del email.
- El botón se encuentra deshabilitado hasta que los datos sean válidos.
- El formulario utiliza Formspree para gestionar el envío de los mensajes.

---

### 📍 Mapa y ubicación

El sitio web incorpora un mapa interactivo de Google Maps dentro de la sección de contacto. Su objetivo es facilitar a los visitantes la ubicación del espacio físico de InFocus Fotografía.

Características
- Integración de Google Maps.
- El mapa se adapta al ancho disponible.
- Se encuentra integrado junto al formulario y los datos de contacto.

---

### 📱 Diseño Responsive

El sitio fue desarrollado para adaptarse a diferentes tamaños de pantalla.

Se utilizaron Media Queries para modificar la distribución del contenido.

💻 Computadoras

En pantallas grandes se utilizan:
Menú horizontal.
Tarjetas distribuidas en varias columnas.
Reseñas en cuatro columnas.
Formulario y mapa en dos columnas.

📱 Tablets

La distribución se adapta reduciendo la cantidad de columnas.

Las reseñas pasan a dos columnas

📱 Celulares

En pantallas pequeñas:

El menú pasa a disposición vertical.
Las tarjetas se acomodan en una columna.
Las reseñas pasan a una columna.
Formulario y mapa se muestran uno debajo del otro.
Se reducen algunos tamaños de texto y espacios.

---

## 📁 Estructura de carpetas

El proyecto está organizado en diferentes carpetas para mantener separados los archivos HTML, CSS e imágenes.

```text
InFocus-Fotografia/
│
├── index.html
├── README.md
│
├── css/
│   └── style.css
│
└── img/
    ├── logo.png
    │── productos1.jpg
    │── productos2.jpg
    │── productos3.jpg
    │── productos4.jpg
    │── productos5.jpg
    │── productos6.jpg
    │── servicios1.png
    │── servicios2.png
 

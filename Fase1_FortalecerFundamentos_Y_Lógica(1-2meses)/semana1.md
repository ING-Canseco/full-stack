¡Excelente! Vamos a comenzar con mucha energía. Te presento el **Plan de la Semana 1: Fundamentos de HTML**.

## 📅 **SEMANA 1: HTML - LAS BASES DE LA WEB**

### **Objetivo de la semana:**

Aprender a estructurar contenido web usando HTML y crear tu primera página web semántica.

---

### **DÍA 1: PRIMEROS PASOS CON HTML**

#### **Conceptos Teóricos:**

- **¿Qué es HTML?** Lenguaje de Marcado de Hipertexto (no es un lenguaje de programación)
- **Elementos y Etiquetas:** `<etiqueta>contenido</etiqueta>`
- **Estructura básica de un documento HTML**

#### **Práctica - Tu Primera Página:**

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Primera Página Web</title>
</head>
<body>
    <h1>¡Bienvenido a mi Camino Full-Stack!</h1>
    <p>Esta es mi primera página web creada desde cero.</p>
</body>
</html>
```

#### **Ejercicio del Día 1:**

1. Crea una carpeta llam `semana1-html`<!DOCTYPE html>`
   <html lang="es">
   <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>Mi Primera Página Web</title>
   </head>
   <body>
       <h1>¡Bienvenido a mi Camino Full-Stack!</h1>
       <p>Esta es mi primera página web creada desde cero.</p>
   </body>
   </html>`
2. Dentro, crea un archivo `dia1.html`
3. Copia el código anterior y modifica:
   - El título de la página
   - El texto del h1
   - Añade un segundo párrafo presentándote

---

### **DÍA 2: ESTRUCTURA SEMÁNTICA Y ENCABEZADOS**

#### **Conceptos Teóricos:**

- **Encabezados:** `<h1>` a `<h6>` (importancia jerárquica)
- **Elementos semánticos HTML5:**
  - `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`

#### **Práctica - Mejorando la Estructura:**

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Mi Portafolio - Estructura Semántica</title>
</head>
<body>
    <header>
        <h1>Mi Nombre</h1>
        <p>Aspirante a Desarrollador Full-Stack</p>
    </header>
  
    <nav>
        <a href="#sobre-mi">Sobre Mí</a> |
        <a href="#proyectos">Proyectos</a> |
        <a href="#contacto">Contacto</a>
    </nav>
  
    <main>
        <section id="sobre-mi">
            <h2>Sobre Mí</h2>
            <p>Texto sobre ti...</p>
        </section>
    </main>
  
    <footer>
        <p>© 2024 Mi Portafolio</p>
    </footer>
</body>
</html>
```

#### **Ejercicio del Día 2:**

Crea `dia2.html` y desarrolla la estructura semántica de tu portafolio personal.

---

### **DÍA 3: LISTAS Y ENLACES**

#### **Conceptos Teóricos:**

- **Listas ordenadas:** `<ol>`, `<li>`
- **Listas desordenadas:** `<ul>`, `<li>`
- **Enlaces:** `<a href="url">Texto</a>`
- **Rutas absolutas vs relativas**

#### **Práctica - Añadiendo Contenido:**

```html
<section id="habilidades">
    <h2>Habilidades que estoy aprendiendo</h2>
    <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
        <li>React</li>
        <li>Node.js</li>
    </ul>
</section>

<section id="proyectos">
    <h2>Mis Proyectos</h2>
    <ol>
        <li>Portafolio Personal</li>
        <li>Página de Recetas</li>
        <li>Blog de Viajes</li>
    </ol>
</section>

<nav>
    <a href="https://github.com/tuusuario" target="_blank">Mi GitHub</a> |
    <a href="dia1.html">Ver mi primer ejercicio</a>
</nav>
```

#### **Ejercicio del Día 3:**

En tu archivo `dia2.html`, añade:

- Una lista de tus hobbies
- Una lista ordenada de tus metas de aprendizaje
- Enlaces a tus redes sociales (o páginas que te gusten)

---

### **DÍA 4: IMÁGENES Y MULTIMEDIA**

#### **Conceptos Teóricos:**

- **Imágenes:** `<img src="ruta" alt="texto alternativo">`
- **Atributos importantes:** `src`, `alt`, `width`, `height`
- **Formatos de imagen:** JPG, PNG, SVG, WebP

#### **Práctica - Haciendo tu Página Visual:**

```html
<section id="galeria">
    <h2>Galería de Proyectos</h2>
  
    <img src="https://via.placeholder.com/300x200" 
         alt="Placeholder de proyecto 1"
         width="300"
         height="200">
  
    <img src="./images/mi-foto.jpg" 
         alt="Mi foto de perfil"
         width="200"
         height="200">
</section>

<!-- Ejemplo con figura y descripción -->
<figure>
    <img src="proyecto.jpg" alt="Captura de mi proyecto">
    <figcaption>Mi primer proyecto en HTML</figcaption>
</figure>
```

#### **Ejercicio del Día 4:**

1. Crea una carpeta `images` en tu proyecto
2. Añade al menos 2 imágenes a tu portafolio
3. Usa imágenes de placeholder si no tienes propias
4. Practica con diferentes tamaños y el atributo `alt`

---

### **DÍA 5: FORMULARIOS BÁSICOS**

#### **Conceptos Teóricos:**

- **Formulario:** `<form>`
- **Inputs comunes:** `text`, `email`, `password`, `textarea`
- **Botones:** `<button type="submit">` y `<input type="submit">`

#### **Práctica - Formulario de Contacto:**

```html
<section id="contacto">
    <h2>Contáctame</h2>
  
    <form>
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre" name="nombre" required>
        <br><br>
      
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <br><br>
      
        <label for="mensaje">Mensaje:</label>
        <textarea id="mensaje" name="mensaje" rows="4" cols="50"></textarea>
        <br><br>
      
        <button type="submit">Enviar Mensaje</button>
    </form>
</section>
```

#### **Ejercicio del Día 5:**

Crea un formulario de contacto en tu portafolio con:

- Campo para nombre
- Campo para email
- Área para mensaje
- Botón de envío

---

### **DÍA 6: TABLAS Y ELEMENTOS ESPECIALES**

#### **Conceptos Teóricos:**

- **Tablas:** `<table>`, `<tr>`, `<td>`, `<th>`
- **Elementos de texto:** `<strong>`, `<em>`, `<mark>`, `<blockquote>`

#### **Práctica - Tabla de Horario de Estudio:**

```html
<section id="horario">
    <h2>Mi Horario de Estudio</h2>
  
    <table border="1">
        <tr>
            <th>Día</th>
            <th>Tema</th>
            <th>Horas</th>
        </tr>
        <tr>
            <td>Lunes</td>
            <td>HTML Semántico</td>
            <td>2 horas</td>
        </tr>
        <tr>
            <td>Martes</td>
            <td>Formularios HTML</td>
            <td>2 horas</td>
        </tr>
    </table>
</section>

<!-- Elementos de texto especiales -->
<p>Estoy <strong>muy emocionado</strong> por aprender desarrollo web.</p>
<p>Recuerda: <em>La práctica hace al maestro</em>.</p>
<blockquote>El único modo de hacer un gran trabajo es amar lo que haces. - Steve Jobs</blockquote>
```

#### **Ejercicio del Día 6:**

Crea una tabla con tu horario semanal de estudio y usa al menos 3 elementos de texto especiales.

---

### **DÍA 7: PROYECTO INTEGRADOR SEMANAL**

#### **🎯 Proyecto: "Mi Primer Portafolio HTML"**

Crea un archivo `proyecto-semana1.html` que incluya:

**Requisitos Mínimos:**

- [X] Estructura semántica completa (header, nav, main, footer)
- [X] Al menos 3 secciones diferentes
- [X] Una lista de habilidades
- [X] Al menos 2 imágenes
- [X] Un formulario de contacto
- [X] Una tabla (horario, experiencia, etc.)
- [X] Enlaces internos y externos
- [X] Elementos de texto especiales

**Ejemplo de Estructura Final:**

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Mi Portafolio - Semana 1</title>
</head>
<body>
    <header>...</header>
    <nav>...</nav>
    <main>
        <section id="inicio">...</section>
        <section id="sobre-mi">...</section>
        <section id="proyectos">...</section>
        <section id="contacto">...</section>
    </main>
    <footer>...</footer>
</body>
</html>
```

---

### **📋 CHECKLIST DE LA SEMANA 1**

Al final de esta semana deberías poder:

- [ ] Crear la estructura básica de un documento HTML
- [ ] Usar elementos semánticos correctamente
- [ ] Crear listas ordenadas y desordenadas
- [ ] Insertar imágenes y enlaces
- [ ] Construir formularios básicos
- [ ] Crear tablas simples
- [ ] Entender la diferencia entre elementos en bloque y en línea

### **💡 CONSEJOS PARA ESTA SEMANA:**

1. **Practica todos los días** aunque sea 1 hora
2. **No copies y pegues** - escribe todo el código manualmente
3. **Experimenta** - cambia valores, prueba cosas diferentes
4. **Usa las herramientas de desarrollador** del navegador (F12)
5. **Valida tu HTML** en [validator.w3.org](https://validator.w3.org/)

---

**¿Listo para comenzar con el Día 1? ¿Tienes alguna pregunta antes de empezar con el primer ejercicio?**

¡Vamos a crear tu primera página web! 🚀

# 🚀 Práctica de Git y GitHub

¡Bienvenido/a a este proyecto web súper sencillo y moderno! Este sitio web estático fue creado específicamente para servirte de lienzo en tu aprendizaje de **Git y GitHub**.

El proyecto consta de una sola tarjeta con diseño moderno (efecto de vidrio/glassmorphism), estilo responsivo y es muy ligero.

---

## 📂 Contenido del Proyecto

* **`index.html`**: Contiene la estructura y la lógica sencilla del botón interactivo.
* **`styles.css`**: Contiene los estilos visuales, colores y animaciones en formato CSS moderno con variables personalizables.

---

## 🛠️ Guía de Práctica de Git (Paso a Paso)

Sigue estos pasos para subir este proyecto a tu propio GitHub y hacer tus primeros cambios (commits).

### Paso 1: Inicializa tu repositorio local
Abre la terminal en la carpeta de este proyecto y escribe:
```bash
git init
```

### Paso 2: Agrega y confirma los archivos iniciales
Prepara los archivos para tu primer "commit" (foto de tu código):
```bash
git add .
git commit -m "feat: commit inicial del proyecto Practica Git"
```

### Paso 3: Crea un repositorio en GitHub
1. Ve a tu cuenta de [GitHub](https://github.com/) y crea un repositorio nuevo llamado `practica-git`.
2. Déjalo **vacío** (no agregues README ni archivo .gitignore desde la web).
3. Copia el enlace HTTPS o SSH de tu repositorio.

### Paso 4: Conecta tu Git local con GitHub y sube el código
Reemplaza `TU_USUARIO` con tu nombre de usuario de GitHub:
```bash
# Cambia el nombre de la rama por defecto a 'main'
git branch -M main

# Conecta tu repositorio local con el remoto en GitHub
git remote add origin https://github.com/TU_USUARIO/practica-git.git

# Sube el código
git push -u origin main
```

---

## 🎯 Ejercicios de Práctica Propuestos

¡Una vez subido, puedes practicar haciendo modificaciones y enviándolas a GitHub!

### Ejercicio A: Tu primer cambio (Simple Commit)
1. Abre `index.html`.
2. Busca la línea que dice: `<p class="author-tag">💡 Modifica esta línea para agregar tu nombre como autor en un commit</p>`.
3. Cambia ese texto por: `Modificado con ❤️ por [Tu Nombre]`.
4. Guarda el archivo y en tu terminal ejecuta:
   ```bash
   git add index.html
   git commit -m "style: agregar mi nombre como autor"
   git push
   ```

### Ejercicio B: Cambiar el diseño (Práctica de ramas / Branches)
Las ramas te permiten experimentar sin dañar el código principal:
1. Crea una nueva rama para tus cambios visuales:
   ```bash
   git checkout -b cambiar-color
   ```
2. Abre `styles.css`.
3. Modifica la variable `--bg-gradient-start` y `--bg-gradient-end` con tus colores favoritos (puedes usar HSL o Hexadecimal).
4. Guarda el archivo y sube tu rama a GitHub:
   ```bash
   git add styles.css
   git commit -m "style: cambiar colores de fondo del sitio"
   git push origin cambiar-color
   ```
5. Ve a tu repositorio en GitHub y verás un botón que dice **"Compare & pull request"**. ¡Haz clic allí para crear un Pull Request y fusionar tus cambios en la rama principal `main`!

---

¡Disfruta aprendiendo Git! El control de versiones es el superpoder de los desarrolladores. 💻✨

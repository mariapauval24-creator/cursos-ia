# Cursos de IA con Paula Valdivia

Landing page estática (HTML + CSS) con estética rosa y beige, lista para publicarse con **GitHub Pages**.

## Estructura
```
index.html
css/styles.css
assets/favicon.svg
.nojekyll
README.md
```

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub (por ejemplo `ia-paula-valdivia`).
2. Sube todos los archivos de esta carpeta a la raíz del repositorio.
3. Ve a **Settings → Pages**. En *Build and deployment* elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
4. Guarda. En uno o dos minutos tu página estará en `https://TU-USUARIO.github.io/ia-paula-valdivia/`.

## Conectar Stripe
1. En el panel de Stripe crea un producto de pago único y otro de suscripción mensual.
2. Para cada uno crea un **Payment Link**.
3. En `index.html` reemplaza `https://buy.stripe.com/REEMPLAZA_CURSO` y `https://buy.stripe.com/REEMPLAZA_COMUNIDAD` por tus enlaces.

Nunca publiques claves secretas de Stripe (`sk_...`) en el repositorio. Los Payment Links no las necesitan.

## Personalizar
- Colores: variables al inicio de `css/styles.css`.
- Precios, módulos y textos: `index.html`.

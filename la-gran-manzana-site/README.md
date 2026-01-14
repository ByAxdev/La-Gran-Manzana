# La Gran Manzana - Centro Comercial

Sitio web oficial del Centro Comercial La Gran Manzana, ubicado en el norte de Guayaquil.

## 🚀 Cómo publicar en GitHub Pages (GRATIS)

### Paso 1: Crear cuenta en GitHub
1. Ve a [github.com](https://github.com)
2. Haz clic en "Sign Up" y crea tu cuenta gratuita
3. Verifica tu email

### Paso 2: Crear un nuevo repositorio
1. Una vez logueado, haz clic en el botón verde "New" o el ícono "+"
2. Nombre del repositorio: `lagranmanzana` (sin espacios)
3. Selecciona "Public"
4. NO marques "Add a README file" (ya tenemos uno)
5. Haz clic en "Create repository"

### Paso 3: Subir los archivos
Hay dos formas de hacerlo:

#### Opción A: Desde la interfaz web (Más fácil)
1. En la página de tu repositorio nuevo, haz clic en "uploading an existing file"
2. Arrastra TODA la carpeta del proyecto (o selecciona todos los archivos)
3. Asegúrate de que se mantenga la estructura de carpetas:
   ```
   lagranmanzana/
   ├── index.html
   ├── README.md
   ├── css/
   │   └── styles.css
   ├── js/
   │   └── main.js
   └── images/
       ├── hero-background.jpg
       └── logo.jpg
   ```
4. Escribe un mensaje de commit: "Primer commit - sitio web La Gran Manzana"
5. Haz clic en "Commit changes"

#### Opción B: Usando Git (Para usuarios avanzados)
```bash
git init
git add .
git commit -m "Primer commit - sitio web La Gran Manzana"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/lagranmanzana.git
git push -u origin main
```

### Paso 4: Activar GitHub Pages
1. Ve a tu repositorio en GitHub
2. Haz clic en "Settings" (Configuración)
3. En el menú lateral izquierdo, busca y haz clic en "Pages"
4. En "Source", selecciona:
   - Branch: `main`
   - Folder: `/ (root)`
5. Haz clic en "Save"
6. ¡Espera 2-3 minutos! GitHub construirá tu sitio

### Paso 5: Ver tu sitio en vivo
Tu sitio estará disponible en:
```
https://TU-USUARIO.github.io/lagranmanzana/
```

Por ejemplo, si tu usuario es "juanperez", tu sitio será:
```
https://juanperez.github.io/lagranmanzana/
```

## 🎨 Características del sitio

- ✅ Diseño responsive (se adapta a móviles y tablets)
- ✅ Colores oficiales de La Gran Manzana
- ✅ Secciones: Inicio, Ventajas, Locales, Ubicación, Contacto
- ✅ Foto aérea como fondo del hero
- ✅ Animaciones suaves
- ✅ 100% gratuito en GitHub Pages

## 📝 Cómo actualizar el sitio

### Cambiar información de contacto
1. Abre `index.html`
2. Busca la sección `<!-- Contact Section -->`
3. Reemplaza:
   - `+593 4 XXX-XXXX` con tu teléfono real
   - `info@lagranmanzana.com` con tu email real

### Agregar más locales
1. Abre `index.html`
2. Busca la sección `<!-- Locales Section -->`
3. Copia y pega una de las tarjetas `.local-card`
4. Modifica el contenido (nombre, tamaño, categoría, etc.)

### Cambiar colores
1. Abre `css/styles.css`
2. Al inicio del archivo están las variables de color en `:root`
3. Modifica los valores hexadecimales según necesites

### Agregar más fotos
1. Sube las imágenes a la carpeta `images/`
2. Referéncialas en el HTML como: `images/nombre-de-tu-imagen.jpg`

## 🔧 Estructura del proyecto

```
lagranmanzana/
├── index.html          # Página principal
├── README.md           # Este archivo (instrucciones)
├── css/
│   └── styles.css      # Todos los estilos
├── js/
│   └── main.js         # JavaScript (navegación, animaciones)
└── images/
    ├── hero-background.jpg  # Foto aérea de La Gran Manzana
    └── logo.jpg             # Logo oficial
```

## 💡 Consejos

- **Dominio personalizado**: Puedes conectar tu propio dominio (ej: www.lagranmanzana.com) desde GitHub Settings > Pages > Custom domain
- **SSL gratis**: GitHub Pages incluye certificado SSL automáticamente (tu sitio será HTTPS)
- **Actualizaciones**: Cada vez que hagas cambios y los subas a GitHub, el sitio se actualiza automáticamente
- **Sin límites**: Puedes hacer cambios ilimitados, el servicio es 100% gratuito

## 📱 Compatibilidad

- ✅ Chrome, Firefox, Safari, Edge
- ✅ Móviles iOS y Android
- ✅ Tablets
- ✅ Computadoras de escritorio

## 🆘 Soporte

Si tienes problemas:
1. Verifica que todos los archivos se hayan subido correctamente
2. Revisa que la estructura de carpetas sea la correcta
3. Espera 2-3 minutos después de activar GitHub Pages
4. Si aparece error 404, verifica que el archivo se llame `index.html` (todo en minúsculas)

## 📄 Licencia

Este proyecto es propiedad de La Gran Manzana Centro Comercial.

---

**Hecho con ❤️ para La Gran Manzana**

# 📊 Comparador AFIP - Libro IVA vs Comprobantes

Herramienta web para comparar archivos CSV del Libro IVA Compras con Mis Comprobantes Recibidos de AFIP.

## 🚀 Publicar en Línea

### Opción 1: Netlify (Recomendado - Más Fácil)

1. Ve a [netlify.com](https://www.netlify.com/) y crea una cuenta gratuita
2. Haz clic en **"Add new site"** → **"Deploy manually"**
3. **Arrastra la carpeta completa** del proyecto al área de deploy
4. ¡Listo! Recibirás un link como `https://tu-sitio-abc123.netlify.app`

**Para actualizar:** Simplemente arrastra la carpeta nuevamente.

---

### Opción 2: GitHub Pages (Gratis)

1. Crea una cuenta en [github.com](https://github.com/)
2. Crea un nuevo repositorio (puede ser privado)
3. Sube los archivos (`index.html` y `README.md`)
4. Ve a **Settings** → **Pages**
5. En "Source", selecciona **"Deploy from a branch"**
6. Selecciona la rama `main` y carpeta `/ (root)`
7. Click en **Save**
8. En unos minutos tendrás tu link: `https://tu-usuario.github.io/nombre-repo/`

---

### Opción 3: Vercel

1. Ve a [vercel.com](https://vercel.com/) y crea una cuenta
2. Click en **"Add New..."** → **"Project"**
3. Importa desde GitHub o sube los archivos
4. Click en **Deploy**
5. Recibirás un link como `https://tu-proyecto.vercel.app`

---

## 📁 Estructura del Proyecto

```
proyecto/
├── index.html    ← Página principal (todo incluido)
└── README.md     ← Este archivo
```

## 🔐 Privacidad y Seguridad

- ✅ **Los archivos CSV nunca salen de tu navegador**
- ✅ No hay servidor backend - todo se procesa localmente
- ✅ No se almacenan datos en ningún servidor
- ✅ Puedes usar la herramienta sin conexión a internet (después de cargarla)

## 🛠️ Uso

1. Abre el link de tu sitio publicado
2. Carga el **Archivo 1** (Libro IVA Compras)
3. Carga el **Archivo 2** (Mis Comprobantes Recibidos)
4. Configura las columnas de comparación
5. Click en **"Comparar Archivos"**
6. Revisa los resultados y exporta si es necesario

## 📧 Compartir con el Equipo

Una vez publicado, simplemente comparte el link:
- Por email
- Por WhatsApp/Slack
- En un documento compartido

Cada persona puede usar la herramienta de forma independiente con sus propios archivos CSV.

---

Desarrollado para facilitar la conciliación contable con AFIP 🇦🇷

# 🚀 Cómo Subir la Invitación a Render

## 📋 Pasos Detallados para Render

### 1. **Crear cuenta en Render**
- Ve a [render.com](https://render.com)
- Crea una cuenta gratuita (puedes usar GitHub, Google, etc.)

### 2. **Preparar el proyecto**
Ya está todo listo. El archivo `render.yaml` ya está creado en la carpeta.

### 3. **Subir a Render - Opción A: Desde GitHub (Recomendado)**

#### Paso 1: Crear repositorio en GitHub
1. Ve a [github.com](https://github.com) y crea una cuenta si no tienes
2. Crea un nuevo repositorio (público o privado, da igual)
3. Nombre sugerido: `joaqui-cumple` o `invitacion-cumple`
4. **NO inicialices con README** (ya tienes archivos)

#### Paso 2: Subir archivos a GitHub
```bash
# Abre PowerShell o Terminal en la carpeta JoaquiCumple
cd C:\Users\senis\OneDrive\Documentos\webs\JoaquiCumple

# Inicializa git (si no lo has hecho)
git init
git add .
git commit -m "Invitación de cumpleaños Anna Joaquina"

# Conecta con GitHub (reemplaza TU-USUARIO y TU-REPO)
git remote add origin https://github.com/TU-USUARIO/TU-REPO.git
git branch -M main
git push -u origin main
```

**O usa GitHub Desktop:**
1. Descarga [GitHub Desktop](https://desktop.github.com)
2. Abre GitHub Desktop
3. File → Add Local Repository → Selecciona la carpeta `JoaquiCumple`
4. Publish repository → Crea el repo en GitHub

#### Paso 3: Conectar con Render
1. Ve a [dashboard.render.com](https://dashboard.render.com)
2. Click en **"New +"** → **"Static Site"**
3. Conecta tu cuenta de GitHub si no lo has hecho
4. Selecciona el repositorio que acabas de crear
5. Configuración:
   - **Name**: `joaqui-cumple` (o el nombre que quieras)
   - **Branch**: `main` (o `master`)
   - **Root Directory**: `.` (un punto, significa la raíz)
   - **Build Command**: **DEJAR VACÍO** (no necesitas build)
   - **Publish Directory**: `.` (un punto, significa la raíz)
6. Click en **"Create Static Site"**
7. Espera 1-2 minutos
8. ¡Listo! Te dará una URL como: `https://joaqui-cumple.onrender.com`

---

### 4. **Subir a Render - Opción B: Directo (Sin GitHub)**

1. Ve a [dashboard.render.com](https://dashboard.render.com)
2. Click en **"New +"** → **"Static Site"**
3. Click en **"Manual Deploy"** o **"Upload"**
4. Sube todos los archivos de la carpeta `JoaquiCumple`:
   - `index.html`
   - `render.yaml`
   - `INSTRUCCIONES.md` (opcional)
5. Configuración:
   - **Name**: `joaqui-cumple`
   - **Root Directory**: `.` (punto)
   - **Build Command**: (vacío)
   - **Publish Directory**: `.` (punto)
6. Click en **"Create Static Site"**

---

## ⚙️ Configuración Importante

### Root Directory
```
.
```
(Un punto significa la raíz del repositorio/carpeta)

### Build Command
```
(Dejar vacío - no necesitas compilar nada)
```

### Publish Directory
```
.
```
(Un punto significa publicar desde la raíz)

---

## 📱 Una vez publicado

1. Copia la URL que te da Render (ejemplo: `https://joaqui-cumple.onrender.com`)
2. Compártela por WhatsApp
3. ¡Listo! Todos verán la invitación perfecta

---

## 🔧 Si tienes problemas

### Error: "No index.html found"
- Verifica que el `index.html` esté en la raíz
- Verifica que el Root Directory sea `.`

### Error: "Build failed"
- Asegúrate de que Build Command esté **vacío**
- No necesitas ningún comando de build

### La página no carga
- Espera 2-3 minutos después del deploy
- Verifica que la URL sea correcta
- Prueba en modo incógnito

---

## ✨ Ventajas de Render

- ✅ **Gratis** para sitios estáticos
- ✅ **HTTPS automático** (importante para WhatsApp)
- ✅ **URL personalizada** (puedes cambiar el nombre)
- ✅ **Deploy automático** cuando actualizas GitHub
- ✅ **Rápido y confiable**

---

## 🎯 Resumen Rápido

1. Crea cuenta en Render
2. New → Static Site
3. Conecta GitHub (o sube manual)
4. Root Directory: `.`
5. Build Command: (vacío)
6. Publish Directory: `.`
7. ¡Listo! Copia la URL y comparte

---

**¿Necesitas ayuda?** Render tiene un chat de soporte muy bueno en su dashboard.

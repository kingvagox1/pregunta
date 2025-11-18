# Propuesta - Juego "¿Quieres jugar?"

Página simple con dos botones **SÍ** / **NO** donde el botón NO se mueve para que no se pueda pulsar; al pulsar SÍ se reproducen fuegos artificiales.

Archivos principales:
- `juego.html` — página principal (HTML/CSS/JS). 
- `index.html` — (si tienes otra versión) archivo alternativo del sitio.

Cómo probar localmente (forma rápida):
1. Abrir `juego.html` directamente con doble clic en tu navegador.

Servidor local (para probar desde otro dispositivo en la misma red):
```powershell
cd "C:\Users\jeanp\OneDrive\Escritorio\+propuesta"
python -m http.server 8000
# Desde otro dispositivo en la misma red abre http://TU_IP:8000/juego.html
```

Subir a GitHub (resumen de comandos PowerShell):
```powershell
cd "C:\Users\jeanp\OneDrive\Escritorio\+propuesta"
git init
git add .
git commit -m "Initial commit: juego con botones y fuegos artificiales"
# Opción A: usar GitHub web - crea repo en github.com y pega remote luego:
# git remote add origin https://github.com/USERNAME/REPO.git
# git branch -M main
# git push -u origin main

# Opción B (recomendado si tienes GitHub CLI 'gh'):
# gh auth login
# gh repo create NOMBRE-REPO --public --source=. --remote=origin --push
```

Publicar como página web (GitHub Pages):
- En el repositorio -> Settings -> Pages -> Source: `main` (root) y guarda.
- Si quieres que la página principal sea `juego.html`, la URL será `https://USERNAME.github.io/REPO/juego.html`.
- Para servir en la raíz (`/`) renombra `juego.html` a `index.html` antes del push.

Si quieres, puedo:
- Preparar el `git commit` local y los archivos `README.md` y `.gitignore` (ya hecho).
- Generar el repo con `gh` (necesitarás autenticación en tu cuenta) si me autorizas a darte los comandos.

Si vas a desplegar con Netlify/Vercel/Supabase o Firebase, te doy los pasos específicos.

---

Si quieres que yo cree el repositorio en GitHub por ti, necesitarás ejecutar los comandos `gh auth login` en tu máquina para autorizar al CLI (no puedo autenticar en tu cuenta desde aquí).
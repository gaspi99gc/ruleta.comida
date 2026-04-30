# 🎡 Ruleta de Comidas

Página web interactiva para elegir qué cocinar según el tiempo disponible y la dificultad.

---

## 📁 Estructura del proyecto

```
ruleta-comidas/
├── index.html        ← La página completa
├── images/           ← Acá van todas las fotos
│   ├── tostadas-palta.jpg
│   ├── ensalada-cesar.jpg
│   └── ... (ver lista completa abajo)
└── README.md
```

---

## 🖼️ Cómo agregar las fotos

1. Generá cada foto con IA (Midjourney, DALL·E, Leonardo, etc.)
2. Guardala con el nombre exacto que aparece en la lista
3. Tirala dentro de la carpeta `images/`
4. Subí los cambios a GitHub → Vercel se actualiza solo

**Las fotos se muestran automáticamente cuando las agregás.** Mientras no estén, aparece un placeholder con ícono de plato.

### Lista de nombres de archivo esperados:

**Fácil — 30 min o menos**
- `tostadas-palta.jpg`
- `ensalada-cesar.jpg`
- `tortilla-espanola.jpg`
- `fideos-manteca.jpg`
- `sandwich-caprese.jpg`

**Fácil — 60 minutos**
- `milanesas-horno.jpg`
- `arroz-salteado.jpg`
- `omelette-relleno.jpg`
- `sopa-tomate.jpg`
- `pollo-limon.jpg`

**Fácil — Más de 60 min**
- `guiso-lentejas.jpg`
- `pollo-horno.jpg`
- `estofado-verduras.jpg`
- `fideos-bolonesa.jpg`
- `arroz-leche.jpg`

**Medio — 30 min o menos**
- `wok-vegetales.jpg`
- `quesadillas-pollo.jpg`
- `croquetas-papa.jpg`
- `risotto-expres.jpg`
- `burger-casera.jpg`

**Medio — 60 minutos**
- `lasana-verduras.jpg`
- `empanadas-horno.jpg`
- `curry-pollo.jpg`
- `ceviche-clasico.jpg`
- `gnocchi-salsa.jpg`

**Medio — Más de 60 min**
- `pulled-pork.jpg`
- `cazuela-mariscos.jpg`
- `canelones-ricota.jpg`
- `paella-valenciana.jpg`
- `carne-vino.jpg`

**Difícil — 30 min o menos**
- `tempura-crocante.jpg`
- `huevos-benedictinos.jpg`
- `crepes-flameados.jpg`
- `tataki-atun.jpg`
- `emulsion-ajo.jpg`

**Difícil — 60 minutos**
- `pasta-fresca.jpg`
- `souffle-queso.jpg`
- `pechugas-rellenas.jpg`
- `sushi-rolls.jpg`
- `creme-brulee.jpg`

**Difícil — Más de 60 min**
- `asado-tira.jpg`
- `croissants-manteca.jpg`
- `pato-naranja.jpg`
- `caldo-ramen.jpg`
- `tarta-tatin.jpg`

---

## 🚀 Cómo subir a GitHub + Vercel

### 1. Subir a GitHub

**Opción A — Sin Git (más fácil):**
1. Entrá a [github.com](https://github.com) y creá una cuenta si no tenés
2. Hacé click en **"New repository"**
3. Nombre: `ruleta-comidas`, dejalo público
4. Una vez creado, hacé click en **"uploading an existing file"**
5. Arrastrá toda la carpeta `ruleta-comidas` (con `index.html` e `images/`)
6. Click en **"Commit changes"**

**Opción B — Con Git:**
```bash
cd ruleta-comidas
git init
git add .
git commit -m "primer commit"
git remote add origin https://github.com/TU_USUARIO/ruleta-comidas.git
git push -u origin main
```

### 2. Publicar en Vercel

1. Entrá a [vercel.com](https://vercel.com) y creá cuenta (podés entrar con GitHub)
2. Click en **"Add New Project"**
3. Importá el repo `ruleta-comidas`
4. Dejá todo por defecto → click **"Deploy"**
5. En ~30 segundos tenés una URL pública tipo `ruleta-comidas.vercel.app`

### 3. Actualizar fotos después

Cada vez que agregues fotos nuevas:
- Si usaste Opción A: entrá al repo en GitHub → `images/` → "Add file"
- Si usaste Git: `git add . && git commit -m "agrego fotos" && git push`

Vercel detecta el cambio y actualiza la página automáticamente.

---

## 💡 Tips para las fotos con IA

- Resolución recomendada: **800x600px** o similar (ratio 4:3)
- Formato: **JPG** (más liviano que PNG para fotos)
- Prompt sugerido: *"overhead food photography, [nombre del plato], natural lighting, white plate, clean background, professional"*

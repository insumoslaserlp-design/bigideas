# Big Ideas Little Maker — tienda web

Catálogo de impresión 3D para GitHub Pages. Todo vive en este repositorio:

- `index.html` — la web (tienda + panel de admin).
- `data.json` — productos, precios, stock, promociones, videos y textos. Lo escribe el panel.
- `media/` — fotos y videos que se suben desde el panel.

## 1. Publicar la web (una sola vez)
1. En GitHub: **New repository** → nombre, por ejemplo `bigideas` → **Public** → Create.
2. **Add file → Upload files** y subí todo el contenido de esta carpeta (incluida `media/` y el archivo `.nojekyll`).
3. **Settings → Pages** → *Source: Deploy from a branch* → rama `main`, carpeta `/ (root)` → Save.
4. En 1–2 minutos la web queda en `https://TU-USUARIO.github.io/bigideas/`.

## 2. Crear la clave del admin (una sola vez por dispositivo)
1. GitHub → foto de perfil → **Settings → Developer settings → Personal access tokens → Fine-grained tokens → Generate new token**.
2. *Repository access*: **Only select repositories** → elegí solo `bigideas`.
3. *Permissions → Repository permissions → Contents*: **Read and write**.
4. Elegí una fecha de vencimiento (por ejemplo 1 año) y copiá la clave.

## 3. Entrar al admin
- Abrí la web, bajá hasta el final y tocá **admin** (o entrá a `.../bigideas/#admin`).
- Completá usuario, repositorio, rama (`main`) y pegá la clave. Queda guardada solo en ese dispositivo.
- Editá productos, promociones, videos de Instagram y fotos de clientes, y tocá **Publicar cambios**. La web pública se actualiza en 1–2 minutos.

## Notas
- La clave nunca se sube al repositorio. Si perdés el celular, borrala en GitHub y creá otra.
- Los videos del iPhone se adaptan solos a MP4 (máx. 60 s) antes de subirse.
- Un repositorio de GitHub Pages puede pesar hasta 1 GB: con fotos comprimidas y videos cortos hay espacio para muchísimos productos. Usá "Borrar archivos que no usa ningún producto" en la pestaña Tienda de vez en cuando.
- Dominio propio (ej. `bigideaslittlemaker.com`): se configura en Settings → Pages → Custom domain.

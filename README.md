# Para Julia

Site-carta de Isaac para Julia.

## Arquivos que PRECISAM ir juntos

O `index.html` e estas mídias têm que ficar **na mesma pasta**:

- `index.html`
- `abraco.jpg`
- `passeio.jpg`
- `carro.jpg`
- `perto.jpg`
- `mascara.jpg`
- `beijo.mp4`
- `filtro.mp4`

Se só o HTML for enviado, as fotos não aparecem.

## Publicar no GitHub Pages

1. https://github.com/new — nome `para-julia` — repositório vazio
2. Em **uploading an existing file**, arraste **todos** os arquivos acima de uma vez (não só o HTML)
3. Commit
4. Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save
5. Link: `https://SEU-USUARIO.github.io/para-julia/`

Ou pelo terminal, dentro desta pasta:

```bash
git add .
git commit -m "fotos na raiz"
git remote add origin https://github.com/SEU-USUARIO/para-julia.git
git push -u origin main
```

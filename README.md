# Para Julia

Site-carta de Isaac para Julia.

## Publicar no GitHub Pages

### 1. Criar o repositório
1. Entre em https://github.com/new
2. Nome sugerido: `para-julia`
3. Deixe **sem** README, **sem** .gitignore e **sem** licença
4. Clique em **Create repository**

> Se o repositório for **público**, qualquer pessoa com o link vê as fotos e os vídeos.  
> Conta grátis do GitHub só publica GitHub Pages a partir de repositório público.

### 2. Enviar os arquivos

No computador, abra o terminal **dentro desta pasta** e rode (troque `SEU-USUARIO`):

```bash
git init
git add .
git commit -m "site para Julia"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/para-julia.git
git push -u origin main
```

Se preferir sem terminal: no GitHub, clique em **uploading an existing file** e arraste `index.html`, a pasta `fotos` e o `README.md`.

### 3. Ligar o GitHub Pages
1. Abra o repositório
2. **Settings** → **Pages**
3. **Source**: Deploy from a branch
4. **Branch**: `main` / pasta `/ (root)`
5. Save

Em 1 ou 2 minutos o site fica em:

```
https://SEU-USUARIO.github.io/para-julia/
```

### 4. Mandar para ela
Envie só o link. Peça para abrir no celular, no Chrome ou no Safari.

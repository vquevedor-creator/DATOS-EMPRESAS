# FORMATO NETCASH — Llenador BBVA Alta Empresas

Herramienta en una sola página HTML: carga el PDF del formulario, ingresa el código central y genera el PDF llenado (pdf-lib).

## Uso

Abre `bbva_alta_llenador (2).html` en el navegador (doble clic o arrastrar al Chrome/Edge).

## Publicar en GitHub y enlace

1. Inicia sesión en GitHub CLI: `gh auth login`
2. En esta carpeta ejecuta:

```bash
cd "/Users/victorquevedo/Desktop/FORMATO NETCASH"
git remote add origin https://github.com/TU_USUARIO/TU_REPO.git   # si creaste el repo vacío en la web
git push -u origin main
```

O crea y sube en un solo paso (con `gh` ya autenticado):

```bash
gh repo create TU_REPO --public --source=. --remote=origin --push
```

- **Link del repositorio:** `https://github.com/TU_USUARIO/TU_REPO`
- **GitHub Pages (opcional):** en el repo → *Settings* → *Pages* → *Branch: main* → */ (root)*. Para que abra directo el llenador, renombra el HTML a `index.html` o indica la ruta del archivo en la URL.

# BM Odontologia Estética

Site institucional da BM Odontologia Estética, em Sorriso (MT).

## Estrutura

```
index.html            página do site
assets/img/hero.jpg   foto do topo
assets/img/dr-daniel.jpg
assets/img/logo.svg   logo (também usada como favicon)
.nojekyll             faz o GitHub Pages servir os arquivos como estão
```

## Publicar no GitHub Pages

1. Crie um repositório e envie todos estes arquivos para a raiz da branch `main`.
2. Em **Settings → Pages**, em *Build and deployment*, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
3. Em poucos minutos o site fica no ar em `https://SEU-USUARIO.github.io/NOME-DO-REPO/`.

## Domínio próprio (ex.: bmodontologia.com.br)

1. Em **Settings → Pages → Custom domain**, digite o domínio e salve (o GitHub cria o arquivo `CNAME`).
2. No Registro.br, configure o DNS do domínio:
   - Registros **A** do domínio apontando para `185.199.108.153`, `185.199.109.153`, `185.199.110.153` e `185.199.111.153`
   - Registro **CNAME** de `www` apontando para `SEU-USUARIO.github.io`
3. Depois que o DNS propagar, marque **Enforce HTTPS**.

## Pendências antes de publicar

- Link do Instagram no rodapé (comentário `TROCAR` no código)
- Link do Facebook, se a clínica tiver página
- CRO e biografia reais do Dr. Daniel (comentário `BIOGRAFIA DE EXEMPLO`)

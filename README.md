<div align="center">

<img src="Banner.png" width="100%" alt="Banner Letícia Andrade"/>

<br><br>

<img src="https://readme-typing-svg.herokuapp.com?font=Playfair+Display&size=28&duration=3200&pause=900&color=F7B7FF&center=true&vCenter=true&width=900&lines=Construindo+tecnologia+centrada+em+pessoas.;Criando+experiências+digitais+com+propósito.;Onde+código+encontra+emoção+e+design." />

</div>

---

<div align="center">

`未来は私たちの手の中にある`

### O futuro está em nossas mãos.

</div>

<br>

# ✦ sobre_mim

```js
const leticia = {
  nome: "Letícia Andrade",
  localizacao: "São Paulo, Brasil",

  foco: [
    "Desenvolvimento Web",
    "UI/UX Design",
    "Análise de Dados",
    "Tecnologia Criativa"
  ],

  estudando: [
    "Java",
    "MySQL",
    "APIs",
    "Backend"
  ],

  interesses: [
    "Interfaces Cinematográficas",
    "Tecnologia Humanizada",
    "Acessibilidade",
    "Experiências Digitais"
  ],

  projetoPrincipal: "Ever Rise",

  filosofia:
    "tecnologia com emoção, propósito e beleza"
}
```

---

# ✦ ever_rise

> Tecnologia criada para devolver autonomia.

A **Ever Rise** é um projeto de tecnologia assistiva criado para ajudar pessoas com mobilidade reduzida através de uma experiência mais segura, humana e acessível.

```txt
acessibilidade • autonomia • segurança • design • inovação
```

---

# ✦ tecnologias

<div align="center">

<img src="https://skillicons.dev/icons?i=html,css,js,java,mysql,git,github,figma,vscode&theme=dark" />

</div>

---

# ✦ universo_github

<div align="center">

<img height="170em" src="https://github-readme-stats.vercel.app/api?username=andradebjl24-cmyk&show_icons=true&hide_border=true&bg_color=0D0618&title_color=F7B7FF&text_color=F4E7FF&icon_color=C084FC"/>

<img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=andradebjl24-cmyk&layout=compact&hide_border=true&bg_color=0D0618&title_color=F7B7FF&text_color=F4E7FF"/>

</div>

---

# ✦ cobra_de_contribuições

<div align="center">

<img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" />

</div>

---

# ✦ estudando_agora

```txt
▸ Java
▸ Banco de Dados
▸ APIs
▸ Desenvolvimento Web
▸ UI/UX
▸ Análise de Dados
```

---

# ✦ direção_criativa

```txt
interfaces futuristas suaves
experiências digitais cinematográficas
tecnologia feita para pessoas reais
design com emoção
código com intenção
```

---

# ✦ conecte_se

<div align="center">

<a href="https://github.com/andradebjl24-cmyk">
  <img src="https://img.shields.io/badge/GitHub-160A24?style=for-the-badge&logo=github&logoColor=F7B7FF">
</a>

<a href="https://linkedin.com">
  <img src="https://img.shields.io/badge/LinkedIn-160A24?style=for-the-badge&logo=linkedin&logoColor=F7B7FF">
</a>

<a href="mailto:andradebjl24@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-160A24?style=for-the-badge&logo=gmail&logoColor=F7B7FF">
</a>

</div>

---

<div align="center">

```txt
✦ criando tecnologia entre sonhos, design e realidade ✦
```

</div>

<!-- SNAKE ANIMATION -->

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/andradebjl24-cmyk/andradebjl24-cmyk/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/andradebjl24-cmyk/andradebjl24-cmyk/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="github contribution grid snake animation"
    src="https://raw.githubusercontent.com/andradebjl24-cmyk/andradebjl24-cmyk/output/github-contribution-grid-snake-dark.svg"
  />
</picture>

<!-- SNAKE WORKFLOW -->

```yml
name: Generate Purple Snake

on:
  schedule:
    - cron: "0 */12 * * *"

  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest

    permissions:
      contents: write

    steps:
      - name: Gerar cobra roxa
        uses: Platane/snk@v3
        with:
          github_user_name: andradebjl24-cmyk
          outputs: |
            dist/github-contribution-grid-snake.svg?palette=github-light&color_snake=#A855F7&color_dots=#F3E8FF,#E9D5FF,#D8B4FE,#C084FC,#9333EA
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark&color_snake=#E879F9&color_dots=#160A24,#2A143D,#4C1D95,#7E22CE,#C084FC

      - name: Publicar animação
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist

        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

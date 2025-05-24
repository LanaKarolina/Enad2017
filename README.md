
# 📘 Análise Estatística ENADE 2017

Este repositório contém uma análise estatística baseada nos microdados do ENADE 2017 para o curso de Geografia - Licenciatura, desenvolvida em R usando RMarkdown.

## 🔍 Objetivo

O projeto visa explorar, resumir e visualizar os dados do ENADE, com foco em métricas descritivas e gráficos informativos, publicados em formato HTML através do GitHub Pages.

## 📂 Estrutura do Projeto

```
├── enade2017_geo_githubpages.Rmd     # Código-fonte do relatório (RMarkdown)
├── docs/
│   └── enade2017_geo_githubpages.html  # Relatório HTML renderizado para publicação
├── .gitignore
└── Enad2017.Rproj
```

## 🌐 Relatório Online

Você pode visualizar o relatório completo e renderizado neste link:

👉 [Clique aqui para visualizar o relatório HTML](https://lanakarolina.github.io/Enad2017/enade2017_geo_githubpages.html)

## 🚀 Como reproduzir localmente

1. Clone o repositório:
```bash
git clone https://github.com/LanaKarolina/Enad2017.git
```

2. Abra o arquivo `.Rproj` no RStudio.

3. Instale os pacotes necessários, se ainda não tiver:
```r
install.packages("rmarkdown")
```

4. Renderize o relatório manualmente:
```r
rmarkdown::render("enade2017_geo_githubpages.Rmd", output_dir = "docs")
```

## 📌 Observação

O arquivo de microdados original (`MICRODADOS_ENADE_2017.txt`) foi removido do repositório por exceder o limite de 100 MB do GitHub. Para reproduzir a análise, você precisará baixar os dados diretamente do site oficial do INEP.

---

Feito com 💙 em R por [Lana Karolina]

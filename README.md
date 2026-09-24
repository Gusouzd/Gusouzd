<h1 align="center">Olá, eu sou o Gustavo</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=2F81F7&center=true&vCenter=true&width=600&lines=Engenharia+de+Dados;Pipelines+ELT+com+Python%2C+BigQuery+e+dbt;P%C3%B3s+em+Big+Data+%26+Intelig%C3%AAncia+Anal%C3%ADtica" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/gustavorafael09"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/São_Paulo,_SP-222?style=for-the-badge&logo=googlemaps&logoColor=white" />
</p>

---

### Sobre mim

- Formado em **Ciência da Computação** (Anhembi Morumbi) e cursando pós em **Big Data & Inteligência Analítica** (PUCPR)
- Vindo do **suporte técnico** (N1 → N2) e fazendo a transição para **Engenharia de Dados**
- Gosto de construir pipelines **ELT** de ponta a ponta: ingestão, modelagem dimensional, testes de qualidade e orquestração

### Stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=python,gcp,git,github,githubactions,linux&theme=dark" />
</p>

<p align="left">
  <img src="https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white" />
  <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" />
</p>

---

### Projetos em destaque

#### [bcb-indicadores-pipeline](https://github.com/Gusouzd/bcb-indicadores-pipeline)
Pipeline **automatizado** que extrai diariamente **SELIC, IPCA e câmbio (USD)** da API SGS do Banco Central.

`Python` → `BigQuery (raw)` → `dbt (star schema)` · orquestrado com **GitHub Actions** todo dia útil às 6h

- Carga **idempotente** (MERGE incremental, sem duplicação em reexecuções)
- Modelagem dimensional com tabelas fato e dimensão
- **19 testes** de qualidade com dbt

#### [olist-payments-analytics](https://github.com/Gusouzd/olist-payments-analytics)
Pipeline ELT sobre ~100 mil pedidos do e-commerce brasileiro (Olist), analisando **meios de pagamento, vouchers e parcelamento**.

`Python` → `BigQuery` → `dbt (staging → intermediate → marts)`

- Cartão de crédito responde por **mais de 70% do valor transacionado**
- Ticket médio no crédito de **R$ 163** com **3,5 parcelas** em média, contra pagamento à vista no boleto/débito
- **26 testes** automatizados passando e DAG documentado com linhagem

---

### Estatísticas

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Gusouzd&show_icons=true&theme=github_dark&hide_border=true&locale=pt-br" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Gusouzd&layout=compact&theme=github_dark&hide_border=true&locale=pt-br" />
</p>

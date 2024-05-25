# Projeto Web Scraping

## Visão Geral
<div>
  <img src="/img/visao_geral.png"  width="70%" height="70%">
</div>

## Preço Médio por Marca
<div>
  <img src="/img/preco_marca.png"  width="50%" height="50%">
</div>

## Satisfação por Marca
<div>
  <img src="/img/satisfacao_marca.png"  width="50%" height="50%">
</div>


## Passo a passo
- Para rodar o web scraping

```bash
scrapy crawl mercadolivre -o ../data/data.jsonl
```

- Para rodar o PANDAS, tem que fazer isso dentro da pasta SRC

```bash
python transformacao/main.py
```

- Para rodar o Streamlit tem que fazer isso dentro da pasta SRC

```bash
streamlit run dashboard/app.py
```


# Análise de Mercado: Monitoramento de Preços com Scrapy e Dashboard com Streamlit
Este projeto realiza o monitoramento de preços de produtos utilizando a biblioteca Scrapy para scraping de dados e exibe os resultados em um dashboard interativo criado com Streamlit.

## Arquitetura
Uma ETL em Python para Web Scraping

- Extração - Scrapy
- Transformação e Load - Pandas
- Dashboard - Streamlit
- Banco de dados - Postgres


## Demonstração do Dashboard 
### Tela inicial
<div>
  <img src="/img/visao_geral.png"  width="60%" height="60%" >
</div>

### Preço Médio por Marca
<div>
  <img src="/img/preco_marca.png"  width="50%" height="50%">
</div>

### Satisfação por Marca
<div>
  <img src="/img/satisfacao_marca.png"  width="50%" height="50%">
</div>


## Uso
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


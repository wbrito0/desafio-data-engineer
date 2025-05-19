<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Desafio de Engenharia de Dados</title>
</head>
<body>
  <h1>Desafio de Engenharia de Dados</h1>

  <p>Este repositório contém a solução para o desafio técnico de Engenharia de Dados e DataOps 2025.</p>

  <h2>Organização dos Dados</h2>

  <p>Para executar corretamente os notebooks e scripts deste projeto, certifique-se de que os arquivos CSV estejam organizados da seguinte forma:</p>

  <pre><code>├── dados/
│   ├── olist_customers_dataset.csv
│   ├── olist_geolocation_dataset.csv
│   ├── olist_order_items_dataset.csv
│   ├── olist_order_reviews_dataset.csv
│   ├── olist_order_payments_dataset.csv
│   ├── olist_orders_dataset.csv
│   ├── olist_products_dataset.csv
│   ├── olist_sellers_dataset.csv
│   └── product_category_name_translation.csv
├── desafio-data-engineer.ipynb
├── olist.db (será criado durante a execução)
└── README.md
</code></pre>

  <h2>Observações</h2>

  <ul>
    <li>Todos os arquivos CSV devem estar localizados na pasta <code>dados/</code> na raiz do projeto.</li>
    <li>Certifique-se de que os nomes dos arquivos correspondam exatamente aos utilizados no código, incluindo letras minúsculas e extensões <code>.csv</code>.</li>
    <li>Os dados utilizados são provenientes do <a href="https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce">Olist Dataset</a>.</li>
  </ul>

  <h2> Executando o Projeto</h2>

  <ol>
    <li>Clone este repositório:
      <pre><code>git clone https://github.com/wbrito0/desafio-data-engineer.git</code></pre>
    </li>
    <li>Navegue até o diretório do projeto:
      <pre><code>cd desafio-data-engineer</code></pre>
    </li>
    <li>Certifique-se de que a pasta <code>dados/</code> contenha todos os arquivos CSV mencionados acima.</li>
    <li>Execute o notebook <code>desafio-data-engineer.ipynb</code> utilizando o Jupyter Notebook ou JupyterLab.</li>
  </ol>

  <h2>Tecnologias Utilizadas</h2>

  <ul>
    <li>Python</li>
    <li>Pandas</li>
    <li>Plotly</li>
    <li>scikit-learn</li>
    <li>Jupyter Notebook</li>
  </ul>
</body>
</html>

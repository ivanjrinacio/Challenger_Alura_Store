# Challenger Alura Store 🏪

![Status](https://img.shields.io/badge/status-concluído-green)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0-blue?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-blue?logo=matplotlib)

---

## 🎯 Sobre o Projeto

O Sr. João, dono da rede de e-commerce **Alura Store**, deseja vender uma de suas quatro lojas para investir em um novo negócio. O objetivo deste projeto é analisar o desempenho de cada loja e, com base nos dados, gerar um relatório que indique qual delas representa a melhor candidata para a venda, ou seja, a que possui o menor desempenho geral.

> Repositório criado para o desafio prático do curso **Tech Foundation - Data Science** (One Oracle Next Education - Alura).
---

## 🛠️ Tecnologias e Ferramentas

* **Linguagem:** Python
* **Bibliotecas:**
    * `Pandas` para manipulação e análise dos dados.
    * `NumPy` para análise dos dados.
    * `Matplotlib` para visualização e criação dos gráficos.
* **Ambiente:** Google Colab

---

## 📊 Análise e Conclusões

A análise foi focada em métricas chave para determinar o desempenho de cada loja.

**Métricas Analisadas:**
* Faturamento total por loja
* Categorias de produtos mais populares
* Média de avaliação dos clientes
* Produtos mais e menos vendidos
* Custo médio do frete

### Resultados

**A principal conclusão da análise é que a LOJA 4 deve ser a escolhida para a venda.** Isso se baseia nos seguintes pontos:
* Menor faturamento comparado às outras.
* Avaliações médias de clientes consistentemente mais baixas.

O gráfico abaixo resume o faturamento de cada loja, destacando visualmente a performance inferior da loja recomendada.

![Gráfico de Faturamento](assets/Faturamento%20das%20Lojas.png)

Enquanto que neste outro gráfico a loja 4 é apenas a terceira melhor avaliada pelos clientes.

![Gráfico de Avaliação da Loja](assets/Avalia%C3%A7%C3%A3o%20das%20notas%20das%20lojas.png)

---

## 💡 Principais Insights
Com base na análise, foram extraídas as seguintes conclusões:

*📈 **Performance de Vendas Consistente:** O mix de produtos campeões de venda é similar entre as lojas, indicando uma estratégia de catálogo bem definida para a rede. O diferencial de desempenho não reside nos produtos oferecidos, mas em outros fatores específicos de cada loja.

*👥 **Satisfação do Cliente como Fator Crítico:** Apesar de todas as lojas manterem um padrão de qualidade com boas avaliações, a Loja 4 apresenta a segunda menor média. Essa pequena, porém consistente, diferença na satisfação do cliente é um forte indicador de problemas operacionais ou de mercado local que impactam diretamente seu faturamento.


## 📁 Estrutura dos Dados

O conjunto de dados utilizado contém informações detalhadas sobre as vendas, produtos e clientes.

<details>
<summary>Clique para ver a estrutura do DataFrame</summary>

|index|Produto|Categoria do Produto|Preço|Frete|Data da Compra|Vendedor|Local da compra|Avaliação da compra|Tipo de pagamento|Quantidade de parcelas|lat|lon|
|---|---|---|---|---|---|---|---|---|---|---|---|---|
|0|Assistente virtual|eletronicos|219.08|9.2497899853|16/01/2021|Pedro Gomes|SP|4|cartao_credito|8|-22.19|-48.79|
|1|Mesa de jantar|moveis|256.35|11.2343053621|18/05/2022|Beatriz Moraes|RJ|1|cartao_credito|4|-22.25|-42.66|
|2|Jogo de tabuleiro|brinquedos|279.51|21.2626809863|15/03/2021|João Souza|DF|1|cartao_credito|1|-15.83|-47.86|
|3|Micro-ondas|eletrodomesticos|1009.99|54.6673442173|03/05/2022|João Souza|RS|4|boleto|1|-30.17|-53.5|
|4|Cadeira de escritório|moveis|446.99|26.9646890964|07/11/2020|Larissa Alves|MG|5|boleto|1|-18.1|-44.38|

</details>

---

## 🚀 Como Executar o Projeto

As urls dos dados utilizados na análise estão no notebook.

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/ivanjrinacio/Challenger_Alura_Store.git](https://github.com/ivanjrinacio/Challenger_Alura_Store.git)
    ```
2.  **Acesse a pasta do projeto:**
    ```bash
    cd Challenger_Alura_Store
    ```
3.  **Instale as dependências:**
    *É recomendado criar um ambiente virtual antes deste passo.*
    ```bash
    pip install -r requirements.txt
    ```
4.  **Execute o Notebook:**
    Abra o arquivo `AluraStoreBr.ipynb` no Google Colaboratory ou em qualquer ambiente Jupyter de sua preferência. As células podem ser executadas sequencialencialmente.

---

## 👨‍💻 Autor

Desenvolvido por **Ivan Jr Inacio**.

[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/ivanjrinacio/)
[<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />](https://github.com/ivanjrinacio)

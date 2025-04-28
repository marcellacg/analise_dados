# Análise de Vendas e Desempenho das Lojas do Senhor João

Este projeto tem como objetivo ajudar o Senhor João a decidir qual loja da sua rede ele deve vender para iniciar um novo empreendimento. O foco da análise é avaliar o desempenho de vendas, as avaliações dos clientes e outras métricas das 4 lojas fictícias dele. O objetivo final é identificar a loja com menor eficiência e fornecer uma recomendação baseada nos dados.

## Funcionalidades

- Há a utilização da biblioteca **Pandas**.
- Visualizações de dados com a biblioteca **Matplotlib**.
- Análise de métricas como faturamento, avaliações e desempenho de vendas.

## Estrutura do Dataset

O dataset contém as seguintes informações sobre as transações:

- **Produto e Categoria**: Itens vendidos e suas respectivas classificações.
- **Preço e Frete**: Valores das vendas e custos de envio.
- **Data de Compra e Local**: Informações de dia e localização geográfica.
- **Avaliação da Compra**: Feedback dos clientes sobre a compra.
- **Tipo de Pagamento e Parcelas**: Métodos utilizados pelos clientes.
- **Coordenadas Geográficas**: Localização das transações.

## Objetivo

O projeto visa identificar qual loja tem o pior desempenho com base nas métricas analisadas e apresentar uma recomendação final para o Senhor João sobre a melhor decisão a ser tomada.

## Tecnologias Utilizadas

- **Pandas** para manipulação de dados
- **Matplotlib** para visualização de dados
- **Python** como linguagem de programação principal
- **Jupyter Notebook** para desenvolvimento e execução interativa do código
- **VSCode** como ambiente de desenvolvimento integrado (IDE)

## Como Executar

### Passo a Passo para Executar na IDE VSCode

1. **Clone o Repositório**:
   Primeiro, clone o repositório do projeto para sua máquina local.
   ```bash
   git clone <URL do repositório>

2. **Abra o Projeto no VSCode**:

  Abra o VSCode e selecione a opção "Abrir Pasta" para abrir a pasta do repositório clonado.

  Certifique-se de que você tenha a extensão Python instalada no VSCode para facilitar a execução do código Python.

3. **Abra o Arquivo de Código**:

   Abra o arquivo principal do código, como analise_vendas.py ou o notebook Jupyter se estiver utilizando .ipynb.

4. **Execute o Código**:

  - Se for um arquivo Python (.py), você pode simplesmente clicar no botão de Executar no VSCode ou rodar o código diretamente no terminal:

  ```bash
  python analise_vendas.py
  ```
  - Se estiver utilizando um Jupyter Notebook, basta abrir o arquivo .ipynb e executar as células individualmente no próprio VSCode.

  - Ativando o ambiente virtual (Linux/macOS):
  
  ```bash
  source meu_env/bin/activate
  ```
  - Ambiente virtual (Windows):
  ```bash
  meu_ambiente\Scripts\activate
  ```

  - Para instalar os requirements do projeto, use o comando:

  ```bash
  pip install -r requirements.txt
  ```

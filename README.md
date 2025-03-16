# 🏡 **Análise de Dados Imobiliários - Pandas**

Este repositório contém scripts Python para análise e manipulação de dados imobiliários utilizando a biblioteca `pandas`. O código permite realizar tarefas como importação, visualização, manipulação e análise estatística de dados relacionados a imóveis na cidade de São Paulo.

## 🚀 **Funcionalidades**

O código implementa as seguintes funcionalidades:

- **Importação de Dados**: Carregamento de arquivos CSV contendo informações sobre imóveis.
- **Visualização de Dados**: Exibição das primeiras e últimas linhas do dataset para inspeção inicial.
- **Renomeação de Colunas**: Conversão de nomes de colunas para o idioma português.
- **Filtros e Consultas**: Aplicação de filtros simples e compostos para extrair informações relevantes (exemplo: imóveis por bairro ou tipo).
- **Análises Estatísticas**: Cálculos de métricas como média, mediana e desvio padrão de variáveis numéricas.
- **Tratamento de Dados Nulos**: Preenchimento de valores nulos com valores predefinidos para garantir integridade dos dados.

## 🧑‍💻 **Estrutura do Código**

### 1. **Criação e Exibição do DataFrame**
- Um `DataFrame` é criado com dados manuais sobre funcionários, incluindo nome, cargo e salário.
- Exibição das primeiras e últimas linhas utilizando `head()` e `tail()`.

### 2. **Importação de Dataset Externo**
- Importação de um arquivo CSV com informações sobre moradias, utilizando o `pandas.read_csv()`.
  
### 3. **Renomeação de Colunas**
- Renomeação das colunas do DataFrame de inglês para português, visando maior clareza.

### 4. **Filtro de Dados**
- Aplicação de filtros para selecionar imóveis de bairros, tipos ou faixas de preço específicas.
- Combinação de múltiplos filtros utilizando operadores lógicos (`&` para "e" e `|` para "ou").

### 5. **Análise Estatística**
- Cálculo de métricas como **média**, **mediana** e **desvio padrão** dos preços de casas em condomínio abaixo de 5000.
- Utilização do método `describe()` para gerar estatísticas descritivas do dataset.

### 6. **Preenchimento de Dados Faltantes**
- Substituição de valores nulos por valores definidos, mantendo a consistência dos dados.

## 🛠 **Requisitos**

Para rodar este projeto, é necessário ter o Python instalado em sua máquina, além da biblioteca `pandas`.

### Instalação de Dependências:

```bash
pip install pandas
```

## 🚀 **Como Utilizar**

1. **Clone o Repositório**

   Clone este repositório para sua máquina local:

   ```bash
   git clone https://github.com/seu_usuario/seu_repositorio.git
   ```

2. **Execute o Script Python**

   Abra o script Python e execute as células de código para realizar as análises.

3. **Importe seu Próprio Dataset**

   Para importar o seu próprio dataset, substitua o caminho do arquivo CSV na variável `url`:

   ```python
   url = "/caminho/do/seu/dataset.csv"
   df = pd.read_csv(url)
   ```

4. **Realize Consultas e Análises**

   Utilize as funções implementadas ou crie novas consultas conforme necessário para explorar os dados.

## 💡 **Contribuições**

Contribuições são bem-vindas! Se você tem sugestões ou melhorias para este projeto, sinta-se à vontade para fazer um **fork** e enviar **pull requests**.

## 📜 **Licença**

Este projeto está licenciado sob a Licença MIT.

---

# Análise de Dados SP 🚀

Este projeto tem como objetivo explorar e extrair insights de um conjunto de dados referentes à cidade de São Paulo, contendo informações como nome, cidade, bairro, CEP, data de nascimento, sexo, e-mail, status na Receita Federal, quantidade de veículos e renda presumida. 📊

---

## 📑 Sumário

- [Visão Geral](#vis%C3%A3o-geral)
- [Descrição dos Dados](#descri%C3%A7%C3%A3o-dos-dados)
- [Visualizações](#visualiza%C3%A7%C3%B5es)
- [Requisitos](#requisitos)
- [Como Executar](#como-executar)
- [Contribuições](#contribui%C3%A7%C3%B5es)
- [Licença](#licen%C3%A7a)
- [Contato](#contato)

---

## Visão Geral ✨

O projeto utiliza Python, Pandas e Matplotlib para realizar a análise exploratória dos dados. Foram gerados gráficos que ajudam a entender:

- **Top 10 CBO Mais Frequentes - SP:** Visualiza os códigos de ocupação mais comuns.
- **Distribuição de Faixas Salariais em SP:** Gráfico de barras que mostra a frequência das faixas salariais (possível aplicação de arredondamento para melhor agrupamento).
- **Top 15 CEPs de SP:** Gráfico de barras (ou barras horizontais) destacando os CEPs com maior frequência.
- **Distribuição de Idades:** Cálculo da idade a partir da data de nascimento e visualização com histograma.
- **Distribuição de Status da Receita Federal:** Gráfico de pizza que mostra a proporção dos diferentes status cadastrais.
- **Distribuição por Gênero:** Gráfico de barras comparando a quantidade de registros por gênero.
- **Distribuição da Quantidade de Veículos:** Histograma que ilustra a frequência da quantidade de veículos por pessoa.

Cada trecho de código possui comentários explicando sua funcionalidade linha a linha, facilitando a compreensão do processo de extração e visualização dos dados. 📝

---

## Descrição dos Dados 🔍

Os dados incluem as seguintes colunas:

- **NOME:** Nome do indivíduo.
- **CIDADE:** Cidade.
- **BAIRRO:** Bairro.
- **CEP:** Código Postal.
- **DT_NASCIMENTO:** Data de nascimento (formato `dd/mm/aaaa`).
- **SEXO:** Gênero.
- **EMAIL:** Endereço de e-mail.
- **STATUS_RECEITA_FEDERAL:** Status cadastral na Receita Federal.
- **DT_OBITO:** Data de óbito (quando aplicável).
- **CBO:** Código Brasileiro de Ocupação.
- **QT_VEICULOS:** Quantidade de veículos.
- **RENDA_PRESUMIDA:** Renda presumida.

---

## Visualizações 📈

O projeto apresenta diversos gráficos para explorar os dados:

1. **Top 10 CBO Mais Frequentes - SP**  
   Visualiza os códigos de ocupação mais comuns.

2. **Distribuição de Faixas Salariais em SP**  
   Gráfico de barras que mostra a frequência das faixas salariais.  
   *Dica:* Utilize arredondamento na coluna `RENDA_PRESUMIDA` para agrupar valores semelhantes.

3. **Top 15 CEPs de SP**  
   Destaque para os CEPs com maior frequência, com possibilidade de utilizar barras horizontais para melhor visualização.

4. **Distribuição de Idades**  
   Calcula a idade a partir da data de nascimento e plota um histograma para visualizar a distribuição etária.

5. **Distribuição de Status da Receita Federal 🔴**  
   Gráfico de pizza que apresenta a proporção dos diferentes status cadastrais.

6. **Distribuição por Gênero 🔴**  
   Comparação entre os gêneros utilizando um gráfico de barras.

7. **Distribuição da Quantidade de Veículos 🔴**  
   Histograma que ilustra a frequência da quantidade de veículos por pessoa.

---

## Requisitos ⚙️

Certifique-se de ter as seguintes ferramentas instaladas:

- **Python 3.x**
- [**Pandas**](https://pandas.pydata.org/)
- [**Matplotlib**](https://matplotlib.org/)


## Downloads

- **⚠️ Arquivo completo disponível para download! Clique no link abaixo para acessar: **
- [**🗃️ DOWNLOAD 🗃️**](https://www.mediafire.com/file/nqy5pxfbo12t0r9/sp_data.csv/file)

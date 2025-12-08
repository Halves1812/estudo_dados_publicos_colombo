# 📊 Dados Públicos para Tomada de Decisão
### Um estudo prático de modelagem de dados aplicado ao município de Colombo/PR

Este repositório contém o **código-fonte** desenvolvido no Trabalho de Conclusão de Curso (TCC) de **Hitalo do Carmo Alves** e **Sávio José da Silva**, apresentado ao Instituto Federal do Paraná – Campus Colombo, em 2025.

O projeto tem como objetivo aplicar **modelagem preditiva de séries temporais** sobre dados demográficos do município de Colombo/PR, utilizando bases da Justiça Eleitoral, e disponibilizar os resultados em um **dashboard interativo** no Microsoft Power BI.

---

## 🚀 Objetivos do Projeto
- Construir séries temporais a partir de dados demográficos históricos.  
- Comparar diferentes algoritmos de previsão (ARIMA, SARIMA, Holt-Winters, SES).  
- Implementar um **dashboard interativo** para apoiar a tomada de decisão de gestores públicos e empreendedores.  

---

## 🛠️ Tecnologias Utilizadas
- **Python** (linguagem principal)  
- **Pandas** (manipulação de dados)  
- **PySpark** (processamento distribuído)  
- **Databricks** (ambiente de desenvolvimento)  
- **Microsoft Power BI** (visualização dos resultados)  

---

## 📂 Estrutura do Repositório
- `notebook/` → Jupyter/Databricks notebooks com experimentos.
- `csv/` → Tabela locais de votação.
- `zip/` → Power BI.
- `README.md` → Este documento.  

---

## ⚙️ Como Executar
Aconselhamos a utilização do databricks em sua versão gratuita.
-Clone o notebook no databricks;
-Suba as tabelas extraidas do site do TSE e apontadas no estudo;
  Fote de tabelas TSE: https://sig.tse.jus.br/ords/dwapr/r/seai/sig-eleicao/home
-Suba a tabela "locais de votação";
-Execute o código;
-Extrai a pasta zipada power_bi e descompacte;
-Extraia os resultados da execução do código para o Power BI.


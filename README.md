# Automação de BI e Análise de Performance Empresarial (Python & Pandas)

## 🚀 O Problema de Negócio
Muitas empresas perdem horas de produtividade consolidando manualmente bases de dados de diferentes setores (como Vendas e RH). Esse processo manual é lento, suscetível a erros de digitação e atrasa a geração de indicadores críticos (KPIs) para a tomada de decisão.

## 🛠️ A Solução
Desenvolvi uma solução de **ETL (Extract, Transform, Load)** em Python que automatiza a integração de dados e a geração de relatórios gerenciais. O projeto elimina a necessidade de manipulação manual de planilhas Excel/CSV.

### Principais funcionalidades:
* **Consolidação Automática:** Integração de bases de dados de RH e Vendas através de chaves únicas.
* **Tratamento de Dados:** Limpeza e estruturação de dados brutos utilizando a biblioteca **Pandas**.
* **Cálculo de Indicadores (KPIs):** Faturamento por unidade, Ticket Médio e Produtividade por área.

## 📈 Resultados e Prova Técnica
O script transforma dados brutos em insights visuais instantâneos. Abaixo, um exemplo do gráfico de performance gerado automaticamente pelo sistema, permitindo a análise imediata do faturamento por área de negócio:

![Gráfico de Performance de Vendas]
(![Uploading Captura de tela 2026-04-29 051441.png…])

## 🧰 Stack Técnica
* **Linguagem:** Python
* **Bibliotecas:** * `Pandas`: Manipulação e tratamento de dados.
    * `Matplotlib`: Criação de gráficos e visualização de indicadores.
    * `OS`: Automação de leitura de arquivos do sistema.

---
### 👨‍💻 Como utilizar
1. Certifique-se de ter as bibliotecas instaladas: `pip install pandas matplotlib`.
2. Coloque as bases de dados na pasta do projeto.
3. Execute o script principal para gerar os relatórios e a visualização gráfica.

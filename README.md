# Desafio de Projeto - Explorando IA Generativa em um Pipeline de ETL com Python

Este projeto visa enriquecer dados de clientes com informações personalizadas de investimento. Para isso, utilizamos um pipeline ETL (Extração, Transformação e Carga) para processar dados de clientes, formatar datas e salários e, em seguida, integrar a API do GPT para gerar recomendações de investimento personalizadas.

## Etapas do Projeto

### 1. Extração dos Dados

- Leitura de um arquivo CSV: `dados_clientes.csv`, que contêm informações de IDs e detalhes pessoais dos clientes.

### 2. Transformação dos Dados

- Formatação da coluna de data: Conversão das datas do formato 'yyyy-mm-dd' para 'dd/mm/yyyy'.
- Formatação do campo de salário: Formatação dos valores de salário no estilo "R$ X.XX".

### 3. Integração com a API do GPT

- Configuração da chave de API do GPT para interagir com a IA generativa.
- Geração de opções de investimento personalizadas com base nos IDs dos clientes.

### 4. Carga dos Dados

- Adição das opções de investimento geradas como uma nova coluna no DataFrame dos clientes.

### 5. Saída dos Dados

- Salvamento do DataFrame final em um novo arquivo CSV chamado "clientes_com_investimentos.csv".

## Conclusão

Este projeto demonstra a aplicação bem-sucedida de um pipeline ETL para enriquecimento de dados de clientes com uma IA generativa. Os dados enriquecidos podem ser usados para tomada de decisões de investimento personalizadas e análises futuras.


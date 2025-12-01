# Constru-o-de-Data-Warehouse-e-ETL-com-Apache-Airflow

# AdventureWorks DW & ETL (Airflow)

Descrição do projeto, instruções de execução e estrutura.

## Estrutura
- `dags/` - DAGs do Airflow
- `dags/sql/` - scripts SQL de criação e transformação
- `docs/` - imagens e diagramas
- `Trabalho_DW_ETL.docx` - artigo do trabalho

## Como rodar (rápido)
1. Levante os containers (Docker) do Postgres e do Airflow (conforme seu setup).
2. Configure Connections no Airflow (postgres_dw_connection -> aponta para o DB com AdventureWorks).
3. Coloque os arquivos em `dags/` e aguarde a leitura do Airflow.
4. Trigger no DAG `etl_adventureworks_dw`.

# Analítico / Data Warehouse (OLAP)

Embora tecnicamente seja um serviço de análise, ele é um banco de dados projetado para consultas pesadas em volumes massivos de dados históricos.

- ⭐️ **Amazon Redshift:** O data warehouse em escala de petabytes da AWS. Usado para executar consultas analíticas complexas e gerar relatórios de Business Intelligence (BI) combinando dados do banco de dados com dados do seu Data Lake (S3).
- ⭐️ **Amazon Athena:** É um serviço de consulta interativa *serverless* (sem servidor) que facilita a análise de dados diretamente no **Amazon S3** usando comandos SQL padrão.
    
                 **Caso de Uso Principal:** Executar consultas *ad-hoc* rápidas para analisar logs de rede, arquivos CSV ou JSON que estão "soltos" no seu armazenamento, sem precisar configurar nenhum servidor ou banco de dados prévio.
    
    **Dica para o Exame:** Se a questão mencionar analisar dados **"diretamente no S3"** ou em um **"Data Lake"** usando **"SQL"** sem provisionar infraestrutura, a resposta certa é o Athena. Você paga apenas pela quantidade de dados escaneados por consulta.
    

> • BI / Analytics → Amazon Redshift
>
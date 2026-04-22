# Bancos de Dados em Memória (Caching)

Ideais para acelerar o desempenho lendo dados diretamente da memória (RAM) em vez de discos, fornecendo latência de microssegundos.

- ⭐️ **Amazon ElastiCache:** Serviço gerenciado que permite implantar, operar e escalar armazenamentos de dados na memória. É compatível com Redis e Memcached. Geralmente usado para aliviar a carga de leitura de bancos de dados primários (como o RDS).
- **Amazon MemoryDB:** Um banco de dados na memória durável, compatível com Redis, que oferece armazenamento persistente em várias Zonas de Disponibilidade, além do desempenho ultrarrápido em memória.
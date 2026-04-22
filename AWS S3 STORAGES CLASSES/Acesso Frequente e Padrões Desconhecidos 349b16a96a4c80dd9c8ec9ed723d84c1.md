# Acesso Frequente e Padrões Desconhecidos

- ⭐️ **S3 Standard:** É a classe de armazenamento padrão. Oferece alta durabilidade, disponibilidade e desempenho para dados acessados com frequência, armazenando os dados de forma redundante em no mínimo três Zonas de Disponibilidade (AZs).
- **⭐️ Dica para o Exame:** É a escolha "padrão". Se a questão falar de sites estáticos, distribuição de conteúdo em tempo real, aplicativos móveis ou dados de jogos que precisam de milissegundos de latência o tempo todo, escolha o S3 Standard.
- ⭐️ **S3 Intelligent-Tiering:** Usa aprendizado de máquina para monitorar seus padrões de acesso e mover automaticamente os dados para a camada de armazenamento mais barata (frequente, infrequente ou arquivo) sem impacto no desempenho ou taxas operacionais.
    
    
    > • **⭐️ Dica para o Exame:** A palavra-chave absoluta aqui é "padrões de acesso **desconhecidos**, **imprevisíveis** ou **variáveis**". Se a empresa não sabe com que frequência vai acessar um arquivo amanhã, o Intelligent-Tiering faz o trabalho sujo por eles.
    >
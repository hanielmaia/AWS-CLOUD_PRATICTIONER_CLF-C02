# Acesso Infrequente (Mas com recuperação rápida)

⭐️ **S3 Standard-IA (Infrequent Access):** Para dados acessados com menos frequência, mas que ainda exigem acesso rápido (milissegundos) quando necessários. Tem um custo de armazenamento menor, mas você paga uma pequena taxa por GB recuperado.

⭐️ **S3 One Zone-IA (Infrequent Access):** Tem a mesma latência e taxa de transferência do Standard-IA, mas armazena os dados em **apenas uma** Zona de Disponibilidade, tornando-o 20% mais barato. O risco é que, se a AZ for destruída, os dados são perdidos.

> **⭐️ Dica para o Exame:** Procure por cenários de "backups que são acessados talvez uma vez por mês", ou "arquivos de relatórios mensais". O segredo é: acesso **infrequente**, mas recuperação **imediata**.
> 

> **⭐️ Dica para o Exame:** A prova entrega essa resposta usando palavras como "dados **reproduzíveis**", "dados que podem ser **recriados** facilmente" ou "backups secundários não críticos".
>
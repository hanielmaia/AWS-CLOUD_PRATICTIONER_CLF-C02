# 01 - Zonas de Disponibilidade (Availability Zones - AZs)

⭐️ Uma Zona de Disponibilidade consiste em um ou mais data centers físicos e isolados localizados dentro de uma mesma Região AWS. Elas possuem energia, refrigeração e rede redundantes. As AZs em uma mesma região são separadas por uma distância significativa (dezenas de quilômetros) para garantir que um desastre local (como uma enchente, terremoto ou apagão) não afete mais de uma AZ ao mesmo tempo.

**⭐️ Dica para o Exame: As palavras-chave definitivas são "Alta Disponibilidade" e "Tolerância a Falhas". Se a questão pedir para arquitetar um sistema que não caia caso um data center inteiro seja destruído, a resposta certa é implantar seus recursos em "Múltiplas Zonas de Disponibilidade (Multi-AZ)".**
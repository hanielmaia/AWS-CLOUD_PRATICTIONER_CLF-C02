# Pontos de Presença (Edge Locations / Local Zones)

⭐️ Os Edge Locations são instalações menores da AWS espalhadas por centenas de cidades pelo mundo, muito mais numerosas do que as Regiões. Eles são usados especificamente para armazenar dados em cache nas bordas da rede, servindo como pontos de entrega para serviços como o Amazon CloudFront (CDN) e o Amazon Route 53 (DNS).

**⭐️ Dica para o Exame: Se o cenário focar em entregar vídeos, imagens ou conteúdos para usuários globais com a "menor latência possível", a resposta envolve o uso de Edge Locations através do CloudFront. Lembre-se: você não implanta servidores principais (EC2) em Edge Locations, apenas faz o cache do conteúdo lá.**
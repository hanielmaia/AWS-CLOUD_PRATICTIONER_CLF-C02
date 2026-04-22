# Detecção de Ameaças e Auditoria (Os "Investigadores")

A prova adora tentar te confundir entre o GuardDuty, o Macie e o Inspector. Anote as diferenças exatas:

- ⭐️ **AWS Trusted Advisor:** é uma ferramenta online que atua como seu especialista em nuvem automatizado, inspecionando seu ambiente AWS em tempo real para fornecer recomendações precisas baseadas nas melhores práticas da AWS em cinco pilares: otimização de custos, desempenho, segurança, tolerância a falhas e limites de serviço (quotas).
- ⭐️ **Amazon GuardDuty:** Serviço de detecção de ameaças inteligente. Ele usa Machine Learning para analisar continuamente seus logs de rede e contas em busca de comportamento malicioso. *Palavras-chave: Detecção de ameaças inteligente, Machine Learning, anomalias de rede.*
- ⭐️ **Amazon Inspector:** Serviço de avaliação de vulnerabilidades automatizado. Ele "inspeciona" suas instâncias EC2 e imagens de contêineres buscando falhas de software conhecidas (CVEs) e exposições de rede acidentais. *Palavras-chave: Avaliação de vulnerabilidades, EC2, contêineres, patches ausentes.*
- ⭐️ **Amazon Macie:** Usa inteligência artificial para descobrir e proteger **dados sensíveis** armazenados especificamente no **Amazon S3**. *Palavras-chave: Identificar PII (Informações Pessoalmente Identificáveis), dados de cartão de crédito no S3.*
- ⭐️ **AWS CloudTrail:** É a câmera de segurança da sua conta. Ele registra **todas as chamadas de API** feitas na sua conta. *Palavras-chave: Auditoria de conformidade, histórico de API, "Quem criou essa máquina?", "Quem deletou esse banco de dados?".*
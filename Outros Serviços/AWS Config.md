# AWS Config

⭐️ O AWS Config é um serviço de auditoria e conformidade que atua como o "gravador de histórico" da sua conta. Ele registra continuamente as configurações de todos os seus recursos da AWS e monitora cada mudança feita neles ao longo do tempo. Na prova, ele é a resposta certa sempre que a questão perguntar sobre "como rastrear quem mudou o que", "como auditar se os servidores estão seguindo as regras de segurança da empresa" (compliance) ou "como ver a configuração exata de um recurso em uma data do passado".

💡 **CUIDADO** para não confundir com o AWS CloudTrail!
    - A diferença principal é: o CloudTrail foca na Ação, o Config foca no Resultado.
    - AWS CloudTrail: O foco é a Ação (O "Quem", "Quando" e "De onde").
    - AWS Config: O foco é o Estado/Configuração (O "Como era" e "Como ficou").
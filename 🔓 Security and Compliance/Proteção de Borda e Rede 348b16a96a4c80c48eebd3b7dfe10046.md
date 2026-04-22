# Proteção de Borda e Rede

Como barrar ataques antes que eles cheguem aos seus servidores.

- ⭐️ **AWS WAF (Web Application Firewall):** Protege aplicações web contra exploits comuns da internet (Camada 7). *Palavras-chave: Bloquear Injeção de SQL (SQLi), Cross-Site Scripting (XSS), regras baseadas em IP, filtragem de tráfego HTTP/HTTPS.*
- ⭐️ **AWS Shield:** Serviço de proteção contra ataques DDoS (Negação de Serviço Distribuída).
    - *Standard:* Gratuito, ativado automaticamente para todos os clientes.
    - *Advanced:* Pago, oferece proteção avançada, mitigação 24/7 e reembolso financeiro se um ataque aumentar sua conta.
- **Security Groups vs. NACLs:** (Como já anotamos antes) SG é o firewall da instância (Stateful) e NACL é o firewall da sub-rede (Stateless).
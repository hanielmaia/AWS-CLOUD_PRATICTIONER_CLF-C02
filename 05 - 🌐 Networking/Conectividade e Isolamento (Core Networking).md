# Conectividade e Isolamento (Core Networking)

- **Amazon VPC (Virtual Private Cloud):** Permite provisionar uma seção logicamente isolada da nuvem AWS, onde você pode lançar recursos em uma rede virtual definida por você.
- **Subnets (Públicas e Privadas):** Segmentos de endereços IP na VPC para agrupar recursos com base em necessidades de segurança e acesso.
- **Internet Gateway (IGW):** O componente que permite a comunicação entre instâncias na sua VPC e a internet.
- **NAT Gateway:** Permite que instâncias em subnets privadas se conectem à internet (para atualizações, por exemplo), mas impede que a internet inicie conexões com elas.
- **VPC Peering:** Uma conexão de rede entre duas VPCs que permite rotear o tráfego entre elas usando endereços IP privados.

> 
> 
> 
> ### O que é uma Network ACL (NACL)?
> 
> A Lista de Controle de Acesso à Rede (NACL) é uma camada de segurança opcional para a sua VPC que atua como um **firewall no nível da Sub-rede (Subnet)**. Ela controla o tráfego que entra e sai de uma ou mais sub-redes específicas.
> 
> ### 
>
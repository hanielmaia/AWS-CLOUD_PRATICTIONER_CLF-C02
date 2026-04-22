# Identidade e acesso

O IAM é o coração da segurança da AWS. É global (não fica restrito a uma região) e gratuito.

- ⭐️ **IAM Users (Usuários):** Pessoas ou aplicações reais que precisam acessar o console ou interagir com a AWS.
- **IAM Groups (Grupos):** Coleção de usuários. Facilita atribuir a mesma permissão para várias pessoas (ex: Grupo "Desenvolvedores").
- ⭐️ **IAM Roles (Funções):** Identidades temporárias que não têm credenciais permanentes (senhas). *Caso de Uso:* Dar permissão a uma instância EC2 para acessar um bucket S3, ou para acesso de terceiros/federação.
- ⭐️ **IAM Access Analyzer:** Ferramenta de segurança avançada que monitora e analisa continuamente as políticas da sua conta para identificar quais recursos (como buckets do S3, chaves do KMS ou funções do IAM) estão configurados para permitir acesso a entidades externas ou públicas, ajudando a garantir que o princípio do privilégio mínimo não seja violado por configurações acidentais.
- **IAM Policies (Políticas):** Documentos JSON que definem *o que* pode ser feito. Seguem sempre o **Princípio do Privilégio Mínimo** (dar apenas a permissão estritamente necessária).
- **AWS IAM Identity Center (antigo AWS SSO):** Serviço para gerenciar o acesso de funcionários a várias contas da AWS e aplicativos de negócios com um único login.
- ⭐️  **Amazon Cognito:** Serviço de gerenciamento de identidades voltado para desenvolvedores, permitindo adicionar facilmente recursos escaláveis de cadastro, login e controle de acesso em seus próprios aplicativos web e móveis, suportando nativamente login integrado com provedores sociais (Google, Apple, Facebook) ou corporativos (SAML).

> O [**Princípio do Menor Privilégio](https://www.google.com/search?q=Princ%C3%ADpio+do+Menor+Privil%C3%A9gio&oq=principio+do+menor+&gs_lcrp=EgZjaHJvbWUqBwgBEAAYgAQyBggAEEUYOTIHCAEQABiABDIHCAIQABiABDIHCAMQABiABDIICAQQABgWGB4yCAgFEAAYFhgeMggIBhAAGBYYHjIICAcQABgWGB4yCAgIEAAYFhgeMgoICRAAGAoYFhge0gEINTU0NGowajeoAgCwAgA&sourceid=chrome&ie=UTF-8&ved=2ahUKEwjauv75mfuTAxXLKbkGHVvIHycQgK4QegYIAQgAEAM) (PoLP)** **é uma doutrina de segurança da informação que determina que usuários, sistemas e aplicações devem receber apenas o nível mínimo de acesso e permissões necessário para realizar suas tarefas específicas**. O objetivo é limitar danos por ameaças internas, erros humanos ou contas comprometidas.
>
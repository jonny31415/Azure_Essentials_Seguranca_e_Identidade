# Entendendo sobre Segurança e Identidade na Azure

## Entra ID
- O Entra ID é a ferramente que gerencia os dados de acesso, realizando a autenticação e autorização dos usuários;
- Contas criadas em ambientes *on-premise* podem ser sincronizadas para a nuvem, mas contas criadas diretamente na nuvem não são sincronizadas para um ambiente *on-premise*;
- Contas deletadas são mantidas sem nenhum tipo de privilégio por 30 dias, caso seja necessário recuperar alguma informação. Após esse período, a conta é deletada permanentemente;
- É possível adicionar pessoas de organizaçoes externas para acessar determinados arquivos/serviços;
- É possível verificar logs de acesso, com registros do usuário que efetuou login e o local e data do acesso.

## RBAC (*Role Based Access Control*)
- É possível atribuir permissões para diferentes usuários em diferentes recursos;
- As permissões são hereditárias, ou seja, se existe uma permissão para um usuário em um grupo de recursos, o usuário tem essa mesma permissão para todos os recursos dentro do grupo.

## Microsoft Defender for Cloud
- Aplicação nativa da nuvem;
- É possível avaliar a segurança da Azure, AWS e GCP;
- Sugestões de segurança para melhorar as políticas;

# Segurança 

**Segurança por Usuário**

- **Politicas do IAM**: O usuário deve possuir permissão no IAM para utilizar o S3.

**Segurança por Recursos**
- **Políticas de Bucket:** Regras definidas no próprio bucket para todos os usuários.
- **Lista de Controle de Acesso (ACL) para objetos:** Oferece controle mais granular sobre quem pode acessar objetos individuais dentro de um bucket.
- **S3 Access Points:** Utilizado para definir diferentes permissões para diferentes usuários para o mesmo bucket, utilizados em níveis de seguranças mais complexos.
- **S3 Object Lock:** Permite bloquear objetos contra exclusões/sobescritas de qualquer motivo por tempo determinado.

**Criptografia**
- O S3 permite criptografar objetos utilizando chaves de criptografia.

**Exemplos de segurança**
- Acesso público? Políticas do Bucket
- Usuário da AWS? Permissões do IAM
- Acesso da instancia EC2? IAM Roles
- Acesso de outra conta AWS? Políticas do Bucket
---
**[Voltar](./s3.md)**
# Regras de Lifecycle 
Permite automatizar a transição e exclusão de objetos S3 com base em condições definidas.
### 1 - Transition Actions
Regra que permite mover objetos para diferentes classes com base no tempo, **exemplo:**
- Mover objetos para a classe Standard-IA **60 dias** após a criação.
- Mover objetos para o **Glacier** para arquivamento **após 6 meses**
## 2 - Expiration Actions
Permite excluir objetos com base no tempo, **exemplo:**
- Excluir arquivos de log de acesso **após 365 dias**
- Excluir **versões antigas** de arquivos quando o versionamento estiver habilitado

## Definição de Regras
Você pode criar regras de exclusão ou transição de objetos utilizando critérios:
- Objetos com prefixo especifico.
- Objetos com tags especificas.
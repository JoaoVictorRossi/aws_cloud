# Replicação de dados
Forma de copiar objetos, com o intuito de atender os requisitos, recuperação e otimização de dados.
- O versionamento do bucket deve estar habilitado (source e target bucket).
- Deve possuir
## Replicação Cross-Region Replication (CRR)
Permite replicar objetos de um bucket de uma região para um bucket de outra região da AWS.
- Suporta replicação entre diferentes contas AWS.
- Pode replicar todas as versões dos objetos.
- Suporta filtragem baseadas em tags e prefixos.

## Same-Region Replication (SRR)
Permite replicar objetos de um bucket para outro bucket da mesma região.
- Dentro da **mesma conta** ou entre **contas diferentes.**
- Preserva o versionamento dos objetos.
- Possibilidade de filtrar os objetos que serão replicados.
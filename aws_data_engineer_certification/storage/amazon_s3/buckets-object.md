# Buckets e Objects

## Buckets
Diretórios/pastas para armazenar objetos.
- Buckets deve possui um nome globalmente único.
- São definidos em nível de região (o S3 é um serviço global, mas o bucket é criado dentro de uma região).
- Possibilidade de habilitar o versionamento nos objetos do bucket.
---
# Object
Nada mais é que um arquivo qualquer.
- Todo object possui uma key (o full path do objeto).
    - s3://my-bucket/my_file.txt
    - s3://my-bucket/my_folder1/another_folder/my_file.txt
- A Key é composto por prefixo + nome do objeto:
    - s3://my-bucket/my_folder1/another_folder/my_file.txt
- Um objeto deve possuir no máximo 5TB (mais do que isso deve ser particionado).
- Objetos podem possuir tags para classificação, útil para segurança e lifecycle.
- Se o versionamento do bucket tiver habilitado, os objetos ganham um “Version ID”
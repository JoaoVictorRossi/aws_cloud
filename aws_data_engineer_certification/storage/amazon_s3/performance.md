# Performance S3
O amazon S3 é altamente escalável e pode lidar automaticamente com grandes quantidades de requisições.
**Escalabilidade e Latência**
- Escalabilidade automatica para lidar com alta quantidade de requisições.
- Baixa latência por operação.
## Multi-part Upload
Método que permite dividir um arquivo grande em partições menores e enviadas para o S3 **simultaneamente**, e posteriomente é agrupado em um unico arquivo.
- Se um erro ocorrer durante o upload, somente a parte afetada precisa ser reenviada.
## S3 Transfer Acceleration
Serviço S3 que melhora a velocidade do upload de um objeto utilizando a infraestrutura mais próxima da AWS utilizando o serviço AWS Edge Location.

---
**[Voltar](./s3.md)**
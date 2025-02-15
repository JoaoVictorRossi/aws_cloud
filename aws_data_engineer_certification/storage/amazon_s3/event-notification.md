# S3 Event Notification
Serviço interno do S3 para notificar quando ocorrem eventos especificos dentro do storage, como: criar, excluir ou restaurar.
- O event notificação pode enviar mensagens para outros serviços AWS.
- É possivel filtrar objetos para que os eventos ocorram somente considerando estes objetos.
## Eventos
Eventos representam as ações que podem acionar uma notificação:
- **S3:ObjectCreated:** Quanto um objeto é criado.
- **S3:ObjectRemoved:** Quando um objeto é excluído.
- **S3:ObjectRestore:** Quando um objeto arquivado (Glacier) é restaurado.
- **S3:Replication:** Quando ocorre uma replicação de buckets.
## S3 Event Notification com outros serviços
- Lambda: Event Notification pode acionar uma função lambda depois que um evento ocorrer.
- SQS: Um evento pode ser enviado para a fila SQS, possibilitando um processamento do evento de forma assíncrona.
- SNS: Pode notificar usuários especificos sobre o evento.
- EventBridge: Pode enviar o evento S3 para diversos serviços AWS.
---
**[Voltar](./s3.md)**
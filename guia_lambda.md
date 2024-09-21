# Guia de Uso do AWS Lambda

## Introdução
O AWS Lambda permite executar código sem provisionar ou gerenciar servidores, realizando tarefas em resposta a eventos.

## Como Usar

1. **Criar uma Função Lambda**:
   - Acesse o console do AWS Lambda.
   - Clique em "Create function".
   - Selecione "Author from scratch" e forneça um nome.

2. **Definir o Código**:
   - Insira seu código diretamente no console ou carregue um pacote de implantação.

3. **Configurar Trigger**:
   - Adicione um evento que aciona sua função (ex: S3, DynamoDB, API Gateway).

4. **Configurar Permissões**:
   - A função deve ter as permissões necessárias para acessar outros serviços.

5. **Testar a Função**:
   - Use o painel de testes para simular eventos e verificar o funcionamento.

## Conclusão
O AWS Lambda é ideal para automações e processamento em tempo real, permitindo foco no desenvolvimento sem gerenciar a infraestrutura.

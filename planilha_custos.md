# Planilhas de Estimativa de Custos

## Introdução
Esta planilha ajuda a estimar os custos dos serviços AWS que você pretende usar.

## Principais Componentes de Custo

1. **Amazon EC2**:
   - Tipo de instância
   - Horas de uso
   - Custos de armazenamento

2. **Amazon S3**:
   - Volume de armazenamento
   - Requisições de PUT, GET e LIST
   - Transferência de dados

3. **AWS Lambda**:
   - Número de requisições
   - Tempo de execução

4. **Outros Serviços**:
   - Custos adicionais para serviços como RDS, CloudFront, etc.

## Exemplo de Cálculo

| Serviço          | Descrição            | Custo Estimado |
|------------------|---------------------|-----------------|
| EC2              | Instância t2.micro  | $0.0116/hora    |
| S3               | 100GB Armazenamento | $2.30           |
| Lambda           | 1M requisições      | $0.20           |

## Conclusão
Utilizar esta planilha para planejar e monitorar os custos pode ajudar a otimizar a alocação de recursos e evitar surpresas na fatura da AWS.

# Manual de Configuração do AWS EC2

## Introdução
O Amazon Elastic Compute Cloud (EC2) é um serviço web que fornece capacidade de computação escalável na nuvem. Este manual orienta sobre como configurar instâncias EC2.

## Passos para Configuração

1. **Acesse o Console da AWS**:
   - Faça login em sua conta AWS e acesse o [Console de Gerenciamento da AWS](https://aws.amazon.com/console/).

2. **Inicie o EC2**:
   - No console, procure por "EC2" e clique em "Instâncias".

3. **Lance uma Nova Instância**:
   - Clique em "Launch Instance".
   - Selecione uma Amazon Machine Image (AMI) que atenda suas necessidades.

4. **Escolha um Tipo de Instância**:
   - Selecione o tipo de instância (ex: t2.micro para uso gratuito).

5. **Configurações de Rede**:
   - Configure as opções de rede e sub-rede.

6. **Armazenamento**:
   - Defina o armazenamento de volumes EBS.

7. **Configurar Grupo de Segurança**:
   - Adicione regras para permitir o tráfego desejado (ex: SSH, HTTP).

8. **Revise e Lance**:
   - Revise suas configurações e clique em "Launch".

9. **Acesse sua Instância**:
   - Use SSH para acessar sua instância, utilizando a chave privada que você criou.

## Conclusão
A instância EC2 está agora em funcionamento. Você pode gerenciá-la através do console ou usando a AWS CLI.

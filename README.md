# AWS CloudFormation

É um processo que auxilia na automação de criação de recurso na AWS por meio de templates JSON ou YAML.
Podemos utilizar os templates quantas vezes quisermos e pagamos apenas pelas stacks cridas(conjunto de recursos, ex: EC2, RDS, S3 etc).
Além de ser um processo automatizado, conseguimos versionar estes templates. Com ele podemos criar desde um recurso simples como um EC2 até uma Arquitetura robusta com vários recursos. 

1. Define o template
2. Executa no CloudFormation
3. Tem a stack criada

## Criando stacks no AWS CloudFormation

- Acessar o serviço CloudFormation na AWS.
- Create stack
- Escolha o template, na AWS tem várias amostras, mas pode colocar um template próprio já pronto, inserindo a fonte desse template(URL, arquivo, repositório).
- Colocar um nome para a stack e parâmetros se tiver

Facilita na criação de recursos, economiza tempo, pois no lugar de fazer um por um manualmente, usando esse serviço pode ser automatizado. 

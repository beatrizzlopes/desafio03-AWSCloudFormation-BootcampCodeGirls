# desafio03-AWSCloudFormation-BootcampCodeGirls

# Introdução

Este repositório possui o desafio implementar sua primeira Stack com AWS CloudFormation, minhas anotações e insights adquiridos durante as aulas e o desafio do bootcamp Santander Code Girls com a DIO, focado em computação em nuvem com AWS.

# Objetivo do desafio

Repositório organizado contendo anotações e insights adquiridos durante a prática.

# Material Presente no repositório

README.md: Explicação de qual é o desafio, anotações e insights adquiridos durante as aulas e o desafio.

anotações extras: Contém anotações.

# Anotações

### O que é CloudFormation

O AWS CloudFormation é um serviço da Amazon Web Services (AWS) que permite criar, configurar e gerenciar recursos da AWS automaticamente, usando código.

Em outras palavras: Em vez de criar manualmente recursos como instâncias EC2, buckets S3 ou bancos de dados RDS pelo console, você escreve um arquivo de configuração (em YAML ou JSON), chamado de template e o CloudFormation monta toda a infraestrutura pra você.

### Vantagens CloudFormation

* Infraestrutura como código (IaC): tudo é reproduzível e versionado.
* Automação: elimina tarefas manuais e reduz erros.
* Gerenciamento simplificado: permite atualizar e excluir recursos em conjunto.
* Integração com outros serviços AWS: como EC2, S3, RDS, IAM, Lambda, VPC, entre outros.

# Insights

### A importância da stack com firewall

Durante o processo pude perceber que a segurança na nuvem é construída em camadas, Cada uma dessas camadas tem um papel fundamendal. 
Uma que se descatou entre elas foi stack com firewall, pois enquanto uma stack comum apenas cria os recursos  principais, a stack com
firewall adiciona camadas extras de proteção.

### Escalabilidade com segurança 

Também percebi que infraestrutura automatizada permite crescer sem comprometer a proteção, isso é escalabilidade com segurança.

# Autora
Beatriz Lopes

# Referência

https://web.dio.me/track/santander-code-girls-2025

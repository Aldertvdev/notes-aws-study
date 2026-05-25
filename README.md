# 01 - Introdução à AWS

**Data:** 25/05/2026  
**Curso:** AWS Cloud Practitioner Essentials

## Objetivos do módulo
- Entender o que é AWS e o modelo de computação em nuvem
- Conhecer os principais benefícios da nuvem
- Entender os 6 pilares do Well-Architected Framework

## O que é AWS?
- Amazon Web Services
- Plataforma de nuvem mais utilizada do mundo
- Mais de 200 serviços disponíveis

## Modelos de Computação em Nuvem
- **On-Premises** (servidores próprios)
- **IaaS** (Infrastructure as a Service)
- **PaaS** (Platform as a Service)
- **SaaS** (Software as a Service)

## Vantagens da Nuvem AWS
- Agilidade
- Elasticidade
- Pay-as-you-go (pague pelo que usar)
- Escalabilidade
- Confiabilidade

## Principais Regiões e Zonas de Disponibilidade
- Regiões (ex: sa-east-1 = São Paulo)
- Zonas de Disponibilidade (AZs)

## Anotações importantes


## Próximos passos
- Continuar para o módulo de IAM

# 02 - Conceitos Básicos de Cloud Computing

**Data:** 25/05/2026  
**Curso:** AWS Cloud Practitioner Essentials

## Modelos de Implantação
- Cloud (Nuvem)
- On-Premises
- Hybrid (Híbrido)

## Modelos de Serviço
- **IaaS** – Ex: EC2
- **PaaS** – Ex: Elastic Beanstalk
- **SaaS** – Ex: Gmail, Dropbox

## Responsabilidade Compartilhada
- AWS: segurança da nuvem
- Cliente: segurança na nuvem

## Vantagens da Nuvem
- Alta disponibilidade
- Escalabilidade
- Economia de custo
- Velocidade de inovação

## Desafios da Nuvem
- Segurança
- Custos não controlados
- Conformidade

## Anotações / Dúvidas

# 03 - Computação (EC2 e Lambda)

**Data:** 25/05/2026  
**Curso:** AWS Cloud Practitioner Essentials

## Amazon EC2
- Servidores virtuais na nuvem
- Tipos de instâncias (t3, m5, etc)
- Preços: On-Demand, Reserved, Spot

## Amazon Lambda
- Serverless computing
- Executa código sem gerenciar servidores
- Paga por milissegundo de execução

## Comparação EC2 x Lambda

| Aspecto          | EC2                  | Lambda                  |
|------------------|----------------------|-------------------------|
| Gerenciamento    | Alta                 | Quase zero              |
| Escalabilidade   | Manual/Auto Scaling  | Automática              |
| Tempo de execução| Contínuo             | Até 15 minutos          |
| Caso de uso      | Aplicações longas    | Eventos, APIs, triggers |

## Outros serviços de computação
- ECS / EKS (containers)
- Fargate

## Anotações importantes

# 04 - Armazenamento (S3)

**Data:** 25/05/2026  
**Curso:** AWS Cloud Practitioner Essentials

## Amazon S3
- Simple Storage Service
- Armazenamento de objetos
- Alta durabilidade (99.999999999%)

## Principais recursos
- Buckets
- Versionamento
- Políticas de acesso
- Classes de armazenamento (Standard, Intelligent-Tiering, Glacier)

## Casos de uso
- Hospedagem de sites estáticos
- Backup
- Data Lake
- Arquivos de mídia

## S3 vs EBS vs EFS

| Serviço | Tipo           | Uso principal             |
|---------|----------------|---------------------------|
| S3      | Objetos        | Arquivos, backup          |
| EBS     | Blocos         | Volumes para EC2          |
| EFS     | Sistema de arquivos | Compartilhado entre EC2 |

## Anotações

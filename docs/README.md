[![English](https://img.shields.io/badge/English-blue.svg)](README.en.md)
[![Português](https://img.shields.io/badge/Português-green.svg)](README.md)

# Meus Desafios de Programação UOL

Bem-vindo! Este repositório documenta os projetos que desenvolvi para os desafios da UOL, com foco em DevOps e Cloud.

## 🚀 Projetos Concluídos

### 1. Projeto UOL 01: Servidor Web com Monitoramento na AWS

Configuração de um servidor web Nginx na AWS com um script de monitoramento que envia alertas de falha para o Discord.

- **🛠️ Tecnologias:** AWS (EC2, VPC), Nginx, Bash Script, Cron.

- **Destaques:**
    - Infraestrutura de rede (VPC) e servidor (EC2) configurados na AWS.
    - Script em Bash que verifica a saúde do servidor a cada minuto via Cron.
    - Notificações automáticas de indisponibilidade enviadas para um webhook do Discord.

### 2. Projeto UOL 02: Infraestrutura Escalável para WordPress com Docker na AWS

Criação de uma infraestrutura de alta disponibilidade e autoescalável na AWS para hospedar uma aplicação WordPress em containers Docker.

- **🛠️ Tecnologias:** AWS (EC2, VPC, RDS, EFS, ALB, ASG), Docker, WordPress, CloudFormation.

- **Destaques:**
    - Arquitetura resiliente com Load Balancer (ALB) e Auto Scaling Group (ASG).
    - Dados persistidos em um banco de dados gerenciado (RDS) e arquivos compartilhados em um sistema de arquivos elástico (EFS).
    - Provisionamento automatizado da infraestrutura com CloudFormation e User Data.

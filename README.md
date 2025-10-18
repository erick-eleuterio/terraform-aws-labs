# Laboratório: Criação de VPC AWS com Terraform

> Este projeto demonstra, de forma prática e didática, como automatizar a criação de uma Virtual Private Cloud (VPC) na AWS utilizando infraestrutura como código com Terraform. Todo o processo é orientado para iniciantes e também para profissionais que querem aprofundar a organização de ambientes Cloud modernas.

---

## ✨ Objetivo do projeto

- Automatizar a criação de uma VPC na AWS, preparando o ambiente para deploy seguro e escalável de aplicações ou outros serviços na nuvem.
- Demonstrar as melhores práticas de escrita, documentação e versionamento de código IaC.
- Ajudar recrutadores e times técnicos a entenderem minha evolução prática em Cloud.

---

## 🚦 O que é uma VPC?

A VPC (Virtual Private Cloud) é uma rede privada, isolada dentro da AWS, onde você organiza subnets, rotas, gateways e recursos como EC2 e bancos de dados. É a base para qualquer arquitetura segura e escalável em nuvem.

---

## 🛠️ Recursos criados pelo Terraform

- **VPC** com bloco CIDR customizável
- **Subnets** públicas e privadas
- **Internet Gateway** (IGW) para saída à Internet
- **Route Tables** para roteamento
- **Tags** para organização de recursos

---

## 📋 Pré-requisitos

- Conta AWS com credenciais IAM válidas
- Terraform instalado ([guia oficial](https://www.terraform.io/downloads.html))
- AWS CLI instalado e configurado
- Git instalado e repositório iniciado

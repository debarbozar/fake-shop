# Deploy de Aplicação Web em AWS EKS com CI/CD, Monitoramento e Grafana/Prometheus

Este repositório contém o processo de containerização de uma aplicação web existente, configuração de CI/CD para deploy automático no **Amazon EKS** (Elastic Kubernetes Service), e integração de monitoramento com **Prometheus** e **Grafana**. O objetivo deste projeto é criar uma solução escalável e monitorada para aplicações na nuvem, utilizando as melhores práticas de DevOps e infraestrutura como código.

## Tecnologias Utilizadas

- **Docker**: Para containerizar a aplicação.
- **Amazon EKS (Elastic Kubernetes Service)**: Para orquestrar e escalar os containers da aplicação.
- **GitHub Actions**: Para automação do pipeline de CI/CD.
- **Amazon ECR (Elastic Container Registry)**: Para armazenar as imagens Docker.
- **Prometheus**: Para coletar métricas da aplicação.
- **Grafana**: Para visualização e monitoramento das métricas coletadas pelo Prometheus.

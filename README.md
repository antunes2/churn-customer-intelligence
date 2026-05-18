# Customer Intelligence Platform

Projeto de Data Science end-to-end focado em inteligência de clientes utilizando dados reais de e-commerce brasileiro.

Objetivo: construir uma plataforma capaz de prever churn, estimar Lifetime Value (LTV), segmentar clientes e validar intervenções através de experimentação estatística.

---

## Problemas de negócio

Este projeto busca responder perguntas como:

- quais clientes possuem maior risco de churn?
- quanto cada cliente vale ao longo do tempo?
- quais segmentos merecem investimento?
- campanhas realmente funcionam?

---

## Dataset

Dataset utilizado:

Brazilian E-Commerce Public Dataset by Olist

Contém aproximadamente:

- ~100k pedidos
- múltiplas tabelas relacionais
- clientes
- pagamentos
- avaliações
- produtos
- vendedores

---

## Stack

### Dados

- Python
- Pandas
- PostgreSQL
- SQLAlchemy

### Machine Learning

- Scikit-learn
- XGBoost
- Lifetimes

### API

- FastAPI

### Dashboard

- Streamlit

### Infra

- Docker
- uv
- GitHub Actions

---

## Estrutura

(ver estrutura de diretórios)

---

## Roadmap

### Setup

- [ ] configurar ambiente
- [ ] baixar dataset
- [ ] configurar PostgreSQL
- [ ] ingestão inicial

### ETL

- [ ] criar schema raw
- [ ] validar dados
- [ ] pipeline idempotente

### Features

- [ ] customer master table
- [ ] RFM
- [ ] churn target

### Modelagem

- [ ] churn
- [ ] LTV
- [ ] clustering

### Produto

- [ ] API
- [ ] dashboard
- [ ] CI/CD

---

## Como rodar

Criar ambiente:

```bash
uv sync
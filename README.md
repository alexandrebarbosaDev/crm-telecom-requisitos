# crm-telecom-requisitos
Documentação de Engenharia de Software e Metodologias Ágeis para um sistema de CRM corporativo
# Engenharia de Requisitos: CRM Inteligente para Telecomunicações 📱💼

Este repositório contém a documentação técnica completa de engenharia de software e gestão ágil para o desenvolvimento de um sistema de CRM (Customer Relationship Management) customizado para grandes operadoras. O projeto une os conceitos teóricos do meu tecnólogo em ADS com a minha vivência prática de mais de 14 anos na área comercial (Nextel, Oi e Vivo).

---

### 🎯 Visão Geral do Produto (O Escopo)

Consultores de vendas em operadoras frequentemente lidam com múltiplos sistemas legados para consultar históricos, metas e ofertas, gerando lentidão no atendimento ao cliente B2B/B2C. Este CRM centraliza a jornada do cliente, otimiza a tomada de decisão do consultor na ponta e garante a conformidade com as regras da LGPD (Lei Geral de Proteção de Dados).

---

### 🏃‍♂️ Abordagem Ágil (Gestão com Scrum)

O desenvolvimento deste software foi planejado utilizando frameworks ágeis para garantir entregas iterativas e de valor rápido para o negócio.

- **Papel Executado:** Product Owner (PO) / Analista de Sistemas
- **Artefatos Produzidos:** Product Backlog, Histórias de Usuário (User Stories) e Matriz de Rastreabilidade.

---

### 📋 Requisitos do Sistema

#### 1. Requisitos Funcionais (RF)
- **RF-001:** O sistema deve permitir que o consultor visualize o consumo médio de dados do cliente nos últimos 3 meses na tela de atendimento.
- **RF-002:** O sistema deve gerar alertas automáticos de ofertas de upgrade (como planos Fibra ou Pós-Pago) com base no perfil de uso do cliente.
- **RF-003:** O sistema deve registrar o histórico completo de interações comerciais de contas corporativas (B2B).

#### 2. Requisitos Não-Funcionais (RNF)
- **RNF-001:** Segurança: Todos os dados confidenciais dos clientes devem ser criptografados em repouso de acordo com a LGPD.
- **RNF-002:** Desempenho: A tela de consulta do perfil do cliente não deve demorar mais do que 2 segundos para carregar.

---

### 📂 Estrutura de Arquivos deste Repositório

- [`/backlog_historias_usuario.md`](backlog_historias_usuario.md): Detalhamento do Product Backlog com histórias de usuário, critérios de aceitação e priorização.
- [`/diagrama_casos_uso.md`](diagrama_casos_uso.md): Mapeamento de atores e interações do sistema utilizando a notação UML.

# Product Backlog & Histórias de Usuário (User Stories) 🏃‍♂️

Este documento detalha o Product Backlog do CRM de Telecomunicações, estruturado com foco em gerar o máximo valor para a operação comercial na ponta, mantendo a clareza técnica necessária para o time de desenvolvimento.

---

### 🗺️ Priorização do Backlog (Técnica MoSCoW)

As funcionalidades do sistema foram priorizadas estrategicamente com base no impacto direto nos resultados de vendas e na experiência do consultor:

- **Must Have (Essencial):** Consulta de perfil de uso do cliente e registro de interações B2B.
- **Should Have (Importante):** Motor de recomendação automática de upgrades de planos.
- **Could Have (Desejável):** Dashboard de acompanhamento de metas para o consultor.
- **Won't Have (Fica para o futuro):** Aplicativo mobile nativo para o cliente final.

---

### 📑 Histórias de Usuário (User Stories)

Aqui estão os itens mapeados para a primeira Sprint do projeto:

#### US-01: Visão 360º do Consumo do Cliente (Must Have)
- **Como** Consultor de Negócios na ponta da operação,
- **Eu quero** visualizar de forma clara o perfil de consumo de dados e serviços do cliente nos últimos 3 meses,
- **Para que eu possa** oferecer um plano perfeitamente alinhado com a real necessidade dele, evitando churn (cancelamento).

**Critérios de Aceitação:**
- [ ] O sistema deve cruzar dados de consumo de telefonia móvel e banda larga fixa na mesma tela.
- [ ] O tempo máximo de carregamento desses dados não pode ultrapassar 2 segundos.
- [ ] Caso o cliente não possua um dos serviços (ex: não tem Fibra), deve exibir um indicador visual de oportunidade de cross-selling.

---

#### US-02: Motor de Ofertas e Upgrades Automatizados (Should Have)
- **Como** Especialista em Vendas Sênior,
- **Eu quero** que o sistema me dê sugestões automáticas de upgrades (Pós-pago ou Fibra de maior velocidade) baseadas na análise de dados do cliente,
- **Para que eu possa** aumentar o ticket médio da venda de forma consultiva e assertiva.

**Critérios de Aceitação:**
- [ ] O motor do sistema deve sugerir um plano superior se o cliente atingiu 90% da franquia de dados nos últimos 2 meses seguidos.
- [ ] A tela deve mostrar o argumento de vendas chave para aquela oferta (ex: *"Cliente elegível a desconto de R$20 no combo"*).
- [ ] Deve existir um botão direto para iniciar a migração do plano sugerido com apenas um clique.

---

#### US-03: Registro de Negociações Corporativas (B2B) (Must Have)
- **Como** Coordenador Comercial de Atacado,
- **Eu quero** registrar o histórico de reuniões, propostas enviadas e status da negociação de grandes contas,
- **Para que o time** tenha rastreabilidade completa e consistência no processo de funil de vendas corporativo.

**Critérios de Aceitação:**
- [ ] O sistema deve permitir anexar propostas comerciais em formatos como PDF ou planilhas.
- [ ] Deve possuir um campo de status com as opções: *Prospecção, Proposta Enviada, Em Negociação, Ganho ou Perdido*.
- [ ] Sempre que o status mudar para "Ganho", um e-mail de notificação deve ser enviado automaticamente para o setor de ativação de contratos.

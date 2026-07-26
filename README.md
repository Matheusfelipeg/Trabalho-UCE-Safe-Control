<h1 align="center">
🦺 SafeControl
</h1>

<p align="center">
Plataforma desenvolvida para otimizar a gestão de Equipamentos de Proteção Individual (EPIs), integrando banco de dados e Power BI para acompanhamento de indicadores em tempo real.
</p>

<p align="center">

<!-- Coloque aqui as badges se quiser -->

<img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black">
<img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white">
<img src="https://img.shields.io/badge/Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
<img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">

</p>

---

# 📖 Sobre o Projeto

O **SafeControl** foi desenvolvido para solucionar uma demanda real da indústria relacionada à gestão de Equipamentos de Proteção Individual (EPIs).

O desafio consistia em reduzir atrasos na troca dos equipamentos, melhorar o controle das entregas e disponibilizar informações estratégicas para apoiar a tomada de decisão do setor de Segurança do Trabalho.

Como solução foi desenvolvida uma plataforma integrada que centraliza o cadastro das informações e disponibiliza um **Dashboard Power BI conectado ao banco de dados**, permitindo o acompanhamento dos principais indicadores operacionais.

---

<p align="center">

<a href="https://matheusfelipeg.github.io/Trabalho-UCE-Safe-Control/principal.html?usuario=admin%40safectrl.com&senha=ADSDA">
<img src="https://img.shields.io/badge/Acessar%20Projeto-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white">
</a>

</p>

> **Observação:** Como o projeto está hospedado no GitHub Pages, a autenticação foi simplificada para fins de demonstração. O link acima realiza o acesso automaticamente ao ambiente de testes.

---

# 🎯 Problema

O processo existente apresentava diversas dificuldades:

✔ Cadastro manual de EPIs

✔ Dificuldade para identificar equipamentos vencidos

✔ Falta de indicadores

✔ Controle ineficiente do estoque

✔ Demora nas entregas

✔ Alto risco de utilização de EPIs vencidos

---

# 💡 Solução

A plataforma centraliza todas as informações em um único sistema.

Entre as principais funcionalidades estão:

- Cadastro de Funcionários
- Cadastro de EPIs
- Registro de Entregas
- Registro de Compras
- Dashboard Power BI
- Banco de Dados Integrado

---

# 📈 Fluxo da Informação

```text
Funcionários
      │
      ▼
Cadastro de EPIs
      │
      ▼
Registro de Compras
      │
      ▼
Registro de Entregas
      │
      ▼
Banco de Dados
      │
      ▼
Power BI
      │
      ▼
Dashboard e Indicadores
```

---

# 📊 Dashboard Power BI

O principal diferencial do projeto é o painel analítico desenvolvido no Power BI.

Os dados registrados na plataforma alimentam automaticamente o banco de dados e são utilizados para gerar indicadores gerenciais que apoiam a tomada de decisão.

## Indicadores

- Total de funcionários
- Total de EPIs cadastrados
- Equipamentos vencidos
- Equipamentos próximos do vencimento
- Controle de estoque
- Histórico de entregas
- Distribuição por setor
- Indicadores operacionais

---

<h2 align="center">
Dashboard
</h2>

<p align="center">

<!-- COLOCAR PRINT -->

<img src="images/dashboard.png" width="100%">

</p>

---

# 🗄 Banco de Dados

Toda a plataforma foi desenvolvida utilizando um banco de dados relacional responsável por armazenar todas as informações do sistema.

Os registros são utilizados tanto pela aplicação quanto pelo Dashboard Power BI.

Benefícios:

- Centralização das informações
- Integridade dos dados
- Atualização dos indicadores
- Consulta rápida
- Integração com Business Intelligence

---

<h2 align="center">
Modelo de Dados
</h2>

<p align="center">

<!-- INSERIR DER OU MER -->

<img src="images/modelagem.png" width="90%">

</p>

---

# 👨‍💼 Cadastro de Funcionários

Módulo responsável pelo gerenciamento dos colaboradores.

Campos cadastrados:

- Nome
- CPF
- Cargo
- Setor
- Data de Admissão

---

<h2 align="center">
Cadastro de Funcionários
</h2>

<p align="center">

<img src="images/funcionarios.png" width="90%">

</p>

---

# 🦺 Cadastro de EPIs

Permite realizar o gerenciamento completo dos equipamentos.

Informações cadastradas:

- Nome do EPI
- Certificado de Aprovação (CA)
- Validade
- Estoque Mínimo

---

<h2 align="center">
Cadastro de EPIs
</h2>

<p align="center">

<img src="images/cadastro_epi.png" width="90%">

</p>

---

# 📦 Cadastro de Compras

Responsável pelo controle dos lotes de equipamentos.

Campos:

- Número do lote
- Data de fabricação
- Data de validade
- Quantidade

---

<h2 align="center">
Cadastro de Compras
</h2>

<p align="center">

<img src="images/compras.png" width="90%">

</p>

---

# 📋 Registro de Entregas

Permite registrar cada entrega realizada aos colaboradores.

Dados registrados:

- Funcionário
- EPI
- Quantidade
- Data
- Observação

Esses registros alimentam automaticamente o Dashboard Power BI.

---

<h2 align="center">
Registro de Entregas
</h2>

<p align="center">

<img src="images/entregas.png" width="90%">

</p>

---

# 🛠 Tecnologias Utilizadas

- Power BI
- SQL
- Banco de Dados Relacional
- HTML
- CSS
- JavaScript
- Bootstrap

---

# 📊 Competências Demonstradas

Este projeto evidencia competências voltadas para a área de Dados e Business Intelligence.

- Modelagem de Dados
- Banco de Dados Relacional
- SQL
- Business Intelligence
- Power BI
- Desenvolvimento de Dashboards
- Construção de KPIs
- Integração entre Sistema e Banco de Dados
- Organização de Dados Operacionais
- Visualização de Dados
- Suporte à Tomada de Decisão

---

# 👨‍💻 Autor

**Matheus Felipe Gonçalves de Souza**

Projeto desenvolvido como solução para uma demanda real da indústria, aplicando conceitos de Banco de Dados, Business Intelligence e Desenvolvimento de Sistemas para otimizar o gerenciamento de Equipamentos de Proteção Individual.

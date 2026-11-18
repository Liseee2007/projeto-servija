# 🤝 ServiJá — Protótipo Interativo Multiusuário

> **"Conectando quem precisa a quem sabe fazer."**  
> O jeito mais fácil, rápido e seguro de contratar serviços residenciais e encontrar oportunidades de trabalho.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)

🔗 **Acesse o Protótipo Interativo Online:** [Clique aqui para testar no navegador](https://liseee2007.github.io/projeto-servija/)  
📊 **Apresentação do Projeto (Slides):** [Visualizar no Canva](https://canva.link/s9ctevysp3vkh0x)

---

## ✿ Sobre o Projeto

O **ServiJá** é um protótipo de alta fidelidade desenvolvido para a disciplina de **Desenvolvimento de Interfaces** do curso de **Ciência da Computação** no **Centro Universitário de Brasília (CEUB)** (2026).

A aplicação simula um ecossistema mobile completo (com alternância entre visualização em *frame* de smartphone e expansão total) e possui arquitetura **multiusuário**, permitindo alternar em tempo real entre três perfis distintos: **Cliente**, **Prestador de Serviços** e **Administrador**.

---

## ✿ Processo de Design Thinking

O desenvolvimento da interface foi guiado pelas etapas do Design Thinking:

1. **Empatia:** Identificação das principais dores de clientes (urgência em imprevistos, insegurança ao contratar desconhecidos, falta de transparência nos preços) e de prestadores (dificuldade em captar clientes próximos e organizar a agenda).
2. **Definição:** Criação de uma plataforma única que centraliza solicitação, comparação de propostas, comunicação direta e gestão de atendimentos.
3. **Ideação:** Definição de funcionalidades-chave, incluindo chamados de emergência (SOS) e filtros de preferência para maior segurança.
4. **Prototipação:** Interface intuitiva com identidade visual diferenciada por perfil (azul para Cliente, verde para Prestador, índigo para Admin e vermelho para alertas de emergência).
5. **Testes & Refinamento:** Planejamento de testes de usabilidade focados no fluxo *Solicitação → Propostas → Perfil → Chat → Contratação*.

---

## ✿ Funcionalidades por Perfil

### ✿ Visão Cliente
* **Serviço de Emergência (SOS 24h):** Atalho em destaque para situações críticas (ex.: vazamentos ou curtos-circuitos) com prioridade visual e atendimento imediato.
* **Solicitação Personalizada:** Escolha de categorias (Elétrica, Hidráulica, Pintura, Limpeza, Montagem, etc.), descrição, data, turno e orçamento estimado.
* **Comparação de Propostas & Filtro Feminino:** Visualização de valores, distância, avaliações e opção de filtrar exclusivamente por **prestadoras mulheres**.
* **Chat Integrado:** Comunicação direta com o profissional, incluindo suporte a envio de imagens.

### ✿ Visão Prestador
* **Status Online/Offline:** Controle de disponibilidade em tempo real.
* **Radar de Oportunidades:** Listagem de chamados abertos em um raio de 10 km, com destaque para emergências e envio rápido de orçamentos.
* **Agenda de Serviços:** Organização de atendimentos confirmados e concluídos com atalho para chat e rota no GPS.

### ✿ Painel Administrativo
* **Indicadores (KPIs):** Acompanhamento de total de solicitações, prestadores verificados, faturamento (GMV) e índice de satisfação.
* **Gráficos Dinâmicos:** Evolução mensal do volume de serviços (via *Chart.js*) e monitoramento de chamados em tempo real.

---

## ✿ Como Executar Localmente

Como o projeto não depende de etapas de build ou instalação de pacotes:

1. Clone este repositório:
   ```bash
   git clone [https://github.com/liseee2007/projeto-servija.git](https://github.com/liseee2007/projeto-servija.git)

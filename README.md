# Oi, eu sou o Juan

**Desenvolvedor Full Stack · .NET · Arquitetura de Software · IA & Automação**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/jverass)
![Rio de Janeiro](https://img.shields.io/badge/Rio%20de%20Janeiro-242428?style=flat-square)

Trabalho na VVS Sistemas como desenvolvedor back-end de uma linha de sistemas corporativos em produção. Atuo com ERP, CRM, WMS e uma plataforma de atendimento omnichannel, trabalhando do banco à interface: .NET e PostgreSQL no servidor, React e Next.js no front, além de Angular, WPF, MAUI e Flutter em sistemas existentes.

Fora do trabalho, desenvolvo projetos voltados a **arquitetura de software, produtos SaaS, automação e agentes de IA aplicados ao desenvolvimento**.

## O que estou construindo no momento

### 🤖 [D.A.N.T.E.](https://github.com/juanverass/dante)

**Distributed Agent Network for Task Execution**

Orquestrador local para desenvolvimento assistido por IA. O projeto conecta agentes e ferramentas como Claude Code, Codex CLI, GitHub e Telegram para executar tarefas reais de engenharia de software.

A proposta é automatizar um fluxo que envolve **issues → agentes → branches/worktrees → implementação → PR → revisão**, mantendo contexto, histórico de decisões e regras específicas de cada projeto.

### 🏋️ Produto SaaS para o segmento fitness

Também trabalho na construção de um produto SaaS real para o segmento fitness, atualmente mantido em repositório privado.

É um projeto que utilizo para aplicar, em contexto de produto, conceitos como:

- .NET e APIs REST;
- arquitetura de software;
- multitenancy;
- autorização e permissões;
- PostgreSQL e EF Core;
- testes automatizados;
- CI e fluxo de desenvolvimento baseado em issues e pull requests.

Por envolver um produto real e contexto de cliente, detalhes de domínio, código e implementação permanecem privados.

### 🎓 [Projeto acadêmico Web](https://github.com/juanverass/projeto-ong-html5)

Projeto desenvolvido durante a graduação e evoluído ao longo das experiências práticas da disciplina.

O repositório reúne estudos e implementação de:

- HTML5 semântico e acessibilidade;
- CSS3, Design System, Grid e Flexbox;
- responsividade e estados de interface;
- JavaScript e manipulação do DOM;
- deploy e integração contínua.

### 🏠 Homelab

Infraestrutura self-hosted usada como ambiente de desenvolvimento e laboratório para automações e IA, com WSL2, Docker, PostgreSQL, Redis, RabbitMQ, n8n e Tailscale.

## Stack

**Back-end**

![.NET](https://img.shields.io/badge/.NET%206--10-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-5C2D91?style=flat-square&logo=dotnet&logoColor=white)
![EF Core](https://img.shields.io/badge/Entity%20Framework%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)

**Front-end e mobile**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![WPF / MAUI](https://img.shields.io/badge/WPF%20%2F%20MAUI-512BD4?style=flat-square&logo=dotnet&logoColor=white)

**Dados**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)

**Infraestrutura, mensageria e automação**

![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white)

**IA aplicada ao desenvolvimento**

![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/Codex-000000?style=flat-square&logo=openai&logoColor=white)

## Sobre o código que não está aqui

Quase tudo que construí profissionalmente é proprietário. Não posso publicar o código, mas posso falar do que ele resolve.

**Busca de atendimentos: ~20 segundos → milissegundos.** A consulta fazia varredura sequencial em uma tabela de alto volume. Reescrevi a estratégia de acesso com índices B-tree e GIN usando `pg_trgm` no PostgreSQL, ajustando as queries ao plano de execução real.

**Listagem de saídas do ERP: ~10 segundos → milissegundos.** Mesmo tipo de problema, contexto diferente: reescrita das queries e indexação adequada sobre um volume que só cresce.

**Integração entre o ERP e plataformas de e-commerce.** Construí a integração do ERP com Tray, WooCommerce, Bling, iFood, Magalu, Wake, SkyHub (Americanas) e Shopee: envio e atualização de produtos, sincronização de estoque e entrada de pedidos e vendas de volta no ERP. Oito plataformas, cada uma com API e modelo de dados próprios, sincronizando nos dois sentidos contra a mesma base.

**Telas e módulos em quatro stacks de front-end.**

- **CRM, em Angular:** módulos de Justificativas, Departamentos, Contatos e Tags, entre outros.
- **CPlus 5 (ERP), em WPF:** mais de 30 telas construídas do zero, cobrindo anúncios, comércio eletrônico, antecipação de recebíveis e localização de produtos, usadas diariamente pelos clientes da VVS.
- **WMS Mobile, em MAUI:** inventário de produto, etiqueta de recebimento, consulta de posição de estoque e de posições disponíveis, carregamentos e abastecimento em picking.
- **Dashboard Mobile, em Flutter:** tela de login, dashboard e componentização de widgets.

**Microsserviços internos.** Respondo pelos serviços internos que sustentam os produtos da VVS, atuando em manutenção, correções em produção e evolução contínua.

Esses casos resumem bem o trabalho que faço: **resolver problemas de software em produção e transformar o aprendizado em projetos que posso construir em público.**

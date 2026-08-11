# Juan Veras

**Desenvolvedor Full Stack · 7 anos de experiência**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/jverass)
![Rio de Janeiro](https://img.shields.io/badge/Rio%20de%20Janeiro-242428?style=flat-square)

Trabalho na VVS Sistemas como desenvolvedor back-end de uma linha de sistemas corporativos em produção — ERP, CRM, WMS e plataforma de atendimento omnichannel. Construo do banco à interface: .NET e PostgreSQL no servidor, React e Next.js no front, com Angular e WPF sendo migrados para essa stack.

## Stack

**Back-end**

![.NET](https://img.shields.io/badge/.NET%20-512BD4?style=flat-square&logo=dotnet&logoColor=white)
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

**Infraestrutura e mensageria**

![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)

## Sobre o código que não está aqui

Quase tudo que construí nesses 7 anos é proprietário. Não posso publicar o código, mas posso falar do que ele resolve.

**Busca de atendimentos: ~20 segundos → milissegundos.** A consulta fazia varredura sequencial em uma tabela de alto volume. Reescrevi a estratégia de acesso com índices B-tree e GIN usando `pg_trgm` no PostgreSQL, ajustando as queries ao plano de execução real.

**Listagem de saídas do ERP: ~10 segundos → milissegundos.** Mesmo tipo de problema, contexto diferente: reescrita das queries e indexação adequada sobre um volume que só cresce.

**Integração com comércio eletrônico:** Integrei diversas plataformas como a Tray, Woocomerce, Bling, Ifood.

**Implementação de diversos cadastros:** Desenvolvi telas nas diversas tecnologias listadas na area de front-end.

Esses casos resumem bem o trabalho que faço.

## O que estou construindo

- **Homelab** — infraestrutura self-hosted com WSL2, Docker, PostgreSQL, Redis, RabbitMQ, n8n e Tailscale, usada como ambiente de desenvolvimento e laboratório de experimentação com IA.

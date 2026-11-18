# SpinRank

**Plataforma demonstrativa para gestão de clubes de tênis, desafios, partidas e ranking esportivo.**

O SpinRank é um projeto de desenvolvimento de produto que reúne regras de pontuação, organização de partidas e ferramentas administrativas em uma aplicação web. Este repositório é uma vitrine técnica de portfólio; não é a distribuição comercial nem a instalação de produção do sistema.

> **Demonstração de portfólio — uso comercial não autorizado.** Consulte [LICENSE](LICENSE) antes de utilizar qualquer conteúdo deste repositório.

## Visão geral

O projeto busca simplificar a rotina de um clube de tênis, conectando jogadores, administração, quadras, desafios e acompanhamento de desempenho em um só ambiente.

### Funcionalidades representadas no projeto

- Gestão administrativa de jogadores, categorias e configurações do clube.
- Cadastro e organização de quadras e horários.
- Solicitação e acompanhamento de desafios entre jogadores.
- Registro de resultados e fluxo de validação administrativa.
- Ranking por períodos e regras de pontuação por categoria do adversário.
- Assistente conversacional com IA para apoiar consultas sobre as informações disponíveis no sistema.
- Personalização visual da aplicação por meio das configurações do clube.

O escopo e o estado de implementação de cada módulo serão documentados em [docs/funcionalidades.md](docs/funcionalidades.md). Nem toda funcionalidade deve ser interpretada como certificada ou pronta para operação comercial.

## Tecnologias

- PHP 8+
- MySQL / MariaDB
- Bootstrap
- JavaScript
- Integração com serviço de IA generativa (configuração por variável de ambiente)

## Arquitetura

A aplicação utiliza uma organização por camadas, separando apresentação HTTP, serviços de aplicação, regras de domínio, repositórios e infraestrutura. Veja [docs/arquitetura.md](docs/arquitetura.md).

## Segurança e dados

Este repositório deve conter somente material preparado para demonstração:

- Não contém credenciais, tokens, arquivos `.env` ou configurações privadas.
- Não contém dados reais de jogadores, clube ou partidas.
- Não contém backups, dumps operacionais ou arquivos enviados por usuários.
- Exemplos e capturas de tela devem utilizar dados inteiramente fictícios.

Não use dados pessoais reais em testes ou demonstrações. A aplicação requer configuração segura e revisão adicional antes de qualquer implantação.

## Estrutura

```text
.
├── docs/                 # Documentação pública do projeto
├── screenshots/          # Capturas sanitizadas da interface (quando adicionadas)
├── demo/                 # Exemplos e dados fictícios (quando adicionados)
├── LICENSE
└── README.md
```

A estrutura será ampliada somente após revisão de cada arquivo que possa ser publicado.

## Status

Projeto em evolução. Este repositório é mantido separadamente do ambiente privado de desenvolvimento e produção. A presença de documentação ou exemplos não representa garantia de disponibilidade, segurança ou prontidão operacional.

## English

**SpinRank** is a portfolio demonstration of a tennis-club management platform, covering player administration, court scheduling, challenges, match results, ranking rules and an AI-assisted interface.

This repository is provided for portfolio review and evaluation only. **Commercial use is not authorized.** See [LICENSE](LICENSE). The project is evolving and must not be treated as a production-ready distribution.

---

Desenvolvido como projeto independente de portfólio.

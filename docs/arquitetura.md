# Arquitetura do SpinRank

## Visão em camadas

O SpinRank organiza responsabilidades para reduzir o acoplamento entre interface, regras de negócio e persistência.

- **Apresentação HTTP:** páginas e endpoints recebem requisições, validam entrada e controlam a resposta.
- **Aplicação:** serviços coordenam casos de uso, como processamento de resultados e atendimento do assistente.
- **Domínio:** concentra regras de negócio independentes de detalhes de infraestrutura, incluindo cálculos de pontuação.
- **Repositórios:** encapsulam consultas e operações de persistência.
- **Infraestrutura:** concentra conexão com banco de dados, carregamento de dependências e integrações externas.

## Tecnologias observadas

- PHP 8+
- MySQL / MariaDB com tabelas transacionais InnoDB
- Bootstrap e CSS para interface responsiva
- JavaScript para interações no navegador
- Integração com serviço externo de IA generativa, configurada por variáveis de ambiente

## Fluxo simplificado de uma partida

1. Um jogador solicita ou participa de um desafio.
2. O sistema registra o agendamento e seu estado.
3. O resultado é informado e segue o fluxo de validação administrativa.
4. A regra de pontuação avalia o resultado e o contexto do período.
5. O ranking e o histórico refletem os lançamentos aceitos.

## Persistência e consistência

Operações que alteram resultados e pontuação devem ser executadas com transações e controles contra duplicidade. A implementação deve ser validada no mesmo mecanismo e versão de banco usados no ambiente de destino.

## Limites desta documentação

Este documento apresenta a arquitetura em alto nível para fins de portfólio. Ele não expõe topologia de hospedagem, endereços internos, nomes de banco de produção, credenciais, dados de usuários ou detalhes operacionais privados. A arquitetura pode evoluir conforme o projeto avança.

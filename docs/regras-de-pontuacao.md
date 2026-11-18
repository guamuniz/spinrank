# Regra de pontuação do ranking

## Categorias

A matriz adotada para a V2 considera três categorias: Iniciante, Prata e Ouro.

## Matriz de pontos por vitória

A linha representa a categoria do vencedor; a coluna representa a categoria do adversário derrotado.

| Vencedor / adversário | Iniciante | Prata | Ouro |
|---|---:|---:|---:|
| Iniciante | 3,0 | 3,5 | 4,0 |
| Prata | 2,0 | 3,0 | 3,5 |
| Ouro | 1,0 | 2,0 | 3,0 |

## Limite por adversário

Somente as duas primeiras vitórias do mesmo jogador contra o mesmo adversário no período vigente geram pontos. As vitórias posteriores contra esse mesmo adversário não acrescentam pontos segundo esta regra.

## Empates e derrotas

- Derrota: não gera pontos.
- Empate: não gera pontos; pode permanecer registrado para estatísticas.
- A regra de empate deve ser alterada somente mediante decisão formal do regulamento do clube.

## Período

O ranking utiliza períodos bimestrais: janeiro-fevereiro, março-abril, maio-junho, julho-agosto, setembro-outubro e novembro-dezembro.

## Requisitos de consistência

- A pontuação deve ser calculada por uma regra centralizada, sem fórmulas divergentes nas telas.
- Somente resultados validados podem gerar pontuação.
- O lançamento no histórico e a atualização do saldo devem ocorrer na mesma transação.
- O sistema deve impedir crédito duplicado do mesmo resultado.
- Correções devem gerar estorno auditável, sem apagar silenciosamente o histórico.

Esta página descreve a regra adotada no projeto demonstrativo. A aplicação de um clube pode exigir regulamento próprio e configuração formal antes de uso real.

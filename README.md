# QA Sprint 5 — Testes Mobile (Urban Lunch)

Testes manuais end-to-end do aplicativo de delivery **Urban Lunch**, cobrindo o fluxo completo do usuário, do local de coleta até a entrega. Bootcamp de Analista de QA da TripleTen.

## Documentação

- **[Checklist mobile](checklist-mobile.md)** — as 36 verificações por seção do aplicativo, com status e link do defeito no Jira.
- Planilha original: `Ingrid Matos - Sprint 5 - QA34.xlsx`

## Objetivo

Verificar o comportamento do aplicativo em todo o fluxo de pedido, incluindo mapa, seleção de itens, cálculo de valores, acompanhamento da entrega e mensagens de erro.

## Seções testadas

1. Seleção do local de coleta
2. Escolha dos pratos
3. Confirmação do pedido
4. Acompanhamento do pedido: coleta
5. Pedido entregue
6. Notificações de erro

## Resultados

- **36 verificações** executadas: 30 aprovadas e 6 reprovadas — taxa de sucesso de **83%**.
- **6 defeitos reportados** no Jira (KAN-78 a KAN-83).

### Defeitos encontrados

| ID | Verificação que falhou | Seção |
|---|---|---|
| KAN-78 | O mapa mostra a ordem dos pontos de coleta | Seleção do local de coleta |
| KAN-79 | O valor total inclui o preço de todos os pratos preparados e a entrega | Confirmação do pedido |
| KAN-80 | Informações de restaurante e valores dos pratos exibidas de forma clara e legível | Confirmação do pedido |
| KAN-81 | Exibe o custo dos pratos e o tempo restante para preparo e entrega | Acompanhamento do pedido |
| KAN-82 | Exibe o valor e o tempo de preparo restante | Acompanhamento do pedido |
| KAN-83 | Rótulo de tempo de entrega escrito corretamente em português | Acompanhamento do pedido |

Quatro dos seis defeitos estão concentrados em valor e tempo — ou seja, exatamente as duas informações pelas quais o usuário decide se confia no pedido.

## Ferramentas

Emulador Android · Jira · Google Sheets / Excel

## Estrutura do repositório

- `checklist-mobile.md` — 36 verificações por seção
- `Ingrid Matos - Sprint 5 - QA34.xlsx` — planilha original
- `README.md`

## O que aprendi

- Em mobile, a severidade se mede pelo que o usuário perde. Valor total errado não é bug de tela: é dinheiro e confiança.
- Testar fluxo end-to-end revela defeitos que teste por tela não pega, porque o estado é carregado de uma etapa para a outra.
- Rótulo escrito errado também é defeito. Se o usuário não entende o que a tela está dizendo, o produto falhou naquele ponto.

## Melhorias a fazer

- Registrar dispositivo, versão do sistema e versão do app em cada execução.
- Anexar prints e gravações de tela dos defeitos.
- Cobrir cenários de conexão instável e de perda de sinal durante a entrega.

---

**Ingrid Matos** — Analista de QA Júnior
[LinkedIn](https://www.linkedin.com/in/ingridmatosn/) · [Portfólio de QA](https://github.com/ingridmatosn/QA-Portfolio-Main)

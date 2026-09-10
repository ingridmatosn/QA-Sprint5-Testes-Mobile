# QA Sprint 5 — Testes Mobile (Urban Lunch)

Testes manuais end-to-end do aplicativo de delivery **Urban Lunch**, cobrindo o fluxo completo do usuário, do local de coleta até a entrega. Bootcamp de Analista de QA da TripleTen.

## Documentação

- **[Checklist mobile](checklist-mobile.md)** — todas as verificações por seção do aplicativo, com status e link do defeito.
- Planilha original: `Ingrid Matos - Sprint 5 - QA34.xlsx`

## Objetivo

Verificar o comportamento do aplicativo em todo o fluxo de pedido, incluindo mapa, seleção de itens, cálculo de valores, acompanhamento da entrega e mensagens de erro.

## Seções testadas

1. Seleção do local de coleta
2. Escolha dos pratos
3. Confirmação do pedido
4. Acompanhamento da entrega
5. Pedido entregue
6. Notificações de erro

## Resultados

- **36 verificações** executadas: 30 aprovadas e 6 reprovadas — taxa de sucesso de **83%**.
- **6 defeitos reportados** no Jira (KAN-78 a KAN-83), dois deles críticos.

### Defeitos encontrados

| ID | Problema | Severidade |
|---|---|---|
| KAN-78 | Ordem dos pontos de coleta incorreta no mapa | Média |
| KAN-79 | Informação do prato incompleta | Média |
| KAN-80 | Cálculo do valor total incorreto | **Crítica** |
| KAN-81 | Localização não atualiza em tempo real | **Crítica** |
| KAN-82 | Avaliação não é salva | Média |
| KAN-83 | Mensagem de erro pouco clara | Baixa |

Os dois críticos afetam confiança direta do usuário: um erra o quanto ele vai pagar, o outro erra onde o pedido está.

## Ferramentas

Emulador Android · Jira · Google Sheets / Excel

## Estrutura do repositório

- `checklist-mobile.md` — 36 verificações por seção
- `Ingrid Matos - Sprint 5 - QA34.xlsx` — planilha original
- `README.md`

## O que aprendi

- Em mobile, a severidade se mede pelo que o usuário perde. Um cálculo de total errado não é bug de tela: é dinheiro e confiança.
- Testar fluxo end-to-end revela defeitos que teste por tela não pega, porque o estado é carregado de uma etapa para a outra.
- Mensagem de erro pouco clara também é defeito. Se o usuário não entende o que fazer em seguida, o produto falhou naquele ponto.

## Melhorias a fazer

- Registrar dispositivo, versão do sistema e versão do app em cada execução.
- Anexar prints e gravações de tela dos defeitos críticos.
- Cobrir cenários de conexão instável e de perda de sinal durante a entrega.

---

**Ingrid Matos** — Analista de QA Júnior
[LinkedIn](https://www.linkedin.com/in/ingridmatosn/) · [Portfólio de QA](https://github.com/ingridmatosn/QA-Portfolio-Main)

# Checklist mobile — Urban Lunch

Checklist e resultados de teste do aplicativo móvel Urban Lunch. 36 verificações, 30 aprovadas e 6 reprovadas.

| # | Descrição | Status | Relatório de bug |
|---|---|---|---|
| **1. Seleção do local de coleta** | | | |
| 1 | O mapa mostra a ordem dos pontos de coleta | REPROVADO | [KAN-78](https://ingridmatos.atlassian.net/browse/KAN-78) |
| 2 | O mapa mostra os pontos de coleta | APROVADO |  |
| 3 | Nenhum dos pontos de coleta é selecionado por padrão | APROVADO |  |
| 4 | Ao tocar em um ponto de coleta, ele é destacado e considerado selecionado | APROVADO |  |
| 5 | Tocar repetidamente em um ponto de coleta cancela a seleção | APROVADO |  |
| 6 | Tocar em um ponto de coleta quando outro já foi selecionado atualiza a escolha para o novo ponto | APROVADO |  |
| 7 | A lista suspensa contém uma relação de restaurantes nos quais o cliente pode retirar seu almoço | APROVADO |  |
| 8 | Ao selecionar um item da lista, ele é marcado no mapa e considerado escolhido | APROVADO |  |
| **2. Escolha dos pratos** | | | |
| 9 | Os pratos são exibidos em formato de lista | APROVADO |  |
| 10 | Cada item na lista contém o nome do prato | APROVADO |  |
| 11 | Cada item na lista contém os botões de -/+ e uma seta | APROVADO |  |
| 12 | Tocar em qualquer área da lista, exceto em +, leva à tela de informações sobre o prato | APROVADO |  |
| 13 | Ao clicar em +, o prato é adicionado à lista de pedidos do restaurante mais próximo ao ponto de coleta | APROVADO |  |
| 14 | Ao clicar em -, o prato é removido da lista de pedidos do restaurante | APROVADO |  |
| 15 | Exibe botão "Avançar" no rodapé | APROVADO |  |
| 16 | Botão "Avançar" fica inativo se não houver pratos na lista de pedidos | APROVADO |  |
| 17 | À esquerda do nome do prato, há uma seta de retorno | APROVADO |  |
| 18 | Pressionar a seta leva o usuário de volta à lista de pratos | APROVADO |  |
| 19 | Ao tocar no nome do restaurante, a quantidade do item é incrementada em uma unidade | APROVADO |  |
| **3. Confirmação do pedido** | | | |
| 20 | Se a lista for muito longa, é possível rolar a tela | APROVADO |  |
| 21 | O valor total inclui o preço de todos os pratos preparados e a entrega | REPROVADO | [KAN-79](https://ingridmatos.atlassian.net/browse/KAN-79) |
| 22 | Exibe o botão "Pedir" no rodapé | APROVADO |  |
| 23 | Tocar no botão "Pedir" leva o usuário à tela de acompanhamento do pedido | APROVADO |  |
| 24 | Informações de restaurante e valores dos pratos devem ser exibidas de forma clara e legível | REPROVADO | [KAN-80](https://ingridmatos.atlassian.net/browse/KAN-80) |
| **4. Acompanhamento do pedido: coleta** | | | |
| 25 | O mapa mostra o ponto de coleta, os restaurantes onde os pratos são preparados e as rotas até o ponto de coleta | APROVADO |  |
| 26 | Exibe o custo de todos os pratos pedidos no restaurante e o tempo restante para o preparo e a entrega no ponto de coleta | REPROVADO | [KAN-81](https://ingridmatos.atlassian.net/browse/KAN-81) |
| 27 | Deve exibir o valor e o tempo de preparo restante | REPROVADO | [KAN-82](https://ingridmatos.atlassian.net/browse/KAN-82) |
| 28 | Rótulo de tempo de entrega deve estar escrito corretamente em português | REPROVADO | [KAN-83](https://ingridmatos.atlassian.net/browse/KAN-83) |
| 29 | Se houver muitos itens na lista e eles não couberem no espaço, é possível rolar a tela | APROVADO |  |
| **5. Pedido entregue** | | | |
| 30 | A mudança para a tela de pedido entregue ocorre automaticamente quando o temporizador expira | APROVADO |  |
| 31 | O mapa mostra a localização do ponto de coleta desejado | APROVADO |  |
| 32 | Depois de clicar no botão "Recebi o pedido", o pedido é considerado concluído | APROVADO |  |
| 33 | O usuário vê uma barra de feedback e é levado de volta ao início após avaliar | APROVADO |  |
| 34 | Depois do feedback é possível selecionar o ponto de coleta para um novo pedido | APROVADO |  |
| **6. Notificações de erro** | | | |
| 35 | Se o acesso de geolocalização não for concedido ao aplicativo, uma mensagem de erro aparece | APROVADO |  |
| 36 | Ao tentar fazer um pedido sem adicionar nenhum prato, uma mensagem de erro aparece | APROVADO |  |


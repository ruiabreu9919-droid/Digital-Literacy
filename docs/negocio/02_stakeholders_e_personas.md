# Personas

## 1. Ana Martins, 32 anos, assistente administrativa
**Função e contexto:** Trabalha no departamento de administração, na sede. Usa o computador todo o dia e pede apoio de TI quando algo falha.

**Objetivo com o SmartDesk:** Pedir ajuda de forma rápida e saber em que ponto está o pedido, sem ter de perguntar a ninguém.

**Dificuldades atuais:**
- Não sabe se o pedido chegou à equipa de TI.
- Tem de repetir o problema por telefone ou mensagem.

**Necessidades na aplicação:**
1. Criar um ticket indicando a categoria (Equipamento, Software ou Acessos) e uma descrição.
2. Consultar o estado dos seus tickets.
3. Ver as atualizações e notas sobre o seu pedido.

## 2. Miguel Costa, 29 anos, técnico de suporte
**Função e contexto:** Faz parte da equipa de TI. Resolve problemas de equipamento, software e acessos dos colaboradores.

**Objetivo com o SmartDesk:** Saber exatamente o que tem para tratar e registar o que já fez.

**Dificuldades atuais:**
- Pedidos perdem-se entre a caixa de correio partilhada e a folha de cálculo.
- Nem sempre é claro quais os pedidos que são seus.

**Necessidades na aplicação:**
1. Ver a lista de tickets que lhe foram atribuídos.
2. Alterar o estado do ticket (Em tratamento, Resolvido).
3. Registar notas sobre o que foi feito.

## 3. Sofia Almeida, 43 anos, responsável de TI
**Função e contexto:** Lidera a equipa de TI, com três técnicos. Responde pela organização do trabalho e pela qualidade do apoio.

**Objetivo com o SmartDesk:** Ter uma visão clara do trabalho da equipa e garantir que nenhum pedido fica sem responsável.

**Dificuldades atuais:**
- A folha de cálculo não dá uma visão fiável do que está pendente.
- É difícil acompanhar a resolução dos pedidos.

**Necessidades na aplicação:**
1. Ver todos os tickets, filtrados por estado e por categoria.
2. Atribuir tickets aos técnicos e ver a carga de cada um.
3. Acompanhar a evolução de cada ticket até ao fecho.

## Relação entre personas e funcionalidades

| Funcionalidade | Ana (colaboradora) | Miguel (técnico) | Sofia (responsável) |
|---|---|---|---|
| Criar ticket com categoria e descrição | ✓ | | |
| Consultar os seus próprios tickets | ✓ | | |
| Ver atualizações e notas de um ticket | ✓ | ✓ | ✓ |
| Ver os tickets atribuídos a si | | ✓ | |
| Alterar o estado do ticket | | ✓ | |
| Registar notas no ticket | | ✓ | |
| Ver todos os tickets, filtrados por estado e categoria | | | ✓ |
| Atribuir tickets e ver a carga por técnico | | | ✓ |
| Fechar ticket | a decidir | a decidir | a decidir |

## Decisões pendentes
- **Atribuição:** só a Sofia atribui tickets ou os técnicos também podem atribuir?
- **Fecho:** quem fecha um ticket resolvido (colaborador, técnico ou responsável)?

# Baseline 

## Introdução

Este documento tem o objetivo de estabelecer a baseline dos requisitos de software, representando o conjunto de requisitos que servirá como referência para o desenvolvimento do sistema de entrega. A baseline apresenta os requisitos funcionais e não funcionais identificados através das diferentes técnicas de elicitação aplicadas (no caso do projeto, [Brainstorming](Brainstorming.md) e [Introspecção](Introspeccao.md)), garantindo a rastreabilidade e a consistência das funcionalidades propostas.


## Metodologia

A baseline de requisitos refere-se ao grupo de requisitos documentados no Software Requirements Specification (SRS). Esses requisitos são desenvolvidos ao longo das diversas etapas do processo de requisitos, incluindo elicitação, modelagem, verificação e validação. Eles servem como fundamento para o design e a implementação do software.

## Baeline de Requisitos

**Tabela 1**: Baseline de Requisitos

| ID  | Descrição                                                                               | Tipo | Rastreabilidade                           |
| --- | --------------------------------------------------------------------------------------- | ---- | ----------------------------------------- |  
| R01 | O aplicativo deve permitir o cadastro de clientes                                       | RF   | Brainstorming (RF1), Introspecção (RF1)   |
| R02 | O aplicativo deve permitir o cadastro de entregadores                                   | RF   | Brainstorming (RF2)                       |
| R03 | O aplicativo deve permitir o cadastro de lojas                                          | RF   | Brainstorming (RF3), Introspecção (RF13)  |
| R04 | O usuário deve ser capaz de fazer login no sistema                                      | RF   | Introspecção (RF2)                        |
| R05 | O usuário deve ser capaz de editar seu perfil                                           | RF   | Introspecção (RF3)                        |
| R06 | O usuário deve ser capaz de cadastrar ao menos um endereço no sistema                   | RF   | Introspecção (RF4)                        |
| R07 | O cliente deve ser capaz de visualizar os produtos disponíveis                          | RF   | Introspecção (RF5)                        |
| R08 | O cliente deve ser capaz de visualizar detalhes dos produtos ao clicar                  | RF   | Introspecção (RF6)                        |
| R09 | O cliente deve ser capaz de buscar produtos                                             | RF   | Brainstorming (RF7), Introspecção (RF7)   |
| R10 | O cliente deve ser capaz de buscar lojas                                                | RF   | Brainstorming (RF6), Introspecção (RF7)   |
| R11 | O cliente deve ser capaz de adicionar itens ao carrinho                                 | RF   | Brainstorming (RF15), Introspecção (RF8)  |
| R12 | O cliente deve ser capaz de visualizar o carrinho                                       | RF   | Introspecção (RF9)                        |
| R13 | O cliente deve ser capaz de remover itens do carrinho                                   | RF   | Introspecção (RF10)                       |
| R14 | O cliente deve ser capaz de finalizar a compra                                          | RF   | Introspecção (RF11)                       |
| R15 | O cliente deve ser capaz de acompanhar sua entrega através do aplicativo                | RF   | Introspecção (RF12)                       |
| R16 | O aplicativo deve ter suporte para múltiplas formas de pagamento                        | RF   | Brainstorming (RF20)                      |
| R17 | O aplicativo deve implementar ferramenta validadora de pagamentos                       | RF   | Brainstorming (RF10)                      |
| R18 | O aplicativo deve implementar protocolos de segurança para transações                   | RF   | Brainstorming (RF21)                      |
| R19 | O cliente deve ser capaz de buscar por geolocalização                                   | RF   | Brainstorming (RF8)                       |
| R20 | O cliente deve ser capaz de visualizar seu histórico de pedidos                         | RF   | Brainstorming (RF14), Introspecção (RF22) |
| R21 | O cliente deve ser capaz de realizar compra automática através do histórico             | RF   | Brainstorming (RF16)                      |
| R22 | O cliente deve ser capaz de avaliar entregadores                                        | RF   | Brainstorming (RF17)                      |
| R23 | O cliente deve ser capaz de avaliar lojas                                               | RF   | Brainstorming (RF18)                      |
| R24 | O cliente deve ser capaz de comentar em avaliações                                      | RF   | Brainstorming (RF19)                      |
| R25 | A loja deve ser capaz de cadastrar seu cardápio no aplicativo                           | RF   | Brainstorming (RF4), Introspecção (RF14)  |
| R26 | A loja deve ser capaz de gerir seus cardápios                                           | RF   | Brainstorming (RF5)                       |
| R27 | A loja deve ser capaz de receber pedidos no aplicativo                                  | RF   | Introspecção (RF15)                       |
| R28 | O aplicativo deve permitir entrega através de parceiros                                 | RF   | Brainstorming (RF11), Introspecção (RF17) |
| R29 | O aplicativo deve permitir retirada na loja                                             | RF   | Brainstorming (RF12), Introspecção (RF17) |
| R30 | O aplicativo deve permitir entrega pela própria loja                                    | RF   | Brainstorming (RF13), Introspecção (RF17) |
| R31 | O entregador deve ser capaz de receber pedidos no aplicativo                            | RF   | Introspecção (RF18)                       |
| R32 | O entregador deve ser capaz de localizar a loja através do aplicativo                   | RF   | Introspecção (RF19)                       |
| R33 | O entregador deve ser capaz de localizar o cliente através do aplicativo                | RF   | Introspecção (RF20)                       |
| R34 | O cliente deve ser capaz de visualizar status do pedido                                 | RF   | Introspecção (RF23)                       |
| R35 | O usuário deve ser capaz de cadastrar dados bancários no aplicativo                     | RF   | Introspecção (RF21)                       |
| R36 | O sistema deve proteger os dados bancários do usuário                                   | RNF  | Introspecção (RNF24)                      |
| R37 | O aplicativo deve possibilitar suporte via chat                                         | RF   | Brainstorming (RF9)                       |
| R38 | O sistema deve proteger os dados pessoais do usuário                                    | RNF  | Introspecção (RNF25)                      |
| R39 | O mapa do aplicativo deve ser atualizado em tempo real                                  | RNF  | Introspecção (RNF26)                      |
| R40 | A implementação do sistema deve seguir as diretrizes da LGPD                            | RNF  | Introspecção (RNF27)                      |
| R41 | O aplicativo deve iniciar em menos de 5 segundos                                        | RNF  | Introspecção (RNF28)                      |
| R42 | O aplicativo deve ter disponibilidade em 99% do tempo                                   | RNF  | Introspecção (RNF29)                      |
| R43 | O processamento de pagamentos deve ser concluído em até 10 segundos                     | RNF  | Introspecção (RNF30)                      |
| R44 | A interface do sistema deve seguir as diretrizes do Android e iOS                       | RNF  | Introspecção (RNF31)                      |
| R45 | A interface do sistema deve seguir as diretrizes WCAG 2.1 para acessibilidade           | RNF  | Introspecção (RNF32)                      |
| R46 | A interface do sistema deve ser adaptada para tamanhos distintos de tela de dispositivo | RNF  | Introspecção (RNF33)                      |
| R47 | O sistema do aplicativo deve utilizar PostgreSQL como banco de dados                    | RNF  | Brainstorming (RNF24)                     |
| R48 | O backend do aplicativo deve ser desenvolvido em Django                                 | RNF  | Brainstorming (RNF23)                     |
| R49 | O aplicativo deve ser desenvolvido em React Native para suporte multiplataforma         | RNF  | Brainstorming (RNF22)                     |

**Autor**: [Kallyne Passos](https://github.com/kalipassos), [Guilherme Westphall](https://github.com/west7)

## Referências

1. SAYÃO, Miriam; LEITE, Julio Cesar. Monografias em Ciência da Computação n° 20/05. Acesso em 3 de novembro de 2024.
2. 1. **Easterbrook, Steve.** *Knowledge Elicitation Techniques in Requirements Engineering.* Universidade de Toronto, Departamento de Ciência da Computação. Disponível em: [https://www.cs.toronto.edu](https://www.cs.toronto.edu/~sme/CSC2106S/slides/04-elicitation-techniques.pdf). Acesso em: 1 nov. 2024.
2. **Asian Research Publishing Network.** *Introspection as an Individual-Centered Requirement Elicitation Technique.* *ARPN Journal of Engineering and Applied Sciences*, v. 14, n. 2, p. 567-568, jan. 2019. Disponível em: [http://www.arpnjournals.com](https://www.arpnjournals.org/jeas/research_papers/rp_2019/jeas_0119_7590.pdf). Acesso em: 1 nov. 2024.
1. **REtraining Requirements Engineering.** *Guia facetado de técnicas elicitação de requisitos*. Disponível em: <https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-brainstorming>. Acesso em: 2 nov. 2024.



## Histórico de Versões

| Versão | Data da alteração | Comentário                                      | Autor(es)                                                                                        | Revisor(es) | Data de revisão |
| ------ | ----------------- | ----------------------------------------------- | ------------------------------------------------------------------------------------------------ | ----------- | --------------- |
| 1.0    | 03/11/2024        | Criação do artefato e da baseline de requisitos | [Kallyne Passos](https://github.com/kalipassos), [Guilherme Westphall](https://github.com/west7) |             |                 |
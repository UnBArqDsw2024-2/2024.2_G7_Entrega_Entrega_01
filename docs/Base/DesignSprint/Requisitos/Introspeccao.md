# 1.1.5 Introspecção

## Introdução

A técnica de elicitação conhecida como **Introspecção**, ou *Insight*, requer que o desenvolvedor visualize os requisitos do sistema no seu próprio pensamento. Essa técnica é especialmente útil quando o desenvolvedor já é bastante familiarizado com o domínio do sistema. A técnica envolve apenas uma pessoa, que foca em gerar um conjunto de requisitos a partir de reflexões e experiências individuais com o domínio do sistema.

## Metodologia

A equipe utilizou a introspecção na etapa de levantamento de requisitos durante a [Design Sprint](../1.1.DesignSprint.md). Os integrantes participaram de um exercício que consistia em se colocar no lugar de um usuário realizando dada funcionalidade. Essa etapa foi feita sem usar o sistema, somente com o que os integrantes se lembravam e conheciam do mesmo. Isso facilitou a elicitação dos requisitos funcionais. Os participantes dessa técnica geraram seu conjunto de requisitos de forma individual e estão listados na **Tabela 1** abaixo:

**Tabela 1**: Participantes

| Nome                                            | Matrícula | Requisitos   |
|-------------------------------------------------|-----------|--------------|
| [Guilherme Westphall](https://github.com/west7) | 211061805 | **Tabela 2** |
| [Kallyne Passos](https://github.com/kalipassos) | 202046229 | **Tabela 2** |

## Resultados

**Tabela 2**: Requisitos elicitados

| Número | Descrição                                                                                     | Tipo |
|--------|-----------------------------------------------------------------------------------------------|------|
| 1      | O usuário deve ser capaz de se registrar no sistema                                           | RF   |
| 2      | O usuário deve ser capaz de fazer login no sistema                                            | RF   |
| 3      | O usuário deve ser capaz editar seu perfil                                                    | RF   |
| 4      | O usuário deve ser capaz de cadastrar ao menos um endereço no sistema                         | RF   |
| 5      | O usuário deve ser capaz de visualizar os produtos disponíveis                                | RF   |
| 6      | O usuário deve ser capaz de visualizar detalhes dos produtos ao clicar                        | RF   |
| 7      | O usuário deve ser capaz de pesquisar por itens ou restaurantes específicos                   | RF   |
| 8      | O usuário deve ser capaz de adicionar itens ao carrinho                                       | RF   |
| 9      | O usuário deve ser capaz de visualizar o carrinho                                             | RF   |
| 10     | O usuário deve ser capaz de remover itens do carrinho                                         | RF   |
| 11     | O usuário deve ser capaz de finalizar a compra                                                | RF   |
| 12     | O usuário deve ser capaz de acompanhar sua entrega através do aplicativo                      | RF   |
| 13     | A loja deve ser capaz de se registrar no aplicativo                                           | RF   |
| 14     | A loja deve ser capaz de cadastrar seu cardápio no aplicativo                                 | RF   |
| 15     | A loja deve ser capaz de receber pedidos no aplicativo                                        | RF   |
| 17     | A loja deve ser capaz de escolher entre entrega própria ou através de parceiros do aplicativo | RF   |
| 18     | O entregador deve ser capaz de receber pedidos no aplicativo                                  | RF   |
| 19     | O entregador deve ser capaz de localizar a loja através do aplicativo                         | RF   |
| 20     | O entregador deve ser capaz de localizar o cliente através do aplicativo                      | RF   |
| 21     | O usuário deve ser capaz de cadastrar dados bancários no aplicativo                           | RF   |
| 22     | O usuário deve ser capaz de visualizar histórico de pedidos                                   | RF   |
| 23     | O usuário deve ser capaz de visualizar status do pedido                                       | RF   |
| 24     | O sistema deve proteger os dados bancários do usuário                                         | RNF  |
| 25     | O sistema deve proteger os dados pessoais do usuário                                          | RNF  |
| 26     | O mapa do aplicativo deve ser atualizado em tempo real                                        | RNF  |
| 27     | A implementação do sistema deve seguir as diretrizes da LGPD                                  | RNF  |
| 28     | O aplicativo deve iniciar em menos de 5 segundos                                              | RNF  |
| 29     | O aplicativo deve ter disponibilidade em 99% do tempo                                         | RNF  |
| 30     | O processamento de pagamentos deve ser concluído em até 10 segundos                           | RNF  |
| 31     | A interface do sistema deve seguir as diretrizes do Android e iOS                             | RNF  |
| 32     | A interface do sistema deve seguir as diretrizes WCAG 2.1 para acessibilidade                 | RNF  |
| 33     | A interface do sistema deve ser adaptada para tamanhos distintos de tela de dispositivo       | RNF  |

> Legendas: RF - Requisito Funcional; RNF - Requisito Não Funcional.

**Autor**: [Guilherme Westphall](https://github.com/west7), [Kallyne Passos](https://github.com/kalipassos)



## Referências

1. **Easterbrook, Steve.** *Knowledge Elicitation Techniques in Requirements Engineering.* Universidade de Toronto, Departamento de Ciência da Computação. Disponível em: [https://www.cs.toronto.edu](https://www.cs.toronto.edu/~sme/CSC2106S/slides/04-elicitation-techniques.pdf). Acesso em: 1 nov. 2024.

2. **Asian Research Publishing Network.** *Introspection as an Individual-Centered Requirement Elicitation Technique.* *ARPN Journal of Engineering and Applied Sciences*, v. 14, n. 2, p. 567-568, jan. 2019. Disponível em: [http://www.arpnjournals.com](https://www.arpnjournals.org/jeas/research_papers/rp_2019/jeas_0119_7590.pdf). Acesso em: 1 nov. 2024.

## Histórico de versões

| Versão | Data da alteração | Comentário                                            | Autor(es)                                       | Revisor(es)                                     | Data de revisão |
|--------|-------------------|-------------------------------------------------------|-------------------------------------------------|-------------------------------------------------|-----------------|
| 1.0    | 1/11/2024         | Criação do artefato                                   | [Guilherme Westphall](https://github.com/west7) | [Kallyne Passos](https://github.com/kalipassos) | 2/11/2024       |
| 1.1    | 1/11/2024         | Adição da introdução e metodologia                    | [Guilherme Westphall](https://github.com/west7) | [Kallyne Passos](https://github.com/kalipassos) | 2/11/2024       |
| 1.2    | 1/11/2024         | Realização da técnica e adição das tabelas 1 e 2      | [Guilherme Westphall](https://github.com/west7) | [Kallyne Passos](https://github.com/kalipassos) | 2/11/2024       |
| 1.3    | 2/11/2024         | Realização da técnica e modificações nas tabela 1 e 2 | [Kallyne Passos](https://github.com/kalipassos) |                                                 |                 |
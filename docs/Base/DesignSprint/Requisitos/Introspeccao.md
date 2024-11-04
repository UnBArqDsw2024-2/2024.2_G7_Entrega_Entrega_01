# 1.1.5 Introspecção

## Introdução

A técnica de elicitação conhecida como **Introspecção**, ou *Insight*, requer que o desenvolvedor visualize os requisitos do sistema no seu próprio pensamento. Essa técnica é especialmente útil quando o desenvolvedor já é bastante familiarizado com o domínio do sistema. A técnica envolve apenas uma pessoa, que foca em gerar um conjunto de requisitos a partir de reflexões e experiências individuais com o domínio do sistema.

## Metodologia

A equipe utilizou a introspecção na etapa de levantamento de requisitos durante a [Design Sprint](../1.1.DesignSprint.md). Os integrantes participaram de um exercício que consistia em se colocar no lugar de um usuário e imaginar a realização de determinadas funcionalidades. Essa etapa foi feita sem usar o sistema, baseando-se apenas nas memórias e no conhecimento prévio dos integrantes. Essa abordagem facilitou a elicitação dos requisitos funcionais. Cada participante gerou individualmente seu conjunto de requisitos, os quais estão listados na **Tabela 1** a seguir:

**Tabela 1**: Participantes

| Nome                                            | Matrícula |    
|-------------------------------------------------|-----------|
| [Guilherme Westphall](https://github.com/west7) | 211061805 | 
| [Kallyne Passos](https://github.com/kalipassos) | 202046229 | 

## Resultados

**Tabela 2**: Requisitos elicitados

| Número | Descrição                                                                                     | Tipo |
|--------|-----------------------------------------------------------------------------------------------|------|
| <a id="i01">01</a>      | O usuário deve ser capaz de se registrar no sistema                                           | RF   |
| <a id="i02">02</a>      | O usuário deve ser capaz de fazer login no sistema                                            | RF   |
| <a id="i03">03</a>      | O usuário deve ser capaz de editar seu perfil                                                 | RF   |
| <a id="i04">04</a>      | O usuário deve ser capaz de cadastrar ao menos um endereço no sistema                         | RF   |
| <a id="i05">05</a>      | O usuário deve ser capaz de visualizar os produtos disponíveis                                | RF   |
| <a id="i06">06</a>      | O usuário deve ser capaz de visualizar detalhes dos produtos ao clicar                        | RF   |
| <a id="i07">07</a>      | O usuário deve ser capaz de pesquisar por itens ou restaurantes específicos                   | RF   |
| <a id="i08">08</a>      | O usuário deve ser capaz de adicionar itens ao carrinho                                       | RF   |
| <a id="i09">09</a>      | O usuário deve ser capaz de visualizar o carrinho                                             | RF   |
| <a id="i10">10</a>     | O usuário deve ser capaz de remover itens do carrinho                                         | RF   |
| <a id="i11">11</a>     | O usuário deve ser capaz de finalizar a compra                                                | RF   |
| <a id="i12">12</a>     | O usuário deve ser capaz de acompanhar sua entrega através do aplicativo                      | RF   |
| <a id="i13">13</a>     | A loja deve ser capaz de se registrar no aplicativo                                           | RF   |
| <a id="i14">14</a>     | A loja deve ser capaz de cadastrar seu cardápio no aplicativo                                 | RF   |
| <a id="i15">15</a>     | A loja deve ser capaz de receber pedidos no aplicativo                                        | RF   |
| <a id="i17">17</a>     | A loja deve ser capaz de escolher entre entrega própria ou através de parceiros do aplicativo | RF   |
| <a id="i18">18</a>     | O entregador deve ser capaz de receber pedidos no aplicativo                                  | RF   |
| <a id="i19">19</a>     | O entregador deve ser capaz de localizar a loja através do aplicativo                         | RF   |
| <a id="i20">20</a>     | O entregador deve ser capaz de localizar o cliente através do aplicativo                      | RF   |
| <a id="i21">21</a>     | O usuário deve ser capaz de cadastrar dados bancários no aplicativo                           | RF   |
| <a id="i22">22</a>     | O usuário deve ser capaz de visualizar histórico de pedidos                                   | RF   |
| <a id="i23">23</a>     | O usuário deve ser capaz de visualizar status do pedido                                       | RF   |
| <a id="i24">24</a>     | O sistema deve proteger os dados bancários do usuário                                         | RNF  |
| <a id="i25">25</a>     | O sistema deve proteger os dados pessoais do usuário                                          | RNF  |
| <a id="i26">26</a>     | O mapa do aplicativo deve ser atualizado em tempo real                                        | RNF  |
| <a id="i27">27</a>     | A implementação do sistema deve seguir as diretrizes da LGPD                                  | RNF  |
| <a id="i28">28</a>     | O aplicativo deve iniciar em menos de 5 segundos                                              | RNF  |
| <a id="i29">29</a>     | O aplicativo deve ter disponibilidade em 99% do tempo                                         | RNF  |
| <a id="i30">30</a>     | O processamento de pagamentos deve ser concluído em até 10 segundos                           | RNF  |
| <a id="i31">31</a>     | A interface do sistema deve seguir as diretrizes do Android e iOS                             | RNF  |
| <a id="i32">32</a>     | A interface do sistema deve seguir as diretrizes WCAG 2.1 para acessibilidade                 | RNF  |
| <a id="i33">33</a>     | A interface do sistema deve ser adaptada para tamanhos distintos de tela de dispositivo       | RNF  |

> Legendas: RF - Requisito Funcional; RNF - Requisito Não Funcional.

**Autor**: [Guilherme Westphall](https://github.com/west7), [Kallyne Passos](https://github.com/kalipassos)

## Referências

1. **Easterbrook, Steve.** *Knowledge Elicitation Techniques in Requirements Engineering.* Universidade de Toronto, Departamento de Ciência da Computação. Disponível em: [https://www.cs.toronto.edu](https://www.cs.toronto.edu/~sme/CSC2106S/slides/04-elicitation-techniques.pdf). Acesso em: 1 nov. 2024.

2. **Asian Research Publishing Network.** *Introspection as an Individual-Centered Requirement Elicitation Technique.* *ARPN Journal of Engineering and Applied Sciences*, v. 14, n. 2, p. 567-568, jan. 2019. Disponível em: [http://www.arpnjournals.com](https://www.arpnjournals.org/jeas/research_papers/rp_2019/jeas_0119_7590.pdf). Acesso em: 1 nov. 2024.

## Histórico de versões

| Versão | Data da alteração | Comentário                                            | Autor(es)                                       | Revisor(es)                                     | Data de revisão |
|--------|-------------------|-------------------------------------------------------|-------------------------------------------------|-------------------------------------------------|-----------------|
| 1.0    | 1/11/2024         | Criação do artefato                                   | [Guilherme Westphall](https://github.com/west7) | [Raquel Ferreira Andrade](https://github.com/raquel-andrade) | 03/11/2024       |
| 1.1    | 1/11/2024         | Adição da introdução e metodologia                    | [Guilherme Westphall](https://github.com/west7) | [Raquel Ferreira Andrade](https://github.com/raquel-andrade) | 03/11/2024       |
| 1.2    | 1/11/2024         | Realização da técnica e adição das tabelas 1 e 2      | [Guilherme Westphall](https://github.com/west7) | [Raquel Ferreira Andrade](https://github.com/raquel-andrade) | 03/11/2024       |
| 1.3    | 2/11/2024         | Realização da técnica e modificações nas tabela 1 e 2 | [Kallyne Passos](https://github.com/kalipassos) | [Raquel Ferreira Andrade](https://github.com/raquel-andrade)  | 03/1/2024  |
# Contribuição

Este guia tem como objetivo estabeler o padrão para a contribuição no projeto

## Issues

Issues são a forma de reportar problemas, bugs, melhorias e novas features. Para criar uma issue, siga os passos abaixo:

1. Acesse a aba `Issues` no repositório
2. Selecione o tipo de issue que deseja criar (bug, feature, task)
3. Preencha o título e a descrição da issue
4. Clique em `Submit new issue`

## Branches

### Branch Principal

A branch principal do projeto é a `main`. Ela é protegida, ou seja, não é possível fazer push diretamente nela. Para contribuir com o projeto, você deve criar uma branch a partir da `main` e fazer um pull request para a `main`.

### Branches de Desenvolvimento

Branches são a forma de trabalhar em novas features, correções de bugs e melhorias. O padrão de nomenclatura de branches é `X-atividade`, onde `X` é o número da issue que você está trabalhando e `atividade` é uma descrição curta da atividade que você está realizando.

## Commits

Os commits devem ser claros e objetivos, respeitando os padrões comentados abaixo:

- Deve possuir número da issue e assunto associado
- Deve ser escrito em português
- Os verbos devem estar no presente do indicativo

Sendo assim, o padrão de mensagem de commit é: `(#numero_da_issue): assunto`

```
(#1): adiciona documento do rich picture
```

Se o commit for feito em conjunto com outra pessoa, basta adicionar o Co-authored-by no final da mensagem de commit:

```
(#1): adiciona documento do rich picture

Co-authored-by: nome <email>
```

## Pull Requests

Pull requests são a forma de contribuir com o projeto. Para criar um pull request, siga os passos abaixo:

1. Acesse o repositório no GitHub
2. Clique em `New pull request`
3. Selecione a branch que você criou
4. Preencha as informações de acordo com o [template](./.github/pull_request_template.md) do pull request
5. Clique em `Create pull request`

## Revisão de Contribuições

Após a criação do pull request, um membro do time fará a revisão da contribuição. Caso haja alguma sugestão de melhoria, você deve fazer as alterações necessárias e adicionar um novo commit na branch do pull request.

## Histórico de Versões

| Versão | Data da alteração | Comentário | Autor(es) | Revisor(es) | Data de revisão |
|--------|-----------|-----------|-----------|-------------|-------------|
| 1.0 | 27/10/2024 | Criação do documento | Lucas Martins | Felipe Araújo | 27/10/2024 |
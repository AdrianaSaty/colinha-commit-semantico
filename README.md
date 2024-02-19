# Colinha - Commit Semântico
Essa colinha foi baseada em dois documentos:
- [Karma Runner](https://karma-runner.github.io/6.3/dev/git-commit-msg.html)
- [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

Deixei de uma forma simplificada de acordo com o que eu vi ser mais usado no dia a dia das empresas que trabalhei & o que eu vi dar mais certo.

## Formato:
Os commits devem ser escrito com o seguinte formato, onde o _type_ é obrigatório e pode ser consultado no próximo tópico e a descrição descreve a ação daquele commit mais detalhadamente:

`<type>: <description>`

## Type
O _type_ pode ser um desses tipos:

| Prefixo | Descrição           | Significado                                    |
|---------|---------------------|------------------------------------------------|
| feat    | Features            | Uma nova funcionalidade                        |
| fix     | Correções de Erros  | Uma correção de bug                            |
| docs    | Documentação        | Apenas mudanças na documentação               |
| style   | Estilos             | Mudanças em relação a estilização              |
| refactor| Refatoração de Código | Uma alteração de código que não corrige um bug nem adiciona uma funcionalidade |
| perf    | Melhorias de Performance | Uma alteração de código que melhora o desempenho |
| test    | Testes              | Adição de testes em falta ou correção de testes existentes |
| build   | Builds              | Mudanças que afetam o sistema de build ou dependências externas (exemplos de escopos: gulp, broccoli, npm) |
| ci      | Integrações Contínuas | Alterações em nossos arquivos e scripts de configuração de CI (exemplos de escopos: Travis, Circle, BrowserStack, SauceLabs) |
| chore   | Tarefas             | Outras mudanças que não modificam arquivos de código-fonte ou de teste |
| revert  | Reverter            | Reverte um commit anterior                    |




## ✒️ Autor

* **[Adriana Saty](https://github.com/AdrianaSaty)** 

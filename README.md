# Padrões de Commits Semânticos 📜

De acordo com a especificação do **[Conventional Commits](https://www.conventionalcommits.org/pt-br)**, os commits semânticos são uma convenção simples para mensagens de commit. Essa convenção define regras para criar um histórico de commits explícito, facilitando a criação de ferramentas automatizadas.

Esses commits ajudam você e sua equipe a entenderem claramente quais alterações foram feitas em cada trecho de código commitado.

## Tipos de Commit e Descrições 🦄

- `feat`: Commits do tipo feat indicam a adição de um **novo recurso** ao projeto (relacionado ao MINOR no versionamento semântico).

- `fix`: Commits do tipo fix indicam que o código commitado está **corrigindo um problema** (bug fix) (relacionado ao PATCH no versionamento semântico).

- `docs`: Commits do tipo docs indicam **mudanças na documentação**, como no README do repositório (não inclui alterações de código).

- `test`: Commits do tipo test são usados quando há **alterações nos testes**, incluindo criação, modificação ou exclusão de testes unitários (não inclui alterações de código).

- `build`: Commits do tipo build são usados quando há alterações em **arquivos de build e dependências**.

- `perf`: Commits do tipo perf são usados para identificar alterações de código relacionadas a **performance**.

- `style`: Commits do tipo style indicam **alterações de formatação de código**, como ponto e vírgula, espaços em branco, lint, etc. (não inclui alterações de código).

- `refactor`: Commits do tipo refactor referem-se a mudanças devido a **refatorações que não alteram a funcionalidade**, como melhorias de performance ou alterações estruturais.

- `chore`: Commits do tipo chore indicam **atualizações de tarefas** de build, configurações de administrador, pacotes, etc. (não inclui alterações de código).

- `ci`: Commits do tipo ci indicam mudanças relacionadas a **integração contínua** (_continuous integration_).

- `raw`: Commits do tipo raw indicam mudanças relacionadas a arquivos de configurações, dados, features, parâmetros.

- `cleanup`: Commits do tipo cleanup são usados para remover código comentado, trechos desnecessários ou qualquer outra forma de limpeza do código-fonte, visando melhorar legibilidade e manutenibilidade.

- `remove`: Commits do tipo remove indicam a exclusão de arquivos, diretórios ou funcionalidades obsoletas ou não utilizadas, reduzindo o tamanho e a complexidade do projeto.

## Recomendações 🎉

- Use um tipo consistente com o propósito da alteração.
- Limite a primeira linha do commit a no máximo 4 palavras.
- Forneça detalhes adicionais na descrição do commit, se necessário.
- Use um emoji no início da mensagem de commit para representar o tipo de alteração.

## Exemplos 💻

Aqui estão alguns exemplos de como utilizar os commits semânticos:

- `git commit -m ":tada: Commit inicial"`
- `git commit -m ":books: docs: Atualização do README"`
- `git commit -m ":bug: fix: Corrige bug na autenticação"`
- `git commit -m ":sparkles: feat: Adiciona funcionalidade de login"`

## Contribuição ✨

Contribua para o projeto ajudando a manter um histórico de commits claro e organizado. Leia como contribuir **[aqui](https://github.com/seu-usuario/seu-repositorio/blob/main/CONTRIBUTING.md)** e verifique a **[licença](https://github.com/seu-usuario/seu-repositorio/blob/main/LICENSE.md)** do projeto.

Este projeto é um recurso gratuito para a comunidade de desenvolvedores. Você também pode apoiar adquirindo meu ebook "**[eFront - Estudando frontend do zero](https://seu-link-do-ebook)**".

Espero que este README revisado ajude a esclarecer como utilizar commits semânticos de forma eficaz no seu projeto.

# GitHub Flow

1. Crie uma branch a partir da `main` para trabalhar numa mudança.
2. Faça as alterações e registre commits com mensagens claras.
3. Abra um Pull Request para mostrar o que mudou e pedir revisão.
4. Leia os comentários, converse sobre as sugestões e faça ajustes na mesma branch. Os novos commits aparecem no Pull Request já aberto.
5. Faça o merge quando a mudança estiver pronta para entrar na `main`.
6. Apague a branch depois que ela entrar na `main`.

## Por que usar uma branch?

A `main` guarda a versão que todo mundo usa. Numa branch separada, dá para testar uma alteração e ver o diff antes de juntar as mudanças. Por exemplo, posso corrigir um link em uma branch enquanto a equipe continua usando a versão principal.

## Como ler o diff

Uma linha com `-` em vermelho foi removida. Uma linha com `+` em verde foi adicionada. Se eu trocar o nome de um título, o título antigo pode aparecer em vermelho e o novo em verde.

# guia-de-revisao-git

Mini guia de revisão de Versionamento e Colaboração. Fiz a Operação Merge individualmente, usando branches e Pull Requests para praticar o fluxo e resolver um conflito de verdade.

## Participante

- Davi — versão individual.

## O que tem aqui

- [Glossário](glossario.md): oito termos de versionamento explicados com exemplos.
- [GitHub Flow](github-flow.md): os seis passos do fluxo e como ler um diff.
- [Combinados](combinados.md): os dias e o horário de estudo definidos após o conflito.

## Respostas

### 1. O diff

No [commit de ajuste do glossário](../../commit/190cb19c4defcdc7edae14b90bb17aab43aff13a), a definição anterior de merge saiu em vermelho. Em verde entrou a nova versão da definição, com o exemplo de integrar a branch `docs/glossario` à `main` e a explicação de quando pode aparecer um conflito. O sinal `-` indica uma linha removida e o `+` indica uma linha adicionada.

### 2. O conflito

As branches `docs/dia-a` e `docs/dia-b` saíram da mesma versão da `main`. Uma trocou a linha por terça-feira e a outra por quinta-feira. Depois que a primeira entrou na `main`, o GitHub bloqueou o merge da segunda porque as duas mudaram a mesma linha. Num arquivo com conflito, `<<<<<<<` abre a primeira versão, `=======` separa as duas e `>>>>>>>` fecha a segunda. Mantive o horário e escrevi **Dias de estudo: terça e quinta** para aproveitar as duas opções. A resolução ficou registrada no [PR #7](../../pull/7).

### 3. A revisão

Fiz uma conferência individual e registrei os ajustes na mesma branch de cada PR. No glossário, as definições estavam diretas e acrescentei um exemplo para deixar merge mais fácil de entender. No GitHub Flow, os passos estavam em ordem e esclareci que os novos commits aparecem no PR já aberto. Em dupla, o colega usaria **Request changes** para pedir cada ajuste e **Approve** depois de verificar o novo commit. Nesta versão individual, as mudanças foram integradas depois da conferência, sem revisão de colega.

### 4. Segurança

Se alguém publicar um telefone e apagar no commit seguinte, o número ainda pode aparecer no commit anterior ou em cópias do repositório. Por isso, é importante conferir o arquivo e o diff antes de publicar. Senhas e números de documentos, como CPF, também precisam ficar fora de repositórios públicos.

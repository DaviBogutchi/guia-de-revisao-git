# guia-de-revisao-git

Mini guia de revisão de Versionamento e Colaboração. A Operação Merge usa dois arquivos de estudo e um conflito planejado para praticar o GitHub Flow.

## Integrantes

- Aluno A: Davi

## Arquivos

- `glossario.md`: oito termos de versionamento (em revisão).
- `github-flow.md`: seis passos do GitHub Flow (segunda parte da atividade).
- [combinados.md](combinados.md): dia e horário de estudo.

## Respostas de revisão

### O diff

O vermelho com `-` indica as linhas removidas da versão anterior. O verde com `+` indica as linhas adicionadas. Se uma frase for trocada, a frase antiga aparece em vermelho e a nova em verde. O exemplo do commit deve ser registrado depois da revisão do PR.

### O conflito

Um conflito aparece quando o Git não consegue juntar mudanças feitas de formas diferentes no mesmo trecho. `<<<<<<<` marca o começo da versão da branch atual, `=======` separa as versões e `>>>>>>>` indica o fim da versão que está sendo integrada. Depois de escolher o texto final, a gente remove os marcadores e registra a resolução. O resultado da dupla será preenchido depois da segunda rodada.

### A revisão

O comentário da dupla deve indicar o trecho, sugerir uma mudança e reconhecer algo que ficou bom. Primeiro o colega usa **Request changes**. Depois do novo commit, ele confere o ajuste e usa **Approve**. Os comentários reais entram aqui após a revisão.

### Segurança

Apagar um telefone no commit seguinte deixa o número nas versões anteriores. Em um repositório público, ainda dá para encontrá-lo no histórico ou em cópias do repositório. Senhas e documentos pessoais, como CPF, também devem ficar fora do GitHub.

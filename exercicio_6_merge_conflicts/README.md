# Exercício 6: Merge Conflicts

## Objetivo

Este exercício tem como objetivo ensiná-lo a resolver conflitos de merge, uma habilidade essencial para qualquer desenvolvedor trabalhando em um ambiente de equipe onde múltiplas pessoas estão fazendo mudanças em um mesmo projeto.

## Tarefa

### Passo 1: Preparação

1. **Crie um novo arquivo:** No branch principal do seu repositório local, crie um arquivo chamado `merge_conflict.txt`.
2. **Adicione conteúdo inicial:** Escreva "Este é o conteúdo original do arquivo." no arquivo `merge_conflict.txt` e faça o commit dessa mudança.

### Passo 2: Crie Branches e Modifique o Arquivo

1. **Crie dois branches:** A partir do branch principal, crie dois novos branches, por exemplo, `feature-branch1` e `feature-branch2`.
   
   ```bash
   git checkout -b feature-branch1
   git checkout main
   git checkout -b feature-branch2
   ```

Modifique o mesmo arquivo em ambos os branches: Em cada branch, altere a mesma linha do arquivo merge_conflict.txt. Por exemplo, em feature-branch1, mude para "Este é o conteúdo alterado no branch1.", e em feature-branch2, altere para "Este é o conteúdo alterado no branch2.". Faça o commit dessas mudanças em seus respectivos branches.

### Passo 3: Tente Mesclar os Branches
Mescle feature-branch1 no main: Volte para o branch main e mescle feature-branch1.

```bash
git checkout main
git merge feature-branch1
```
Tente mesclar feature-branch2 no main: Agora, tente mescle feature-branch2 no main. Você encontrará um conflito de merge.

```bash
git merge feature-branch2
```

### Passo 4: Resolvendo o Conflito
Abra o arquivo: Abra o arquivo merge_conflict.txt em um editor de texto. Você verá marcas de conflito indicando as diferentes alterações.

Escolha o conteúdo a ser mantido: Edite o arquivo para resolver o conflito. Escolha qual versão do conteúdo você deseja manter ou combine-as de alguma maneira.

Finalize o merge: Depois de resolver o conflito, adicione o arquivo ao staging area e complete o merge com um commit.

```bash
git add merge_conflict.txt
git commit -m "Resolved merge conflict between feature-branch1 and feature-branch2"
```

### Submissão
Após completar a tarefa, submeta um breve relatório na issue designada para este exercício, descrevendo sua experiência e como você resolveu o conflito de merge.

### Reflexão
- Como os conflitos de merge podem impactar o fluxo de trabalho em equipe?
- Que estratégias você pode utilizar para minimizar a ocorrência de conflitos de merge?
- Estamos ansiosos para ver suas soluções e discussões sobre como resolver conflitos de merge efetivamente!
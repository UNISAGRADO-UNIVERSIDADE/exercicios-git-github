# Exercício 8: Gitignore e Arquivos Sensíveis

## Objetivo

O objetivo deste exercício é aprender a utilizar o arquivo `.gitignore` para evitar que arquivos desnecessários ou sensíveis sejam commitados em seu repositório. Isso é crucial para manter o repositório limpo e seguro.

## Tarefa

### Passo 1: Criar o Arquivo `.gitignore`

1. No diretório raiz do seu repositório local, crie um arquivo chamado `.gitignore`.
2. Abra este arquivo em um editor de texto de sua escolha.

### Passo 2: Configurar `.gitignore`

Adicione as seguintes linhas ao seu arquivo `.gitignore` para ignorar arquivos comuns que não devem ser commitados:

Arquivos de log
*.log

Diretório node_modules
node_modules/

Pastas de build
build/
dist/

Arquivos temporários
*.tmp
*~
.DS_Store

Ambiente virtual Python
venv/


Estas são apenas algumas entradas comuns para muitos projetos, mas sinta-se à vontade para adicionar qualquer outro arquivo ou pasta que seja específico para o seu projeto.

### Passo 3: Aplicar as Configurações

1. Salve e feche o arquivo `.gitignore`.
2. Adicione o `.gitignore` ao seu repositório com `git add .gitignore` e faça o commit com `git commit -m "Adicionado .gitignore"`.

## Submissão

Após completar a tarefa, submeta um breve relatório na issue designada para este exercício no repositório de exercícios. Inclua:
- Uma descrição das configurações que você adicionou ao seu `.gitignore`.
- Qualquer desafio que você encontrou ao configurar o `.gitignore` e como você o resolveu.

## Reflexão

- Por que é importante ignorar certos arquivos e pastas em um repositório Git?
- Como a inclusão de arquivos desnecessários ou sensíveis pode afetar o desenvolvimento e a segurança do projeto?

Estamos ansiosos para ver suas configurações de `.gitignore` e discutir as melhores práticas para manter os repositórios limpos e seguros!

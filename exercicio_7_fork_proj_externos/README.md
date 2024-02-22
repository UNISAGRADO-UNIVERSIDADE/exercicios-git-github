# Exercício 7: Fork e Contribuição para Projetos Externos

## Objetivo

Este exercício tem como objetivo proporcionar uma compreensão prática de como contribuir para projetos de código aberto. Aque você aprenderá a fazer um fork de repositórios, cloná-los para sua máquina local, realizar mudanças e submeter pull requests para contribuir com melhorias ou correções para o projeto original.

## Tarefa

### Passo 1: Escolher um Repositório de Código Aberto

1. Navegue pelo GitHub para encontrar um projeto de código aberto que você acha interessante e gostaria de contribuir. Pode ser qualquer coisa que desperte seu interesse e para o qual você sinta que pode contribuir, mesmo que seja com uma pequena correção de documentação.

### Passo 2: Fazer um Fork do Repositório

1. Na página do repositório no GitHub, clique no botão "Fork" no canto superior direito. Isso criará uma cópia do repositório na sua conta do GitHub.

### Passo 3: Clonar o Fork para Sua Máquina Local

1. Navegue até o fork do repositório em sua conta do GitHub.
2. Clique no botão "Code" e copie o URL para clonar o repositório.
3. Abra o terminal ou prompt de comando, navegue até o diretório onde deseja colocar o projeto e execute:
   ```bash
   git clone URL_DO_SEU_FORK
   ```
Substitua URL_DO_SEU_FORK pela URL que você copiou.

### Passo 4: Fazer Alterações Locais
Crie um novo branch para suas alterações:

```bash
git checkout -b nome-do-seu-branch
```
Faça suas alterações no código ou na documentação do projeto.
Adicione e commit suas mudanças.

### Passo 5: Submeter um Pull Request
Faça push do seu branch para o GitHub:

```bash
git push origin nome-do-seu-branch
```

- Vá para o seu fork no GitHub e clique em "Compare & pull request" ao lado do seu branch.
- Certifique-se de que o pull request está sendo feito para o repositório original do qual você fez fork.
- Adicione uma descrição clara do que você alterou e por que. Se houver issues relacionadas, mencione-as.
- Envie o pull request.

### Submissão
Depois de completar a tarefa, submeta um breve relatório na issue designada para este exercício no repositório de exercícios. Inclua o link para o pull request que você submeteu. Compartilhe sua experiência sobre o processo de contribuição.

### Reflexão
- Como você se sentiu contribuindo para um projeto de código aberto?
- Quais foram os desafios que você encontrou e como os superou?
- Esperamos que este exercício tenha proporcionado uma visão valiosa sobre como contribuir para a comunidade de código aberto. Estamos ansiosos para ver suas contribuições!

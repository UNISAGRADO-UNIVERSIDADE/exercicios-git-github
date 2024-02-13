# Exercício 9: Branches para Features e Hotfixes

## Objetivo

Este exercício tem como objetivo praticar o gerenciamento de branches no Git, uma habilidade crucial para o desenvolvimento colaborativo de software. Você aprenderá a criar branches específicos para desenvolver novas funcionalidades e para correções urgentes, e como integrá-los ao branch principal do projeto.

## Tarefa

### Passo 1: Criar Branch para Nova Funcionalidade

1. **Crie um branch para uma nova funcionalidade:** No seu repositório local, crie um branch chamado `feature/nova_funcionalidade`:
   ```bash
   git checkout -b feature/nova_funcionalidade
   ```
Desenvolva a funcionalidade: Faça as alterações necessárias no código para adicionar a nova funcionalidade. Pode ser algo simples, como adicionar um novo arquivo ou modificar um existente com novas funções.

Commit e Push: Faça commit das suas alterações e faça push do branch para o repositório remoto:

```bash
git add .
git commit -m "Adicionada nova funcionalidade"
git push origin feature/nova_funcionalidade
```

### Passo 2: Criar Branch para Correção Urgente
Crie um branch para correção urgente: Volte para o branch principal e crie um branch chamado hotfix/correcao_urgente:

```bash
git checkout main
git checkout -b hotfix/correcao_urgente
```

Desenvolva a correção: Realize as mudanças necessárias para corrigir o problema urgente.

Commit e Push: Faça commit das suas alterações e faça push do branch para o repositório remoto:

```bash
git add .
git commit -m "Correção urgente aplicada"
git push origin hotfix/correcao_urgente
```

### Passo 3: Merge dos Branches no Branch Principal
Merge da nova funcionalidade: Primeiro, faça merge do branch feature/nova_funcionalidade no branch principal:

```bash
git checkout main
git merge feature/nova_funcionalidade
```

Merge da correção urgente: Em seguida, faça merge do branch hotfix/correcao_urgente:

```bash
git merge hotfix/correcao_urgente
```

Push das alterações: Após resolver quaisquer conflitos que possam surgir, faça push das alterações do branch principal para o repositório remoto.

### Submissão
Após completar a tarefa, submeta um breve relatório na issue designada para este exercício no repositório de exercícios. Inclua links para os branches e pull requests criados, juntamente com uma descrição das funcionalidades ou correções implementadas.

### Reflexão
Como o uso de branches específicos para funcionalidades e correções impacta o fluxo de trabalho em projetos de software?
Quais desafios você encontrou ao trabalhar com múltiplos branches e como os superou?
Esperamos que este exercício tenha proporcionado uma compreensão prática do gerenciamento de branches no Git e como ele pode ser aplicado para melhorar o desenvolvimento colaborativo de software.
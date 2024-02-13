# Exercício 4: Push para o GitHub

## Objetivo

O objetivo deste exercício é praticar o envio de mudanças locais para o repositório remoto no GitHub. Isso é fundamental para compartilhar suas contribuições com outros colaboradores e manter uma cópia de segurança das suas mudanças na nuvem.

## Tarefa

### Passo 1: Verifique o Status do Seu Repositório

Antes de prosseguir com o push, verifique o status do seu repositório para garantir que todas as mudanças estão prontas para serem enviadas. No terminal, navegue até o diretório do seu repositório e execute:

```bash
git status
```

### Passo 2: Commit de Mudanças Pendentes
Se você tiver arquivos que foram modificados ou adicionados mas ainda não commitados, faça isso agora:

Adicione os arquivos à staging area com:

```bash
git add .
```
Faça o commit das mudanças:

```bash
git commit -m "Sua mensagem de commit"
```

### Passo 3: Faça Push das Suas Mudanças
Com seus commits prontos, envie-os para o GitHub com o comando:

Para o branch main:

```bash
git push origin main
```
Ou para o branch master, se for o caso:

```bash
git push origin master
```
### Passo 4: Verificação
Após o push, visite seu repositório no GitHub para verificar se as mudanças foram sincronizadas corretamente.

### Submissão
Complete a tarefa e submeta o link do seu repositório na issue designada para este exercício no GitHub. Compartilhe quaisquer desafios enfrentados e como você os superou.

### Reflexão
- Reflita sobre como o aprendizado deste exercício pode ser aplicado em projetos colaborativos.
- Discuta a importância de manter o repositório remoto sincronizado com as mudanças locais.
- Aguardamos suas submissões e estamos entusiasmados para ouvir sobre sua jornada aprendendo Git!
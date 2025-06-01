# 03 - Comandos Básicos

## git init
Inicializa um novo repositório Git em um diretório local.

### Exemplo:
**Bash**
mkdir meu-projeto
cd meu-projeto
git init

## git status
Mostra o estado atual do repositório: arquivos modificados, não rastreados e prontos para commit.

### Exemplo:
$ git status
On branch main

Untracked files:
  (use "git add <file>..." to include in what will be committed)
    index.html

## git add
Adiciona arquivos ou alterações à área de stage, preparando-os para o commit.

### Exemplo:
git add .

## git commit
Salva as alterações adicionadas (staged) com uma mensagem descritiva.

### Exemplo:
git commit -m "feat: adiciona página inicial"

## git log
Mostra o histórico de commits do repositório.

### Exemplo:
$ git log
commit 94e9a3df98223ac79e409d (HEAD -> main)
Author: Gui <gui@email.com>
Date:   Tue May 28 14:03 2025
    feat: adiciona página inicial

## Simulação fluxo completo

**Criação do projeto**

mkdir site-exemplo
cd site-exemplo
git init

**Criar um arquivo**
echo "<h1>Olá, mundo!</h1>" > index.html

**Verificar status**
git status

**Adicionar arquivo**
git add index.html

**Fazer commit**
git commit -m "feat: adiciona arquivo index.html"

**Ver histórico**
git log

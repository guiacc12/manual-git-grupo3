# 04 - Branches e Merge

## O que são Branches?

Branches são **linhas de desenvolvimento independentes** dentro de um repositório Git. A ideia é permitir que você trabalhe em novas funcionalidades, correções ou experimentos **sem afetar diretamente a branch principal** (geralmente chamada `main` ou `master`).

## Criar, Mudar e Deletar Branches:

**Criar:** git branch nome-da-branche

**Mudar:** git checkout nome-da-branche

**Deletar:** git branch -d nome-da-branche

### `git merge` e como lidar com conflitos:

**Comando Básico de Merge**
git checkout main
git merge nome-da-branche

**Lidando com Conflitos**
O Git marca os conflitos assim:

<<<<<<< HEAD
Código da branch atual (ex: main)
=======
Código da branch que está sendo mergeada (ex: nova-feature)
>>>>>>> nova-feature

**Resolver os conflitos:**
Edite o arquivo manualmente, removendo os marcadores (<<<<<<<, =======, >>>>>>>)
Escolha qual código manter (ou combine as alterações)


**Explicação passo a passo**

1. Criar branch
   git checkout -b ajuste-banner
2. Fazer alterações, depois:
   git add .
   git commit -m "feat: ajusta imagem do banner"
3. Voltar para main e aplicar o merge,
   git checkout main
   git merge ajuste-banner
4. Se tudo estiver certo, branch pode ser deletada:
   git branch -d ajuste-banner
   


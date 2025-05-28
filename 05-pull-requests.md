# 05 - GitHub e Pull Requests

## Criar conta no GitHub

1. Acesse [https://github.com](https://github.com)
2. Clique em **Sign up**
3. Preencha:
   - Nome de usuário
   - E-mail
   - Senha
4. Confirme seu e-mail e pronto!

## Criar repositório remoto

1. Após fazer login, clique no botão verde **"New"** ou vá em [https://github.com/new](https://github.com/new)
2. Preencha:
   - **Repository name** (ex: `nome-do-projeto`)
   - Descrição (opcional)
   - Marque como público ou privado
3. Clique em **Create repository**

## Clonar, Push e Pull

### Clonar um repositório (copiar para seu computador):

git clone https://github.com/seu-usuario/nome-do-repositorio.git

**Push**
git add .
git commit -m "feat: Descrição do commit"
git push origin nome-da-branch

**Pull**
git pull origin nome-da-branch

##Pull Requests e Revisão de Código
Um Pull Request (PR) é uma solicitação para mesclar mudanças de uma branch (geralmente de um colaborador) na branch principal (main).

1. Crie sua branch com o conteúdo novo
2. Envie com git push origin sua-branch
3. No GitHub, clique em "Compare & pull request"
4. Preencha o título e a descrição
5. Clique em "Create pull request"

**Revisar um Pull Request:**
1. Vá até a aba Pull Requests
2. Clique no PR
3. Verifique os arquivos modificados
4. Comente ou aprove com "Review changes"
5. Clique em "Merge pull request" para aceitar



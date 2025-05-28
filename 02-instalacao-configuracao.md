02-Instalação e Configuração do Git

Este tema mostra como instalar e configurar o Git rápido e fácil.

Como Instalar o Git

Para Windows:

1.  Baixe: (https://git-scm.com/download/win)
2.  Instale: Execute o .exe e siga as instruções básicas na caixinha que irá aparecer

Para Linux

Abra o terminal:

  Ubuntu/Debian:
    bash
    sudo apt update
    sudo apt install git -y
    
  Fedora/Red Hat:
    bash
    sudo dnf install git -y
    
2.1.3 Para macOS

Use o Homebrew no Terminal:

1.  Instale Homebrew (se não tiver):
    bash
    /bin/bash -c "$(curl -fsSL (https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh))
    
2.  Instale Git:
    bash
    brew install git
    
Verificando a Instalação

No Terminal (ou Git Bash), digite:

bash
git --version
///////////////////////////////////////////
Configurações Iniciais Essenciais:

primeiramente você precisa informar seu nome ao git, use esse comando

exemplo:
git config --global user.name "Seu Nome Completo"

logo em seguida o seu email, use esse comando

exemplo:
git config --global user.email "seu.email@example.com"

e para verificar se tudo está em ordem use esse comando
git config --list

algo importante é configurar a branch principal para 'main' em novos projetos

exemplo:
git config --global init.defaultBranch main

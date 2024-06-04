
# Sysadmin Guide

Bem-vindo ao Sysadmin Guide!

Este projeto é um guia de estudo dedicado a profissionais que desejam aprofundar seus conhecimentos em administração de sistemas e Linux. O material aqui apresentado é um recurso em constante construção, abrangendo desde conceitos básicos até tópicos avançados.

## Importante
**Este guia não é um treinamento oficial e nem substitui um treinamento oficial. A ideia deste repositório é coletar informações e links relacionados aos conhecimentos necessários para sysadmin.**

## Objetivo
O objetivo deste guia é fornecer uma base sólida para administradores de sistemas, abordando tópicos essenciais para o gerenciamento eficaz de sistemas Linux. Este material é ideal tanto para iniciantes quanto para profissionais experientes que buscam aprimorar suas habilidades.

## Estrutura do Guia
O conteúdo do Sysadmin Guide está organizado em temas, cada um focado em diferentes aspectos da administração de sistemas. Cada tema inclui explicações detalhadas, exemplos práticos e exercícios para reforçar o aprendizado.

## Dica Importante!
### Se você ainda não instalou o Red Hat Enterprise Linux recomendo dar uma olhada no Red Hat Developer Program

O Red Hat Developer Program oferece a **Red Hat Developer Subscription for Individuals**, uma assinatura gratuita destinada a desenvolvedores individuais. Com essa assinatura, você pode baixar e testar o Red Hat Enterprise Linux, entre outros produtos da Red Hat.

## O que está incluído:
- Red Hat Enterprise Linux Server (inclui GUI)
- Red Hat Software Collections e Application Streams
- Red Hat Developer Toolset e Compilers
- Diversos add-ons de infraestrutura do Red Hat Enterprise Linux

## Como obter:
Inscreva-se gratuitamente no Red Hat Developer Program em [developers.redhat.com/register](https://developers.redhat.com/register).

## Benefícios:
- Acesso às mesmas versões de software usadas em produção por empresas.
- Oportunidade de explorar e utilizar as tecnologias Red Hat sem custo.

## Como Instalar o RHEL 9

Excelente artigo com passo a passo do processo de instalação do RHEL 9 - [How to install RHEL 9 ](https://www.redhat.com/sysadmin/install-linux-rhel-9).

## Recursos Adicionais
### Laboratório Online
**Red Hat Enterprise Linux Open Lab**: Teste e valide comandos Linux em um ambiente de laboratório online. [Acesse em RHEL Open Lab](https://developers.redhat.com/learn/lessons/RHEL-open-lab).

### Temas Incluídos:
- **Acessar o Prompt de Comando e executar Comandos com Sintaxe Correta**
  - Terminals, shells, consoles, e command lines - [Terminals, shells, consoles, and command lines](https://www.redhat.com/sysadmin/terminals-shells-consoles) 
  - Acessar um shell prompt e emitir comandos com sintaxe correta - [How to access the Linux terminal](https://www.redhat.com/sysadmin/access-linux-terminal)
  - Execução de comandos básicos no Linux - [Linux Commands Cheat Sheet](https://developers.redhat.com/cheat-sheets/linux-commands-cheat-sheet-old)
  - Usar redirecionamento de entrada e saída (>, >>, |, 2>, etc.) - [How to manipulate files with shell redirection and pipelines in Linux](https://www.redhat.com/sysadmin/linux-shell-redirection-pipelining)
  - Usar grep analisar texto - [How to use grep](https://www.redhat.com/sysadmin/how-to-use-grep)
  - Usar grep e expressões regulares para analisar texto - [Manipulating text at the command line with grep](https://www.redhat.com/sysadmin/manipulating-text-grep)
  - Acessar sistemas remotos usando SSH - [How to access remote systems using SSH](https://www.redhat.com/sysadmin/access-remote-systems-ssh)
  - Fazer login e alternar usuários em alvos multiusuário - [Linux superuser access, explained](https://www.redhat.com/sysadmin/linux-superuser-access)
  - 10 comandos básicos do Linux - [10 basic Linux commands you need to know](https://www.redhat.com/sysadmin/basic-linux-commands)
  - **Laboratório**: Uma laboratório prático que aborda uma série de comandos essenciais, desde a localização de arquivos até a verificação de recursos do sistema - [Helpful Linux Commands](https://developers.redhat.com/learn/lessons/linux-commands)

- **Arquivar, Comprimir, Descompactar e Descomprimir Arquivos**
  - Arquivar, comprimir, descompactar e descomprimir arquivos usando tar, star, gzip e bzip2 - [Taming the tar command: Tips for managing backups in Linux](https://www.redhat.com/sysadmin/taming-tar-command)

- **Criar e Editar Arquivos de Texto**
  - Criar e editar arquivos de texto - [Linux basics: A beginner's guide to text editing with vim](https://www.redhat.com/sysadmin/beginners-guide-vim)

- **Gerenciar Arquivos e Diretórios**
  - Criar, deletar, copiar e mover arquivos e diretórios  - [Linux essentials: How to create and delete files and directories](https://www.redhat.com/sysadmin/basic-linux-commands)
  - Criar links físicos e simbólicos  - [Hard links and soft links in Linux explained](https://www.redhat.com/sysadmin/linking-linux-explained)
  - Listar, definir e alterar permissões padrão ugo/rwx  - [How to manage Linux permissions for users, groups, and others](https://www.redhat.com/sysadmin/manage-permissions)

- **Documentação do Sistema**
  - Localizar, ler e usar documentação do sistema, incluindo man, info e arquivos em /usr/share/doc  - [How to find out what a Linux command does](https://www.redhat.com/sysadmin/linux-command-documentation)

- **Criar Scripts Shell Simples**
  - Criar scripts shell simples  - []()

- **Execução Condicional e Laçosloop em ShellScripts**
  - Executar código condicionalmente (uso de: if, test, [], etc.)  - []()
  - Usar construções de laço (for, etc.) para processar entrada de linha de comando  - []()
  - Processar entradas de script ($1, $2, etc.)  - []()
  - Processar saída de comandos shell dentro de um script - []()

- **Operar Sistemas em Execução**
  - Inicializar, reiniciar e desligar um sistema normalmente
  - Inicializar sistemas em diferentes alvos manualmente
  - Interromper o processo de inicialização para obter acesso a um sistema
  - Identificar processos intensivos de CPU/memória e matar processos
  - Ajustar agendamento de processos
  - Gerenciar perfis de ajuste
  - Localizar e interpretar arquivos de log do sistema e journals
  - Preservar journals do sistema
  - Iniciar, parar e verificar o status de serviços de rede
  - Transferir arquivos entre sistemas de forma segura

- **Configurar Armazenamento Local**
  - Listar, criar e deletar partições em discos MBR e GPT - []()
  - Criar e remover volumes físicos - []()
  - Atribuir volumes físicos a grupos de volumes - []()
  - Criar e deletar volumes lógicos - []()
  - Configurar sistemas para montar sistemas de arquivos na inicialização usando ID universalmente único (UUID) ou rótulo - []()
  - Adicionar novas partições e volumes lógicos, e swap a um sistema sem destruição - []()

- **Criar e Configurar Sistemas de Arquivos**
  - Criar, montar, desmontar e usar sistemas de arquivos vfat, ext4 e xfs - []()
  - Montar e desmontar sistemas de arquivos de rede usando NFS - []()
  - Configurar autofs - []()
  - Estender volumes lógicos existentes - []()
  - Criar e configurar diretórios set-GID para colaboração - []()
  - Diagnosticar e corrigir problemas de permissões de arquivos - []()

- **Implantar, Configurar e Manter Sistemas**
  - Agendar tarefas usando at e cron - []()
  - Iniciar e parar serviços e configurar serviços para iniciar automaticamente na inicialização - []()
  - Configurar sistemas para inicializar em um alvo específico automaticamente - []()
  - Configurar clientes de serviço de tempo - []()
  - Instalar e atualizar pacotes de software da Red Hat Network, de um repositório remoto, ou do sistema de arquivos local - []()
  - Modificar o bootloader do sistema - []()  

- **Gerenciar Rede Básica**
  - Configurar endereços IPv4 e IPv6
  - Configurar resolução de nome de host
  - Configurar serviços de rede para iniciar automaticamente na inicialização
  - Restringir acesso à rede usando firewall-cmd/firewalld

- **Gerenciar Usuários e Grupos**
  - Criar, deletar e modificar contas de usuários locais
  - Alterar senhas e ajustar expiração de senha para contas de usuários locais
  - Criar, deletar e modificar grupos locais e associações de grupos
  - Configurar acesso de superusuário

- **Gerenciar Segurança**
  - Configurar configurações de firewall usando firewall-cmd/firewalld
  - Gerenciar permissões de arquivos padrão
  - Configurar autenticação baseada em chave para SSH
  - Definir modos de aplicação e permissivo para SELinux
  - Listar e identificar contexto de arquivos e processos do SELinux
  - Restaurar contextos de arquivos padrão
  - Gerenciar rótulos de porta do SELinux
  - Usar configurações booleanas para modificar configurações do sistema SELinux
  - Diagnosticar e resolver violações de política do SELinux

- **Gerenciar Containers**
  - Encontrar e recuperar imagens de container de um registro remoto
  - Inspecionar imagens de container
  - Realizar gerenciamento de containers usando comandos como podman e skopeo
  - Construir um container a partir de um Containerfile
  - Realizar gerenciamento básico de containers como executar, iniciar, parar e listar containers em execução
  - Executar um serviço dentro de um container
  - Configurar um container para iniciar automaticamente como um serviço systemd
  - Anexar armazenamento persistente a um container

### Sessões em Construção
- **Serviços de Rede:** Sessão focada em serviços de rede como DNS, FTP, DHCP, HTTP, etc. está em construção.

## Índice de Tópicos
- Acessando o Sistema
- Sistema de Arquivos
- Usuários e Grupos Locais
- Controle de Acesso a Arquivos
- Controle de Serviços
- Monitoramento de Serviços
- Gerenciamento de Armazenamento
- Ajuste de Desempenho do Sistema
- Configuração do Yum
- Redefinição de Senha Root
- Configuração de Rede
- Configuração de Nome de Host

## Recursos Adicionais
- [Documentação Oficial Red Hat](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/)
- [Red Hat Enterprise Linux Open Lab](https://lab.redhat.com/)

# Desafio Git/Github Bootcamp

Repositório do Desafio git/github Bootcamp Santander Full Stack

## Anotações 

### Estados

- Untraked (não rastreado)
  O arquivo ainda é desconhecido pelo git.

- Unmodified (não modificado)
  O arquivo ainda recebeu nenhuma modificação

- Modificado (modified)
  Arquivos forão modificados

- Preparado (staged/index)
  Arquivos estão preparados e esperando para serem "comitados"

- Consolidado (comitted)
  Os arquivos estão prontos e recebem nesta fase o sha1 e podem carregar uma mensagem que os identifique e/ou idenfique a alteração feita.

### Comandos:
- Ajuda
**Geral** 
  git help

**Comando específico**
- git help add
- git help commit
- git help <qualquer_comando_git>

### Configuração
**Geral***
As configurações do git são armazenadas no arquivo .gitconfig localizado dentro do diretório do usuário.

_Os comandos a seguir fazem alterações que são incluídas nos arquivos anteriores:_ 

- **Configurar usuário:** git config --global user.name "Seu username"
- **Configurar email:** git config --global user.email seuemail@email.com.br
- **Setar editor:** git config --global core.editor vim
- **Setar ferramenta de merge:** git config --global merge.tool vimdiff
- **Setar arquivos a serem ignorados:** git config --global core.excludesfile ~/.gitignore
- **Listar configurações:** git config --list

___(é interessante manter os dados de e-mail e name do cadastro do git iguais aos configurados)___



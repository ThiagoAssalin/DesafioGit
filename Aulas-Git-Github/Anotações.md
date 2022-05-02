[Sintaxe Basica Markdown](https://https://www.markdownguide.org/basic-syntax/)

##Comandos para trabalhar com chaves ssh

- ssh-keygen-t ed25519 -C email.@.com (gerando a chave)
- cat id_ed25519.pub (pegando a chave)
- eval $(ssh-agent -S) (criando um agente)
- ssh-add id_ed25519 (entregando a chave para o agente lidar com ela)


##Comandos basicos de navegação no terminal

Windowns        Unix
-cd             -cd (navegar entre pastas)
-dir            -ls (listar arquivos da pasta em questão)
-mkdir          -mkdir (criando uma pasta)
-del/rmdir      -rm-rf (excluindo arquivos/pastas)
-cls            -clear (limpando terminal)

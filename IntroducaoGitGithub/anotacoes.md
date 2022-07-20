# Introdução ao Git e Github

# Terminal

- cmd - para abrir
- cd - ir até diretório/pasta
- dir - listar pastas
- mkdir - criar uma pasta
- cd .. - voltar para pasta anterior
- del - deleta arquivo
- rmdir - deleta pasta
- cls - limpar tela
- seta pra cima - volta nos comandos anteriores

# Git

### SHA 1

- É um conjunto de funções hash criptográficas projetadas pela NSA ( Agência nacional de segurança
- A encriptação gera conjunto de caracteres identificador de 40 digitos - Único
- É uma forma de representar um arquivo

## Objetos internos do GIT

### Blobs

- guarda o SHA (id)
- contêm o tipo do objeto
- tamanho da string ou do arquivo
- armazena metadados do GIT

### Trees

- tem *blobs* dentro
- estruturas de onde está localizados os arquivos
- guarda o nome do arquivo

### Commits

- engloba tudo
- também possuem encriptação (SHA1)

## Chave SSH

- Uma forma de manter uma conexão segura entre duas máquinas
    - ssh-keygen -t ed… -C  e-mail
    - cd  /home/Users/meu-nome/.ssh/
    - ls
    - cat id_ed... .pub
    - copia chave e cola no github
    - eval $(ssh -agent -s)
    - ssh -add id_ed…

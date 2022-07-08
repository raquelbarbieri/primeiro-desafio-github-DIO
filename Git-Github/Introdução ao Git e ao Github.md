# Introdução ao Git e ao Github

### Link para download do git: 
https://git-scm.com/downloads

### Git Bash 
É um terminal estendido para otimizar o uso do Git. 

### Git
- É um sistema/software de versionamento de código distribuído
- Criado por Linus Torvalds, que também criou o Linux
- Software é feito de forma colaborativa, não é feito somente por uma pessoa 
- O Git foi criado para que várias pessoas pudessem trabalhar juntas ao mesmo tempo de forma fluida em um mesmo software
- Nasceu do descontentamento do Linus de trabalhar com softwares de versionamento de códigos ruins 

### GitHub
- Espaço para guardar códigos 

### Vantagens de usar Git e GitHub

- Armazenamento em nuvem
- Controle de versão 
- Trabalho em equipe 
- Melhorar seu código
- Reconhecimento

### Git
- é um CLI - command line interface
- Interagimos com ele por linha de comando

### SHA1
- pega uma foto ou arquivo e faz a sua encriptação 
- é uma forma curta de representar um arquivo 
- é composto por 40 caracteres
- se o arquivo não sofrer modificações, os 40 caracteres se mantêm iguais 
- mas se o arquivo sofrer qualquer modificação, como mudar uma vírgula por ponto, será gerado um novo código

### Objetos do SHA1: 
- Um está relacionado com o outro. 

1. blob: o arquivo de 40 caracteres do sha também armazena dentro dele metadados. Um dos objetos desses metadados é o blob. É o dado básico. É uma bolha. Só guarda o SHA1 do arquivo
2. tree: é o segundo objeto do metadado, é a árvore porque aponta para um blob ou para outras trees. Também guarda o nome do arquivo
3. Commit: aponta para uma tree, parente, um commit, autor e mensagem. Cada autor possui um commit único. O commit é o ato de jogar alguma coisa dentro do Git. Essa coisa vai ser linkada com a árvore pelos galhos.
- O Git é um sistema distribuído seguro porque tudo fica registrado. Qualquer alteração fica salvo dentro do histórico de commit. Uma vez que você altera o arquivo, você altera o commit. 

### Chaves SSH 
- é uma forma de estabelecer uma conexão segura e encriptada entre duas máquinas
- vai ter sempre uma chave pública e uma chave privada 
- a chave pública é inserida no GitHub para que o GitHub conheça a nossa máquina, que vai ficar configurada para mandar códigos para lá



 




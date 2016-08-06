# **GIT Educational**
  
## Brach Master

#### Passos para a o primeirp PUSH**
  
  
1. git add README.me
  1. Adicionar o arquivo README.me
  2. *git add .* tambem utilizado para adicionar todos os arquivos editados
2. git commit -m "comentário"
  1. Realizar os commit local no BRANCH master com o comentário das alterações
3. git push origin master 
  1. Enviar as alterações para o repositório remoto configurado anteriormente
  2. considerando **origin** o ALIAS para o servidor remoto e **master** o BRACH que estamos enviando para o servidor remoto
  
#### Comandos para a criação de BRACH
  
1. git checkout -b funcionalidadex
  1. Criar um novo BRANCH chamado funcionalidadex
2. git checkout master
  1. Retornar para o BRANCH master ou substituir **master** pelo BRACH que desja acessar
3. git brach -d funcionalidadex
  1. Remover o BRANCH funcionalidadex
4. git push origin funcionalidadex
  1. Enviar um BRANCH para o repositório remoto
  


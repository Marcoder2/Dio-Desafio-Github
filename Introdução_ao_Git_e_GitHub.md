# Introdução ao Git e ao GitHub :computer::email:

### O que é Git?? 

Sistema de Versionamento de código no qual através deles podemos desenvolver projetos na qual diversas pessoas podem contribuir simultaneamente no mesmo, editando e criando novos arquivos e permitindo que os mesmos possam existir sem o risco de suas alterações serem sobrescritas.

#### Fonte: https://tableless.com.br/tudo-que-voce-queria-saber-sobre-git-e-github-mas-tinha-vergonha-de-perguntar/



### Quais as Etapas do Arquivo dentro do Git :vertical_traffic_light:

- Os Arquivos ficam em dois estados que é Untracked e Tracked.
- Arquivos Untracked são arquivos que o Git ainda não tem conhecimento deles
- Arquivos Tracked são arquivos que tem conhecimento deles e eles passam por 3 etapas: unmodified, modified e staged.
- Quando usado o comando git init os arquivos passam de Untracked para Trecked no estado Unmodified.
- Se depois disso você modifica algo no arquivo seja uma virgula e salva de novo ele se move para modified.
- Se o arquivo seja Tracked no estado Unmodified ou Modified e você usa o comando git add, o arquivo vai para staged, pronto para ser commitado
- Se usar o comando git commit -m "descrição", o arquivo sai de staged e volta para Unmodified.
- Se quiser empurrar o Arquivo para a Nuvem então usamos o git push.



## O que é Github??

O GitHub é uma comunidade ou plataforma em Nuvem para Desenvolvedores compartilhar projetos e também colaborar com projetos compartilhados por outras pessoas.



### Quais etapas os arquivos passam pelo Git até serem empurrados para a nuvem?? :cloud:

- Primeiramente vamos criar um repositório ou um arquivo no caso o tipo que estamos usando é o .md (Markdown linguagem de marcação).

- Após isso vamos no terminal do Git Bash e caminhar até a pasta na qual queremos enviar/empurrar para a nuvem no caso sua página no GitHub.

- Após isso vamos usar o comando git init para iniciar o Git dentro desta pasta na qual estamos trabalhando.

- se dermos o comando ls -a , iremos listar as pastas e arquivos e encontraremos a pasta oculta .git/

- após a etapa anterior vamos configurar o git para que nosso projeto tenha um autor atrelado a ele, vamos usar o comando git config --global user.email "seu-email" e também o git config --global user.name "Seu Nick".

- Após tudo configurado podemos ir para a próxima que é usar o comando git add * (usamos o * pois ele ja seleciona todos os arquivos que precisam ser commitados).

- Após esta etapa do git add se usarmos o git status aparecera que o(s) Arquivo(s) esta(ão) em area de Stage, pronto para serem commitados.

- Então usamos o comando git commit -m "Comentário(s) do(s) arquivo(s)" (geralmente comenta-se algo relacionado ao arquivo/projeto).

- Agora é só empurrar o projeto para a Nuvem no caso o GitHub e para isso usamos o comando git push origin main. (ou master dependendo da forma em que esteja salvo).

- Pronto, agora é só atualizar a página e o(s) arquivo(s) vai(ão) estar tanto no seu diretório quanto na sua página na nuvem no caso GitHub. :smile:

  


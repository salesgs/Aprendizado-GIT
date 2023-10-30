<h2>O QUE É GIT</h2>

  <h3>O GIT é uma ferramenta que nos permite através da sua estrutura de repostiório acompanhar as alterações e novas versões dos nossos arquivos. Com ele podemos trabalhar de uma forma mais colaborativa, aonde várias pessoas podem trabahar no mesmos, facilitando assim a organização desse trabalho.</h3>


<h2>Principais comandos<h2>
<h3>
git init: 
  inicializa um repositório local contendo a pasta .git, essa pasta oculta contém toda a estruturação que o GIT irá utilizar para fazer o controle desses arquivos, pastas essas como: hooks,info, object e refs. 
</h3>
 <h3>
  git status:
    Esse comando nos permite checar o estado dos nossos arquivos no que diz respeito ao saber do GIT sobre esses arquivos. Há possíveis estados para um arquivo como, Monitorado: arquivos que o git tem a ciência de sua existência, os monitorados podem ser inaltarados, modificados ou selecionados. Temos também o estado de Não Monitodado: são arquivos ou pastas que o git ainda não tem ciência, ou seja não forma selecionados.
 </h3>
  <h3>  
  git add .
   Esse comando adiciona os arquivos ou pastas para à àrea de seleção para "commit". Ou seja esse comando antecede o commit selecionando tudo aquilo que queremos commitar.

   git commit -m "mensagem"
   Esse comando salva as alterações trazendo uma mesagem e um algoritmo de hash gerado para esssa alteaçao.
</h3>

<h2> Instalando e configurando</h2>
<h3> Ao baixo o git no site oficial precisamos no terminal definir configurações importantes como: "user.name" e o "user.email".
  git config --global user.name "nome"
  git config --global user.email "email"

  as flags ao invés de --global podem ser --local configurando as propriedades para um trablho local ao invés de global.</h3>

  <h2>Branch<h2>
  <h3>
  Branchs 
  São ramos de desenvolvimento isolados do ramo principal "master". Tem como principal conceito ter funcionalidades contidas que se diferem do ramo principal "master". Exemplo branchs de conexão ao banco de dados, conexão API etc.. Esses ramos podem se mesclar ao ramo principal trazendo assim para o ramo principal as alterações que ele não possuem. O ramo destinto do principal não sofre alterações, somente o ramo principal.

  criando branch 
  
  Criando e naveganto 
 Criando e navegando para o ramo criado: git checkou -b novaBranch  

  Navegando entre branhcs
  Navegando para o ramo principal: git checkout master
  </h3>
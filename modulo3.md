Módulo 3: Colaboração e revisão de alterações

## 1. Objetivo do módulo 

O objetivo deste módulo é aprender como trabalhar em equipe utilizando o GitHub, compartilhando repositórios, convidando colaboradores e organizando alterações por meio de branches, pull requests, revisões e merges. 

Ao final deste módulo, seremos capazes de colaborar em projetos de forma organizada, segura e eficiente. 

## 2. Convidando colaboradores para um repositório 

O GitHub permite adicionar outras pessoas a um repositório para que elas possam participar do desenvolvimento do projeto. 

**Passo a passo:**

1. Acesse o GitHub e entre na sua conta. 

2. Abra o repositório desejado. 

3. Clique em Settings (Configurações). 

4. Acesse a opção Collaborators (Colaboradores) ou Collaborators and teams (Colaboradores e times). 

5. Clique em Add people (Adicionar pessoas). 

6. Digite o nome de usuário ou e-mail da pessoa. 

7. Selecione a pessoa e envie o convite. 

8. O colaborador deverá aceitar o convite para ter acesso ao repositório. 

## 3. Como compartilhar um repositório

Compartilhar um repositório permite que outras pessoas visualizem o código e, dependendo das permissões, participem do desenvolvimento. 

Importante: Em repositórios públicos, qualquer pessoa pode visualizar o conteúdo. Em repositórios privados, é necessário conceder acesso aos colaboradores. 

1. Acesse o repositório no GitHub. 

2. Clique no botão Code. 

3. Copie o endereço HTTPS do repositório. 

4. Envie o link para a pessoa com quem deseja compartilhar. 

Exemplo: https://github.com/usuario/nome-do-repositorio

## 4. O que é uma branch? 

Uma branch (ramificação) é uma versão independente do desenvolvimento de um projeto.

Ela permite realizar alterações sem modificar diretamente a branch principal, geralmente chamada de main.

As branches são importantes porque permitem que diferentes pessoas trabalhem em funcionalidades ou correções ao mesmo tempo, sem prejudicar o código principal.


1. Acesse o GitHub pelo navegador.
2. Entre no repositório desejado.
3. Na página inicial do repositório, localize o botão de seleção de branches, onde aparece main.
4. Clique nesse botão.
5. Digite o nome da nova branch, por exemplo, teste.
6. Clique na opção Create branch: teste from main.

A nova branch foi criada com sucesso.


1. Certifique-se de que a branch teste está selecionada.
2. Abra o arquivo README.md.
3. Clique no ícone de lápis (Edit this file).
4. Adicione a seguinte informação.
5. Clique em Commit changes.
6. Escreva uma mensagem explicando a alteração, por exemplo: Adiciona nova funcionalidade.
7. Confirme o commit.
8. A alteração foi salva diretamente na branch teste, sem modificar a branch principal main.

## 5. Realizando uma alteração na branch 

Depois de criar uma branch, podemos editar os arquivos do projeto diretamente pelo navegador do GitHub. Assim, as alterações ficam salvas na nova branch, sem modificar a versão principal.

1. Acesse o repositório no GitHub.
2. Selecione a branch teste.
3. Abra o arquivo README.md.
4. Clique no ícone de lápis (Edit this file).
5. Adicione uma nova informação ao arquivo.
6. Clique em Commit changes.
7. Escreva uma mensagem para identificar a alteração.
8. Confirme o commit.

## 6. O que é um Pull Request? 

Um Pull Request é uma solicitação para que as alterações realizadas em uma branch sejam revisadas e incorporadas a outra branch. 

Ele permite que os integrantes da equipe analisem o código antes de aprovar sua integração ao projeto principal. 

Para que serve? 

-Apresentar alterações realizadas no projeto. 

-Permitir que outros colaboradores revisem o código. 

-Identificar erros antes de incorporar as mudanças. 

-Discutir melhorias e sugerir modificações. 

-Organizar o trabalho em equipe.

## 7. Como abrir um Pull Request 

1. Acesse o repositório no GitHub. 

2. Entre na aba Pull requests. 

3. Clique em New pull request. 

4. Selecione a branch principal (main) como destino (base). 

5. Selecione a branch de teste (teste) como origem (compare). 

6. Confira as alterações apresentadas. 

7. Clique em Create pull request. 

8. Adicione um título e uma descrição explicando a alteração. 

9. Clique novamente em Create pull request. 

## 8. Revisão de alterações 

A revisão de alterações é o processo de analisar o código enviado em um Pull Request antes de aprová-lo. Durante a revisão, os colaboradores podem: 

-Verificar se o código funciona corretamente. 

-Identificar erros e problemas. 

-Sugerir melhorias. 

-Comentar trechos específicos do código. 

-Aprovar ou solicitar alterações.

## 9. O que é Merge? 

Merge é o processo de unir as alterações de uma branch em outra. 

Por exemplo, depois que uma alteração realizada na branch teste é revisada e aprovada, podemos incorporá-la à branch principal main. 

realizando o merge 

1. Acesse o Pull Request criado. 

2. Confira se as alterações foram revisadas. 

3. Clique em Merge pull request. 

4. Confirme em Confirm merge. 

## 10. Desafio prático

Atividade: trabalhando em equipe com GitHub

Agora que aprendemos a utilizar os recursos de colaboração do GitHub, vamos colocar os conhecimentos em prática.

A atividade consiste em criar um repositório no GitHub e convidar pelo menos um colega para participar do projeto. Depois de compartilhar o repositório, deverá ser criada uma nova branch chamada melhoria, na qual será realizada uma alteração no arquivo README.md, adicionando uma nova seção ao conteúdo.

Após realizar a alteração, será necessário salvar as modificações utilizando um commit e abrir um Pull Request para solicitar a incorporação da mudança à branch principal (main).

Outro integrante da equipe deverá revisar a alteração, verificar se está correta e aprová-la. Depois da aprovação, deverá ser realizado o merge para incorporar a modificação à branch principal.

Para finalizar, todos deverão acessar a branch main e conferir se a alteração foi incorporada corretamente.

Objetivo: Praticar o trabalho em equipe utilizando branches, commits, Pull Requests, revisão de alterações e merge pelo GitHub.
# Contribuindo com o Hacktoberfest

Este é um documento extraído do hands on (mão na massa) apresentado no Hacktoberfest Campinas 2018 e tem como objetivo ajudar iniciantes a contribuírem pela primeira vez.

O conteúdo deste guia é resumido e não aborda questões avançadas de uso do GitHub ou Git, para aqueles que queiram se aprofundar, recomendamos o **curso gratuito ”Git e GitHub”** disponível no Udemy desenvolvido por **Bruno Orlandi**:
> https://www.udemy.com/git-e-github/ (Bruno Orlandi)

## Requerimentos
É importante que você já tenha uma conta no GitHub e tenha instalado no seu computador o Git.

* Criar conta no GitHub: [github.com/join](https://github.com/join?source=header-home)

* Download do Git: https://git-scm.com/downloads
-- Windows: https://git-scm.com/download/win
-- MacOS: https://git-scm.com/download/mac
-- Linux: $ apt-get install git
-- Outras distro: https://git-scm.com/download/linux

## Como contribuir
Para contribuir é muito simples, basta ajudar qualquer repositório / projeto hospedado pelo GitHub, resolvendo um problema (issue) reportado por outros usuários ou que você mesmo tenha encontrado.

## Git e GitHub
O Git é um sistema de controle de versão distribuído e é ele que faz a gestão dos repositórios entre os servidores remotos (Nuvem) e nosso computador, o GitHub hospeda repositórios e fornece uma interface e recursos para gerenciá-los.

Para iniciarmos a contribuição em qualquer repositório GitHub precisamos entender alguns conceitos.

### Criando o fork (bifurcação)
O **fork** é uma cópia remota de um repositório de terceiro em seu estado atual. Todo repositório de outra pessoa ou time está disponível apenas para visualização, você não poderá modificá-los, por isso, ao encontrarmos um projeto para contribuir devemos criar um **fork** para a nossa conta, criando um repositório idêntico ao original.

O fork é um recurso do GitHub e seu processo ocorre inteiramente na interface do GitHub.

### Clonando o repositório
O **clone** é uma cópia local de um repositório remoto, você pode clonar qualquer repositório, porém, apenas os repositórios da sua conta poderão receber as alterações realizadas localmente.

O **clone** é um recurso do Git e o processo ocorre em duas etapas :
* Obter a url do repositório
* Executar o comando `git clone [url do repositório]` no seu computador para efetuar a cópia.

### Enviar as alterações (Commit-Push)
Agora que já clonamos e fizemos as alterações necessárias, vamos enviar as modificações para o nosso repositório (Fork) remoto.

#### Commit
O *commit* é um recurso do Git, e permite salvar as modificações no histórico local.

Todos os comando a seguir são recursos do Git. 

**Passos para o commit:**
* Verificar o status de modificação (Quais arquivos foram modificados)
> Comando: `git status`
* Adicionar modificação ao commit
> Comando: `git add [path/nome_arquivo]`

* Criar o commit
> Comando: `git commit -m "Descrição do commit"`

O **commit** pode ser executado diversas vezes durante o desenvolvimento, recomendamos a criação de um commit após toda modificação importante.

#### Push
Uma vez criado o **commit**, temos agora modificações no repositório local prontas para serem enviadas para o repositório remoto.

O **push** é um recurso do Git e é responsável por enviar o histórico local de modificações para o repositório remoto.

> Comando: `git push`

### Pull Request
A **Pull request** é um recurso do GitHub e permite enviar para um repositório de terceiro, modificações efetuadas em um repositório seu, neste guia, o repositório é um fork do repositório que irá receber as modificações.
As suas modificações não são mescladas diretamente ao repositório destino, mas agora, você poderá solicitar ao dono do repositório que aplique o conteúdo caso esteja de acordo com o que foi modificado, caso contrário ele poderá rejeitar, encerrando a solicitação.


**Todo o processo de criação da PR é executado na interface do GitHub:**
* Visite o seu repositório **fork**
* Clique em **New Pull Request**

### Descobrindo um projeto
Agora que os conceitos básicos foram esclarecidos, precisamos encontrarmos um projeto para iniciarmos a primeira contribuição.
Para ajudar na busca por projetos, criamos uma lista com repositórios relacionados às tecnologias e assuntos relacionados às comunidades participantes, o seu primeiro passo é encontrar um projeto para você.

No dia-a-dia, registrar problemas encontrados ou dúvidas sobre o projeto também é uma forma de contribuir, use sempre o painel de problemas (issues) para reportar algo ou notificar alterações.

## Fontes
* http://jlord.us/git-it/challenges/forks_and_clones.html
* https://hacktoberfest.digitalocean.com/
* https://www.udemy.com/git-e-github/
* https://lab.github.com/
* http://jlord.us/git-it/challenges/branches_arent_just_for_birds.html
* https://medium.com/@kenwarner/command-line-ux-matters-too-improve-your-git-status-colors-170de858953d

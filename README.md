<h1>Git studies</h1>

## 🎯tecnologias
  <img src = "https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)"><img src = "https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)"><img src = "https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)">

# Team 

  <img src = "https://avatars.githubusercontent.com/u/147282295?s=96&v=4">

<h2>📖English</h2>
<p>Content that i learned during my first three months of studing.

1-	Creating github account to share projects.<br>
2-	Set up my git account and the git program on my computer.<br>
3-	Creating a git repositorio.<br>
4-	Configuring the connection between the local and  remote repositori.<br>
5-	Cloning the repositori without the download, because i 	wanted more then just 	the files.<br>
6-	Testing commits and restoring files.<br>
7-	Learning how to add collaborators in my project on 	github.<br>
8-	Using the right commands to check what have changed in 	the project.<br>
9-	becoming familiar with the open source concept.<br>
10-	Creating a project fork which  mean two things:<br>
		I- hard fork → both project are separated in a 	permanent way.<br>
		II- soft fork → all changes in the code can be 	incorporated on the main  project.<br>
11-	Opening Pull Requests.<br>
12-	Simulating conflicts (!) issues and solving then.<br>
13-	Reverting commits using <git revert “ID”>, that id is 	possible to get by using <git log> to see the commit’s id.<br>
14-	Trying out < git reset –hard “id” >, that parameter (--	hard) means that im not only reverting the commit but 	also eliminating from the log as well.<br>
15-	Changing the commit message with <git commit –amend -m 	“correct msg” <br>
16-	Learning how important is to create a Read.md to get 	everyone into the project with context. (MD = markdown).<br>
17-	Using <.gitignore> .<br>
18-	Sharing codes with Gist. <br>
</p>  
<h2> 📖 Portuguese </h2>


*  Controle de histórico .<br>
*  Trabalhar em equipe no mesmo projeto .<br>
*  Logs Detalhados.<br>
*  Trabalhar de forma isolada em seu próprio ambiente.<br>
*  Eliminar sujeita em código e duplicidade.<br>

* GIT =

   		Software de controle de versão LOCAL <br>
		precisa criar um diretório e dentro do diretório inicializar o git<br>
		para fazer todo controle e dimensionamento de código no ato. <br>

* GITHUB = 	Plataforma de repositório remoto:
		
  		(Armazenar nuvem).<br>
		Funciona como rede social de desenvolvedores.<br>
		Funciona como portifoleo.<br>

		REPOSITÓRIO LOCAL 	→ Envio (PUSH) →  HUB <br>
		REPOSITÓRIO DIFERENTE	→ Envio (PUSH) com autorização → HUB <br>

* INSTALADO GIT → 

		credenciais de usuário no git bash → <br>
		charl@Chur MINGW64 ~<br>
		git config --global usar.name "ChurleMaster"<br>

		charl@Chur MINGW64 ~<br>
		$ git config --global user.email "charlie_cwv@hotmail.com"<br>


<h3>O QUE É UM REPOSITÓRIO ? Aula 4 </h3> <br>

	OBS. ( git config user.name ou user.email caso esquecer algo)<br>

	OBS.2 (Clear para limpar) / (Apertar pra cima ainda mostra histórico)<br>

	REPOSITÓRIO é o local que os arquivos do projeto serão 	armazenados ou seja quando iniciamos um projeto com o 	GIT, estamos criando um repositório para aquele projeto.<br>


<h3>REPOSITÓRIOS MAIS CONHECIDOS: </h3> <br>

* 	1- Github 
*	2- Bitbucket 
*	3- Gitlab


<h3>INICIANDO REPOSITÓRIO MODIFICAÇÕES: AULAS 5 e 6 </h3> <br>


	COMANDO → <br>
	(Git init na pasta que deseja incluir após abri-la com o GIT BASH)<br>

* 1- 	Criar a pasta (Confirmar pastas ocultas)<br>
* 2- 	Criar um projeto dentro e iniciar com GIT BASH HERE<br>

	OBS. →

		(É interessante ver se as pastas .git já estão 	dentro do projeto).<br>
	OBS. →

		(Testar as pastas pelo terminal com GIT STATUS).<br>

* 3- 	Usar Code .

  		(Dentro do terminal para abrir o visual studio)<br>
		Clicar em terminal dentro do Visual Studio <br>
		Mudar o prompt de comando para configuração Git Bash<br>

* 4-	Criar a folha:
  
  		 Index.Html <br>
		Adicionar ela com o comando “ Git add “Index.Html” <br>
		Testar com git status <br>

* 5-	Assim que qualquer coisa for adicionado ao arquivo e ele for salvo, ocorrerá a modificação de Status para = M, 	portanto o monitoramento mostra que alguém fez alguma modificação.<br>

		OBS. → (UNTRACKED significa “o arquivo esta sendo visto pelo GIT”)
  		Ou seja, não esta apto a ser versionado ou 	monitorado.
		As siglas U = untracked e A = Adicionado M = 	Modificado R = Renamed.

* 6- 	Apos a modificação e necessário incluir o arquivo ao git mais uma vez então preciso definir se ele sera Restored 	ou Commited <br>

	OBS. →

 		Git Restore <file> serve para reverter as alterações,ou, mandar o arquivo para ser commitado (Validada as informações) com Git add <file>.
  		Contudo normalmente não e usado o nome do arquivo individual, e sim GIT ADD .
  		De forma que será adicionado todos os arquivos dentro desse repositorio	monitorado pelo GIT


<h3>SOBRE COMMIT → AULA 7 </h3> <br>


* 1- 	Git commit NOME.HTML -m “ estou criando a pagina “ <br>

* 2-	-m é uma flag de mensagem / aviso <br>
  
* 3- 	Depois de confirmar os COMMITS e checar as modificações usar git status para obter WORKING TREE CLEAR.<br>

* 4-	Usar ( GIT ADD . ) para incluir os arquivos no 	monitoramento e deixar os modificados prontos para o 	commit.<br>
	
	Usar ( GIT COMMIT ) Para commitar todos os arquivos de 	uma vez e obter a analise do que foi feito, adicionado, 	inserido, deletado. <br>

	OBS. → Sempre utilizar -m para deixar o comentário sobre 	a ação especifica. <br>

	EX “ FINALIZADO A MODIFICAÇÃO REQUISITADA”.<br>

* 5-	O comando (git rm) é usado no Git para remover arquivos do índice (staging area) e do diretório de trabalho. <br>

		OBS.→ UTILIZAR <COMMIT> depois do <RM> para autorizar.<br>
		Este comando é frequentemente utilizado quando você deseja excluir arquivos do seu repositório Git de forma controlada.<br>
		A sintaxe básica do comando é:<br>

		<git rm <nome_do_arquivo><br>
		Aqui estão algumas opções comuns do comando git rm:<br>
  
* 	5.1- 		--cached:<br>

       		 ◦ Remove apenas o arquivo do índice (staging area), mantendo-o no diretório de trabalho.<br>
       
       		   <git rm --cached <nome_do_arquivo><br><br>

* 	5.2-	2-r ou –recursive :<br>

		Usado para remover recursivamente diretórios e seu conteúdo.<br>
		git rm -r <nome_do_diretório><br>

* 	5.3-	--force:<br>

		Força a remoção do arquivo, mesmo se ele estiver modificado no 	diretório de trabalho. Útil quando você deseja excluir arquivos que foram modificados sem commit.<br>
         	 <git rm --force <nome_do_arquivo><br>
*	5.4-
		--dry-run:<br>
  
		Permite visualizar o que seria removido sem realmente executar a remoção.<br>
  		<git rm --dry-run <nome_do_arquivo><br>
          

*	5.5- 
		-n ou –dry-run:<br>
  
        	  Uma abreviação para --dry-run.<br>
         	 <git rm -n nome_do_arquivo><br>

*	 5.6- -q ou –quiet:<br>

         	 Suprime mensagens de saída, exceto erros e mensagens de status.<br>
       	 	 <git rm -q <nome_do_arquivo><br>
 	 		Lembre-se de que após usar git rm, você também 	precisa realizar um commit para efetivar a remoção. Por exemplo:<br>
			 git commit -m "Remover <nome_do_arquivo>"<br>
  			 ste comando adiciona um novo commit que reflete a remoção do arquivo ou diretório especificado.<br>

* 	5-7	<CNTR+C> →  igual a sair no terminal <br>
		(apertar varias vezes se precisar com 	paciência) e 	depois INPUTAR: <br>
		<:qa!> → Dois pontos significa VOU INPUTAR o  COMANDO. <br>
		<:CP!> → Comando de copia<br>


<h3>CONHECENDO O GITHUB → AULA 8</h3> <br>

* 1- 	É o Serviço de armazenar e gerenciar repositórios <br>

* 2- 	Podemos subir nossos repositórios para outros devs gerenciarem versões dos projetos e ou trabalho em equipe.<br>



<h3>ADICIONANDO REPOSITÓRIO GIT → AULA 9 </h3> <br>

* 1- 	Adicionar novo repositorio ao github .<br>

* 2- 	Criar uma BRANCH.<br>

		<git branch -m main><br>

* 3- 	Linkar seu repositorio com o github.<br>

		<git remote add origin github.com:Churle/HTML5.git> e depois <Git push -u origin main> <br>

* 4-	Conferir se existem chaves no computador.<br>

		<ls -al ~/.ssh><br>

* 5- 	Gerando uma nova chave.<br>

		<ssh-keygen -t ed25519 -C “seu e-mail do github”><br>

	Ele ira pedir para locar o arquivo é só apertar enter e depois criar o PIN/Password. <br>

* 6-	Rodar o ssh-agent: eval $(ssh-agent -s). 

	(ele ira achar o Agent pid que é um processo de localização de ID).<br>

	OBS.→ O ssh-agent é uma ferramenta que funciona como um gerenciador de chaves SSH, facilitando o uso seguro de chaves privadas para autenticação em conexõesSSH. O agente mantém suas chaves privadas na <br>	memória durante uma sessão de login, permitindo que você use-as para se autenticar em vários servidores remotos sem precisar digitar a senha ou a passphrase a cada vez. <br>

* 7-	Incluir a chave privada: ssh-add ~/.ssh/id_ed25519<br>

* 8-	Copiar chave pública.<br>

	Agora que já adicionamos a chave privada no ssh-agent, 	vamos copiar a chave pública que faz par com ela, para concluirmos no nosso github. No mesmo terminal. <br>
	executar:<br>
     		 No Windows: clip < ~/.ssh/id_ed25519.pub. (<br>
     		 Automaticamente o conteúdo da sua chave pública será copiado para a área de transferência).<br>
      
* 9-	Exibir a chave publica no terminal para alocar no github.<br>
			
		<cat ~/./id_rsa.pub>	
		
<h3>Adicionando novos arquivos → Aula 10</h3> <br>
* 1-	GIT PUSH empurra os arquivos para o repositorio externo.<br>

<h3>Recebendo Arquivos Pull → Aula 11 </h3> <br>
* 1-	Exemplo: Criar o README.md para interagir com o 	repositorio inicial.<br>

* 2-	Vai haver uma verificacao de key, em caso de problemas 	utilizar :<br>
				
		ssh agent:   eval “$(ssh-agent -s)”

		adicionando a chave: ssd-add ~ /.sshid_ed25519

<h3>Clonando Repositórios → Aula 12 </h3> <br>

* 1-	Criar uma pasta “clone” dentro da paste que esta o 	projeto.<br>

* 2-	Copiar o projeto no github.<br>
	
* 3-	Abrir pelo gitbash e digitar: <br>

		GIT CLONE git@github.com:Churle/gitclass.git

* 4-	Caso queira mudar de repositorio, apagar a pasta nova 	criada dentro da pasta clone e :<br>

		$ CD .. (/com/caminho/diretorio/novo)

* 5-	Caso quiser conferir qual repositorio esta utilizando:<br>

		pwd

* 6-	Caso queira ver o conteudo do diretorio usar:<br>

		ls ou ls/path/to/your/directory

* 7-	Portanto usar consecutivamente:<br>
	
		$ cd..
		$ ls
		$ cd cloneprojeto1
		$ git clone “nome do repositorio” espaco+ponto


<h3>Acessando LOGS → Aula 13</h3> <br>

* 1-	Comando novo <git log> , mostrando o ultimo commit 	no 	topo sempre.<br>

* 2-	Press <q> para sair.<br>

<h3>Revertendo arquivos com checkout ou restore → Aula 14</h3> <br>

* 1-	Comando <git restore “nome do arquivo”>.<br>

* 2-	Comando <git checkout “nome do arquivo”>.<br>

* OBS.→ 	o simbolo $ dentro do terminal, significa que o operador esta operando o sistema como usuario comum.<br>
<br>
* OBS2.→ 	o Visual studios e uma IDE = integrate development environment.
<br>
<h3>Como ignorar arquivos → Aula 15 </h3> <br>

* OBS.→ 	utilizar o arquivo <.env.local> para criar uma pagina contendo as variaveis do projeto, como senha_api por exemplo.<br>
		
			$ .env.local
			senha_api
			senha_api = xxxx

* OBS2.→ 	Geralmente o projeto tera a pasta <node_module> antes><br>

* 1-		Criando o arquivo de ignorar <.gitignore> .<br>

* 2-		Todos os arquivos dentro do arquivo acima serao ignorados, PORTANTO não serao enviados ao repositorio 	externo, exemplo abaixo: <br>

		<.gitignore>	
		/node_modules (pasta criada para aula)
		.env.local (arquivo criado para aula)

<h3>Dando o comando RESETE → Aula 16</h3> <br>

* 1-		Esse commit não volta atras então tomar cuidado.<br>

* 2-		Comando <git reset -- hard origin/ main> <br>
		(eles esta voltando para origin da brach main, porque 	é a única que tenho no momento, se tivesse mais poderiamos escolher).<br>

* 3-		Elá volta para a configuração padrão designada.<br>

<h3>O que são BRANCHS → Aula 17</h3><br>

* 1-		Branch é simplesmente uma maneira que o git disponibiliza para separar projetos.<br>

* 2-		A Branch inicial se chamará main<br>

<h3>Criando Branch → Aula 18</h3><br>

* 1-		<git branch> :

 		mostra qual branch temos e qual esta ativa no momento. Importante deixar claro que o certo e criar as novas branchs a partir da branch main.
  		Portante sempre conferir com <git checkout><br>.

* 2-		Criando a brach nova com o comando:<br>

			<git branch “nome”> <br>
			ex:<br>
			< git branch pagina_home> 
			Utilizar sempre letras minusculas e separar as 	palavras com underline (por convencao).

<h3>Mudando de branch e criando uma abrindo direto nela → Aula 19.</h3><br>

* 1-		A principio criamos a branch “pagina_home” para trabalhar no index sem precisar mexer na branch main.<br>

* 2-		Para trocar de branch usar o comando:<br>
		
			<git checkout “nome”>

* 3-		Para enviar a branch nova no repositorio externo:<br>
		
			<git push origin nome_nome >

* OBS.→ 	O nome UPSTREAM significa branch remota correspondente.<br>


* 4-		Para SETAR a branch com a upstream usar :<br>

			<git push --set-upstream origin nome_nome>

* 5-		Para criar a BRANCH e ja iniciar ela, utilizar o comando:<br>
	
			<git checkout -b “nova_branch”>
<br>
<h3>Deletando uma BRANCH → Aula 20</h3>

* 1-		Usar o comando:

   			  <git branch -d nome_nome><br>
			Contudo isso apenas exclui o repositorio local!

* 2-		Para deletar do repositorio remoto (ex GIT HUB), usar 	o comando:

    			<git push origin -- delete nome_nome ><br>

<h3>Unindo branch GIT MERGE pelo GITHUB → Aula 21</h3><br>

* 1-		Antes de mais nada, retornar a BRANCH MAIN.<br>
* 2-		Comando para MERGE: <git merge nome_nome><br>
* 3-		Se fizer MERGE por meio de PUSH REQUEST direto do GIT 	HUB, lembrar de atualizar o repositorio local ou <git pull>.<br>



<h3>Realizando Simulacao de trabalho com BRANCHS ultrapassadas →Aula 22.</h3><br>	

1-		Alterar a branch main, faz as outras ficarem ultrapassadas/ out off date.<br>

2-		Estando em outra branch e querendo atualizar, usar o comando:<br>

			<git merge main> → De forma que puxaremos as atualizacoes da branch desejada para a branch que	estamos.

<h3>GIT STASH → Aula 23 </h3><br>

* 1-		Git Stash e um comando que volta para as configuracoes originais do meu ultimo PUSH (e como se 	fosse um rewind), e o comando e :<br>

  		<git stash>.	

* 2-		Stash apaga as modificacoes voltando ao original do ultimo push e cria um arquivo em formato de codigo ex:

  		d80cf0a. <br>

<h3>Recuperation um STASH → Aula 24 </h3><br>

* 1-		Utilizando o comando: <git stash list>, e possivel ver o que temos armazenado no stash.<br>

* 2-		Utilizando o comando: <git stash apply “1”>, e possivel retornar o stash de acordo com a ordem 	deles, portanto usei o 1 no caso de termos 2 ou mais stashs guardados.<br>

* 3-		Utilizando o comando: <git stash pop>, sera possivel utilizar o stash mais recente e o remover da lista ao mesmo tempo.<br>

<h2>((Curso Finalizado))</h2><br>

<h3>Extraindo arquivos de outras branchs → Estudo 1</h3><br> 

* 1-		Utilizar:
* 		 <git checkout branch_Name> para se mover a branch  que voce quer receber a pagina.<br>

* 2-		Em seguida utilizar o comando:
* 		<git checkout branch_Name arquivo_name.xxx>.  <br>




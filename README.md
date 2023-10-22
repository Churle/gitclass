<h1>Git studies</h1>

## 🎯tecnologias
  <img src = "https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)">
  <img src = "https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)">
  <img src = "https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)">

# Team 

  <img src = "https://avatars.githubusercontent.com/u/147282295?s=96&v=4">

<h2>📖Sobre</h2>
  
<p>GIT e GITHUB  AULAS 1, 2 e 3 

→ Controle de histórico .
→ Trabalhar em equipe no mesmo projeto .
→ Logs Detalhados.
→ Trabalhar de forma isolada em seu próprio ambiente.
→ Eliminar sujeita em código e duplicidade.

GIT =	Software de controle de versão LOCAL 
		precisa criar um diretório e dentro do diretório 			inicializar o git
		para fazer todo controle e dimensionamento de código 		no ato. 

GITHUB = 	Plataforma de repositório remoto (Armazenar nuvem).
		Funciona como rede social de desenvolvedores.
		Funciona como portifoleo.

	REPOSITÓRIO LOCAL 	→ Envio (PUSH) →  HUB 
	REPOSITÓRIO DIFERENTE	→ Envio (PUSH) com autorização → 	HUB 

	INSTALADO GIT → credenciais de usuário no git bash → 

	charl@Chur MINGW64 ~
	git config --global usar.name "ChurleMaster"

	charl@Chur MINGW64 ~
	$ git config --global user.email 	"charlie_cwv@hotmail.com"


O QUE É UM REPOSITÓRIO ? Aula 4

	OBS. ( git config user.name ou user.email caso esquecer 	algo)

	OBS.2 (Clear para limpar) / (Apertar pra cima ainda 	mostra histórico)

	REPOSITÓRIO é o local que os arquivos do projeto serão 	armazenados ou seja quando iniciamos um projeto com o 	GIT, estamos criando um repositório para aquele projeto.


REPOSITÓRIOS MAIS CONHECIDOS → 

	1- Github 
	2- Bitbucket 
	3- Gitlab


INICIANDO REPOSITÓRIO MODIFICAÇÕES → AULAS 5 e 6 


COMANDO → 
	(Git init na pasta que deseja incluir após abri-la com o 	GIT BASH)

1- 	Criar a pasta (Confirmar pastas ocultas)
2- 	Criar um projeto dentro e iniciar com GIT BASH HERE

	OBS. → (É interessante ver se as pastas .git já estão 	dentro do projeto).
	OBS. → (Testar as pastas pelo terminal com GIT STATUS).

3- 	Usar Code . (Dentro do terminal para abrir o visual studio)
		Clicar em terminal dentro do Visual Studio 
	Mudar o prompt de comando para configuração Git Bash

4-	Criar a folha Index.Html 
	Adicionar ela com o comando “ Git add “Index.Html” 
	Testar com git status 

5-	Assim que qualquer coisa for adicionado ao arquivo e ele 	for salvo, 	ocorrerá a modificação de Status para = M, 	portanto o monitoramento 	mostra que alguém fez alguma 	modificação.

	OBS. → (UNTRACKED significa “o arquivo esta sendo visto 	pelo GIT”), ou seja, não esta apto a ser versionado ou 	monitorado.

	As siglas U = untracked e A = Adicionado M = 	Modificado R = Renamed.

6- 	Apos a modificação e necessário incluir o arquivo ao git 	mais uma 	vez então preciso definir se ele sera Restored 	ou Commited 

	OBS. → Git Restore <file> serve para reverter as 	alterações,ou, mandar o arquivo para ser commitado 	(Validada as informações) com 	Git add <file>.
		
	→ Contudo normalmente não e usado o nome do arquivo 		individual, e sim GIT ADD . , de forma que 	será 	adicionado todos os arquivos dentro desse repositorio 	monitorado pelo GIT


SOBRE COMMIT → AULA 7


1- 	Git commit NOME.HTML -m “ estou criando a pagina “ 

2-	-m é uma flag de mensagem / aviso 
  
3- 	Depois de confirmar os COMMITS e checar as modificações usar git status para obter WORKING TREE CLEAR.

4-	Usar ( GIT ADD . ) para incluir os arquivos no 	monitoramento e deixar os modificados prontos para o 	commit.
	
	Usar ( GIT COMMIT ) Para commitar todos os arquivos de 	uma vez e obter a analise do que foi feito, adicionado, 	inserido, deletado. 

	OBS. → Sempre utilizar -m para deixar o comentário sobre 	a ação especifica. 

	EX “ FINALIZADO A MODIFICAÇÃO REQUISITADA”.

5-	O comando (git rm) é usado no Git para remover arquivos 	do 	índice (staging area) e do diretório de trabalho. 
	OBS.→ UTILIZAR <COMMIT> depois do <RM> para autorizar.
	Este comando é frequentemente utilizado quando você 	deseja excluir arquivos do seu repositório Git de forma 	controlada.
		A sintaxe básica do comando é:

		<git rm <nome_do_arquivo>
		Aqui estão algumas opções comuns do comando git rm:
5.1-		--cached:

        ◦ Remove apenas o arquivo do índice (staging area), mantendo-o no diretório de trabalho.
       
          <git rm --cached <nome_do_arquivo>

5.2-		2-r ou –recursive :
		Usado para remover recursivamente diretórios e seu conteúdo.
	
		<git rm -r <nome_do_diretório>
5.3-		--force:
		Força a remoção do arquivo, mesmo se ele estiver modificado no 			diretório de 	trabalho. Útil quando você deseja excluir arquivos que 			foram modificados sem 	commit.
          <git rm --force <nome_do_arquivo>
5.4-		--dry-run:
		Permite visualizar o que seria removido sem realmente executar a 			remoção.
       
          <git rm --dry-run <nome_do_arquivo>
          

5.5-		-n ou –dry-run:
          Uma abreviação para --dry-run.
          <git rm -n nome_do_arquivo>

5.6-		-q ou –quiet:
          Suprime mensagens de saída, exceto erros e mensagens de status.
       
          <git rm -q <nome_do_arquivo>
          
		Lembre-se de que após usar git rm, você também 			precisa realizar um commit para efetivar a remoção. 		Por exemplo:

		<git commit -m "Remover <nome_do_arquivo>"
		Este comando adiciona um novo commit que reflete a 		remoção do arquivo ou diretório especificado.

5-7		<CNTR+C> →  igual a sair no terminal 
				(apertar varias vezes se precisar com 					paciência) e 	depois INPUTAR: 
		<:qa!> → Dois pontos significa VOU INPUTAR o 					COMANDO. 
		<:CP!> → Comando de copia


CONHECENDO O GITHUB → AULA 8 

1- 	É o Serviço de armazenar e gerenciar repositórios 

2- 	Podemos subir nossos repositórios para outros devs 	gerenciarem versões dos projetos e ou trabalho em equipe.



ADICIONANDO REPOSITÓRIO GIT → AULA 9

1- 	Adicionar novo repositorio ao github .

2- 	Criar uma BRANCH.

		<git branch -m main>

3- 	Linkar seu repositorio com o github.

		<git remote add origin github.com:Churle/HTML5.git> 		e depois <Git push -u origin main> 

4-	Conferir se existem chaves no computador.

		<ls -al ~/.ssh>

5- 	Gerando uma nova chave.

		<ssh-keygen -t ed25519 -C “seu e-mail do github”>

	Ele ira pedir para locar o arquivo é só apertar enter e 	depois criar o PIN/Password. 

6-	Rodar o ssh-agent: eval $(ssh-agent -s). 

	(ele ira achar o Agent pid que é um processo de 	localização de ID).

	OBS.→ O ssh-agent é uma ferramenta que funciona como um 		gerenciador de chaves SSH, facilitando o uso 				seguro de chaves privadas para autenticação em 			conexões SSH. O agente mantém suas chaves 				privadas na memória durante uma sessão de login, 			permitindo que você use-as para se autenticar em 			vários servidores remotos sem precisar digitar a 			senha ou a passphrase a cada vez. 

7-	Incluir a chave privada: ssh-add ~/.ssh/id_ed25519

8-	Copiar chave pública.

	Agora que já adicionamos a chave privada no ssh-agent, 	vamos copiar a chave 	pública que faz par com ela, para 	concluirmos no nosso github. No mesmo terminal. 
	executar:
      No Windows: clip < ~/.ssh/id_ed25519.pub. (
      Automaticamente o conteúdo da sua chave pública será copiado para a área de transferência).
      
9-	Exibir a chave publica no terminal para alocar no github.
			
		<cat ~/./id_rsa.pub>	
		
Adicionando novos arquivos → Aula 10
1-	GIT PUSH empurra os arquivos para o repositorio externo.

Recebendo Arquivos Pull → Aula 11 
1-	Exemplo: Criar o README.md para interagir com o 	repositorio inicial.

2-	Vai haver uma verificacao de key, em caso de problemas 	utilizar :
				
	ssh agent:   eval “$(ssh-agent -s)”

	adicionando a chave: ssd-add ~ /.sshid_ed25519

Clonando Repositórios → Aula 12 

1-	Criar uma pasta “clone” dentro da paste que esta o 	projeto.

2-	Copiar o projeto no github.
	
3-	Abrir pelo gitbash e digitar: 

	GIT CLONE git@github.com:Churle/gitclass.git

4-	Caso queira mudar de repositorio, apagar a pasta nova 	criada dentro da pasta clone e :

	$ CD .. (/com/caminho/diretorio/novo)

5-	Caso quiser conferir qual repositorio esta utilizando:

	pwd

6-	Caso queira ver o conteudo do diretorio usar:

	ls ou ls/path/to/your/directory

7-	Portanto usar consecutivamente:
	
	$ cd..
	$ ls
	$ cd cloneprojeto1
	$ git clone “nome do repositorio” espaco+ponto


Acessando LOGS → Aula 13

1-	Comando novo <git log> , mostrando o ultimo commit 	no 	topo sempre.

2-	Press <q> para sair.

Revertendo arquivos com checkout ou restore → Aula 14

1-	Comando <git restore “nome do arquivo”>.

2-	Comando <git checkout “nome do arquivo”>.

OBS.→ 	o simbolo $ dentro do terminal, significa que o 			operador esta operando o sistema como usuario comum.

OBS2.→ 	o Visual studios e uma IDE = integrate development 		environment.

Como ignorar arquivos → Aula 15

OBS.→ 	utilizar o arquivo <.env.local> para criar uma pagina 		contendo as variaveis do projeto, como senha_api por 		exemplo.
		
		$ .env.local
			senha_api
			senha_api = xxxx

OBS2.→ 	Geralmente o projeto tera a pasta <node_module> 			antes>

1-		Criando o arquivo de ignorar <.gitignore> .

2-		Todos os arquivos dentro do arquivo acima serao 			ignorados, PORTANTO não serao enviados ao repositorio 		externo, exemplo abaixo:

		<.gitignore>	
			/node_modules (pasta criada para aula)
			.env.local (arquivo criado para aula)

Dando o comando RESETE → Aula 16

1-		Esse commit não volta atras então tomar cuidado.

2-		Comando <git reset -- hard origin/ main> 
		(eles esta voltando para origin da brach main, porque 		é a única que tenho no momento, se tivesse mais 			poderiamos escolher).

3-		Elá volta para a configuração padrão designada.

O que são BRANCHS → Aula 17

1-		Branch é simplesmente uma maneira que o git 				disponibiliza para separar projetos.

2-		A Branch inicial se chamará main
Criando Branch → Aula 18

1-		<git branch> , mostra qual branch temos e qual esta 		ativa no momento. Importante deixar claro que o certo 		e criar as novas branchs a partir da branch main, 			portante sempre conferir com <git checkout>

2-		Criando a brach nova com o comando: 
			<git branch “nome”> 
		ex:

		< git branch pagina_home> 
		Utilizar sempre letras minusculas e separar as 			palavras com underline (por convencao).

Mudando de branch e criando uma abrindo direto nela → Aula 19.

1-		A principio criamos a branch “pagina_home” para 			trabalhar no index sem precisar mexer na branch main.

2-		Para trocar de branch usar o comando:
		
		<git checkout “nome”>

3-		Para enviar a branch nova no repositorio externo:
		
		<git push origin nome_nome >

OBS.→ 	O nome UPSTREAM significa branch remota 					correspondente.


4-		Para SETAR a branch com a upstream usar :

		<git push --set-upstream origin nome_nome>

5-		Para criar a BRANCH e ja iniciar ela, utilizar o 			comando:
	
		<git checkout -b “nova_branch”>

Deletando uma BRANCH → Aula 20

1-		Usar o comando: <git branch -d nome_nome>
		Contudo isso apenas exclui o repositorio local!

2-		Para deletar do repositorio remoto (ex GIT HUB), usar 		o comando: <git push origin -- delete nome_nome >

Unindo branch GIT MERGE pelo GITHUB → Aula 21

1-		Antes de mais nada, retornar a BRANCH MAIN.
2-		Comando para MERGE: <git merge nome_nome>
3-		Se fizer MERGE por meio de PUSH REQUEST direto do GIT 		HUB, lembrar de atualizar o repositorio local ou 			<git pull>.



Realizando Simulacao de trabalho com BRANCHS ultrapassadas →Aula 22.		

1-		Alterar a branch main, faz as outras ficarem 		ultrapassadas/ out off date.

2-		Estando em outra branch e querendo atualizar, 		usar o comando:

		<git merge main> → De forma que puxaremos as 		atualizacoes da branch desejada para a branch 		que 	estamos.

GIT STASH → Aula 23.

1-		Git Stash e um comando que volta para as 					configuracoes originais do meu ultimo PUSH (e como se 		fosse um rewind), e o comando e :
			<git stash>.	

2-		Stash apaga as modificacoes voltando ao original do 		ultimo push e cria um arquivo em formato de codigo 		ex: d80cf0a.




Recuperation um STASH → Aula 24.

1-		Utilizando o comando: <git stash list>, e possivel 		ver o que temos armazenado no stash.

2-		Utilizando o comando: <git stash apply “1”>, e 			possivel retornar o stash de acordo com a ordem 			deles, portanto usei o 1 no caso de termos 2 ou mais 		stashs guardados.

3-		Utilizando o comando: <git stash pop>, sera possivel 		utilizar o stash mais recente e o remover da lista ao 		mesmo tempo.

----------------------------((Curso Finalizado))

Extraindo arquivos de outras branchs → Estudo 1

1-		Utilizar <git checkout branch_Name> para se 			mover a branch  que voce quer receber a 				pagina.

2-		Em seguida utilizar o comando:						 <git checkout b	ranch_Name arquivo_name.xxx>. 

</p>


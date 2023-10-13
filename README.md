GIT e GITHUB  AULAS 1, 2 e 3 

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
          <git rm -n <nome_do_arquivo>

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

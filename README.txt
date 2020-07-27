Aprendendo a trabalhar com o Git e GitHub

--Preparação
	//informar email e nome
	-> git config --global user.email "nogueirasilverio@gmail.com"
	-> git config --global user.name "Anderson Silverio"

--Iniciar projeto
	->	git init

--Adicionar arquivo para monitorar
	-> git add _arquivo_

--Salva arquivos monitorados no repositorio local --cria um ponto na historia
	->	git commit -m "_mensagem_" //mensagem

--*adiciona e salva ao mesmo tempo a branch atual
	->git commit -am "_mensagem_"

--Ver o ponto alterado
	->git log

--ver status
	->git status

-- ver alteracoes
	-> git show (mostra ultima alteracao)
	-> git show _codigo do commit

-- criar ramificação
	->git branch _nome_

--criar uma ramificação e já mudar pra ela
	->git checkout -b _nome_

--muda de ramificação
	->git checkout _nome da ramificação_

--unir ramificação com a master
	->git merge _nome da ramificação_

--deletar a branch da nova funcionalidade
--depois de aplicar no projeto principal
	->git branch -D _nome da ramificacao_

--Adicionar repositorio remoto
	-> git remote add origin _endereço do repositorio_

--Verificar repositorio remoto
	->git remote -v

--Salvar repositorio local no repositorio remoto
	
	//se for a primeira vez tem que criar a branch master
	->git push -u origin master
	//se não
	->git push

--Configurar de vez os dados de acesso ao github
	->git config credential.helper store

--Pega um projeto já iniciado no github
	
	->git clone _endereco_

--Salvar repositorio remoto no repositorio local

	->git pull

--retorna a um estado anterior
	
	->git checkout _d20a83f98f28009fc3b4d9755f33722e85ad8f05_ log do estado
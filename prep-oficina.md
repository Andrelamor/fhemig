# preparação oficina FHEMIG 

## 1. etapa de limpeza:

- exclusão de células mescladas

- inclusão de coluna mês

- inclusão de coluna ano

- realinhamento das linhas conforme novas colunas

- edição dos nomes das colunas

- transformação das colunas numéricas de texto para numéricas

- exportação para o formato csv (2 arquivos diferentes)

- salvar arquivos numa pasta nova em C

- abrir pasta nova no Sublime

- mostrar arquivos csv no Sublime

- salvar com csv + BOM (problema encoding windows)


## 2. etapa de documentação 

- dicionário de dados no datapackage creator https://create.frictionlessdata.io/

- MARKDOWN = usar descrição com hiperlink no datapackage

- salvar datapackage na nova pasta criada

- apartar schema do datapackage, pois têm a mesma estrutura

- mover arquivos para pasta data e corrigir path no datapackage

	- validador de json no sublime pretty json (erros de sintaxe - chaves, vírgulas) 

- erros 'didáticos'

	- inclusão dos decimalChar e groupChar e mudança de integer para number

	- inclusão do OWNER_ORG APÓS PUBLICAÇÃO VIA DPCKAN DETECTAR ERRO


## 3. inclusão no repo git

- criar novo repo site github e copiar o https

- configuração github actions

- na bash, da pasta que será o repo: 

  - git init > git status > git add . > git remote add origin <URL repo> > git commit -m "commit inicial > "git push <URL repo>

- inclusão do texto readme com badge de validação github actions

	- MARKDOWN = usar descrição com hiperlink no datapackage 

## 4.validação inicial com github actions

- inclusão dos decimalChar e groupChar e mudança de integer para number (5 min) APÓS VALIDAÇÃO DETECTAR ERRO

- correção a partir da mensagem de erro (e replicar para as demais, comentando que é difícil e que tem que abrir o arquivo)

* ERROS: 
	number --> integer 
	decimalChar, 
	groupChar, 
	dialect.json (depende da versão do frictionless??), 

* recursos no Sublime para visualização e correção de erros
	
- rainbow csv (marcação de colunas)



## 5. publicação no homologa CGE com dpckan

* REQUISITOS: 
	python, etc 
	ambiente (venv) + 
	inclusão da propriedade owner_org

- criar ambiente 

 	- configuração do ambiente = pyhton -m venv venv; para ativar, source venv/Scripts/activate

- instalar pacote

- mostrar chave de usuário no ckan HOMOLOGA

- conferir ambiente de homologação antes de rodar o comando de publicação

`echo $CKAN_HOST`

- realizar alteração na description da primeira coluna e executar 

## para segundo encontro

- descrição campos variáveis

- textos changelog, contributting

- schema yaml

- git large files

   
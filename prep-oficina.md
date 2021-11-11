# preparação oficina FHEMIG 

## etapa de limpeza:

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


## etapa de documentação 

- dicionário de dados no datapackage creator 

- salvar datapackage na nova pasta criada

- apartar schema do datapackage, pois têm a mesma estrutura

- mover arquivos para pasta data e corrigir path no datapackage 

- erros 'didáticos'

	- inclusão do dialect.csv (5 min) APÓS VALIDAÇÃO DETECTAR ERRO

	- inclusão dos decimalChar e groupChar e mudança de integer para number

	- inclusão do OWNER_ORG APÓS PUBLICAÇÃO VIA DPCKAN DETECTAR ERRO

- frictionless describe para geração do schema yaml (segundo encontro?)

## validação inicial com frictionless

- inclusão dos decimalChar e groupChar e mudança de integer para number (5 min) APÓS VALIDAÇÃO DETECTAR ERRO

* REQUISITOS: 
	number --> integer 
	decimalChar, 
	groupChar, 
	dialect.json (depende da versão do frictionless??), 


## inclusão no repo git

- criação novo repo site github

- git init > git status > git add . > git remote add <nome repo> <URL repo> > git push <nome repo>

- configuração github actions e git LFS = NECESSITAM MODIFICAÇÃO APÓS PARA MOSTRAREM RESULTADO

- configuração do ambiente = CAÓTICO

	


## publicação no homologa CGE com dpckan

* REQUISITOS: 
	python, etc 
	ambiente (venv) + 
	inclusão da propriedade owner_org

* obs: conferir ambiente de homologação antes de rodar o comando de publicação

`echo $CKAN_HOST`

## para segundo encontro

- descrição campos variáveis

- schema yaml

- local schema e dialect (pasta separada)

- git large files
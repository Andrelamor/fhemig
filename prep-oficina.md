# preparação oficina FHEMIG (2021-11-10 18:04)

## etapa de limpeza:

- exclusão de células mescladas

- inclusão de coluna mês

- inclusão de coluna ano

- realinhamento das linhas conforme novas colunas

- edição dos nomes das colunas

- transformação das colunas numéricas de texto para numéricas

- exportação para o formato csv


## etapa de documentação (18:20)

- dicionário de dados no datapackage creator (10 min)

- apartar schema do datapackage (10 min)

- frictionless describe para geração do schema yaml (segundo encontro?)

- inclusão do dialect.csv (5 min) APÓS VALIDAÇÃO DETECTAR ERRO

- inclusão do OWNER_ORG APÓS PUBLICAÇÃO VIA DPCKAN DETECTAR ERRO


## validação inicial com frictionless

- inclusão dos decimalChar e groupChar e mudança de integer para number (5 min) APÓS VALIDAÇÃO DETECTAR ERRO

* REQUISITOS: 
	number --> integer 
	decimalChar, 
	groupChar, 
	dialect.json, 


## inclusão no repo git

- configuração github actions

- configuração git LFS


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
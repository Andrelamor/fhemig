# oficina mão-na-massa FHEMIG

- como fazer o yaml? a partir do datapackage creator? usar frictionless describe para schema inferido no yaml, para conferir os tipos das variáveis; adotar schema em arquivo separado como padrão

- cronograma: documentar e validar um datapackage na sessão, depois setar os requisitos (setup, cadastro e variáveis de ambiente)

	- primeiro encontro: DCTA documenta, valida e publica um exemplo
	 
	- resolver setup, cadastro e variáveis de ambiente 
	 
	- segundo encontro: FHEMIG documenta, valida e publica outro exemplo 

- tempo da conversa prévia determinado pelo tempo estimado da oficina

- 2 pacotes principais = frictionless e dpckan (piplist); uma hora de setup para um encontro intermediário


## 1. (20 min) entrevista guiada pelo formulário, com foco nas ferramentas específicas:

  - markdown (editores de texto)

  - json (datapackage creator, editores de texto e yaml)

  - bash cell

  - git (site, interface gráfica, bash)


## 2. (50 min) demonstração das fases com foco nas ferramentas específicas: 
	INOVA 2020 (+/- 30 min para demonstração da documentação, publicação, validação e correção de datapackage)

2.1. dicionário de dados (descrição dos metadados)

  - especificações dos metadados

    - [datapackage](https://specs.frictionlessdata.io/data-package/)
    - [resource](https://specs.frictionlessdata.io/data-resource/)
    - [schema](https://specs.frictionlessdata.io/table-schema/)
    - [csv dialect](https://specs.frictionlessdata.io/csv-dialect/#specification) 

  - [datapackage creator](https://create.frictionlessdata.io/)

  - schema em yaml - via `frictionless describe`

2.2. validação dos dados

  - [pacote frictionless](https://framework.frictionlessdata.io/docs/guides/guides-overview)

  - [github actions]()

2.3. controle de versão

  - valor da chave `version` dos metadados do datapackage

  - repositório git como background ('pinceladas')

2.4. catalogação

  - [criar e atualizar conjunto e recurso via terminal](https://github.com/dados-mg/dpckan#criando-e-atualizando-com-um-conjunto-de-dados-via-terminal)

  - requisitos: 

  setup da máquina ([programas necessários](https://github.com/dados-mg/fluxo-ETL/blob/master/setup-maquina.md))

  [cadastro dos usuários no portal CKAN]()

  [configurar variável de ambiente](https://github.com/dados-mg/dpckan#configura%C3%A7%C3%A3o-de-vari%C3%A1veis-de-ambiente)  




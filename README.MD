##INSTALAR SERVERLESS FRAMEWORK.
npm i -g serverless

#ALIAS
sls  - criar 1 projeto serverless.

#SEMPRE FAZER DEPLOY ANTES DE TUDO, PARA VERIFICAR O AMBIENTE.
sls deploy

#INVOCAR ENDPOINT AWS (nome do endpoint hello.)
sls invoke -f hello

#INVOCAR ENDPOINT LOCAL (nome do endpoint hello.)
sls invoke local -f hello

#INVOCAR ENDPOINT LOCAL (nome do endpoint hello.) COM LOG.
sls invoke local -f hello --log

#CONFIGURAR DASHBOARD.
sls  - criar uma nova aplicacao, depois fazer o deploy e abrir o link retornado no log.

#LOGS EM TEMPO REAL
sls logs -f hello -t

#DELETAR 1 SLS FRAMEWORK
sls remove
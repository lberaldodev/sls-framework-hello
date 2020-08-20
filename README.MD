# INSTALAR SERVERLESS FRAMEWORK.
npm i -g serverless

# ALIAS LIST.
sls  - criar 1 projeto serverless.

# DEPLOY
sls deploy

# INVOCAR FUNÇÃO REMOTA.
sls invoke -f hello

# INVOCAR FUNÇÃO LOCAL.
sls invoke local -f hello

# INVOCAR FUNÇÃO COM LOGS.
sls invoke local -f hello --log

# CONFIGURAR SERVERLESS DASHBOARD.
sls  - criar uma nova aplicacao, depois fazer o deploy e abrir o link retornado no log.

# LOGS EM TEMPO REAL.
sls logs -f hello -t

# DELETAR 1 SLS FRAMEWORK
sls remove
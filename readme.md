Instalando de forma local
npm init -y
npm i typescript -D

instalando dependência de desenvolvimento
ts-node
npm i ts-node -D


cria uma pasta .vscode e procura em { ccde-runner.executorMap}
para poder rodar com a seta do coderunner
depois exclui e só deixa esse arquivo: "typescript": "ts-node",
pra rodar o coderunner localmente é assim: "typescript": "npx ts-node --files",
npx tsc --init  para gerar um tsconfig.json válido e funcionou (mantendo as configurações do professor também).

npx tsc -w  = Pra visualizar localmente
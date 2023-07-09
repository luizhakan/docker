FROM node:14
# versão do node 

WORKDIR /app-node
# diretório de trabalho

ARG PORT_BUILD=6000
# variável de ambiente definida na build

ENV PORT=$PORT_BUILD
# variável de ambiente definida no dotenv

EXPOSE $PORT_BUILD
# expor a porta $PORT_BUILD

COPY . .
# copiar arquivos do diretorio atual para o diretorio de trabalho

RUN npm install
# executar o comando npm install no terminal para instalar as dependências

ENTRYPOINT npm start
# executar o comando npm start no terminal para iniciar o servidor
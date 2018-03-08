# APPONTE FullStack 

Este é um repositorio para o teste de FullStack da APPONTE

## Requerimentos

- node e npm
- Conta no https://mlab.com/ e uma base de dados MongoDB
- ionic

## Como usar

1. Clone o repositório: `git clone https://github.com/caiomelzer/fullstack-apponte.git`
2. Entre na pasta clonada: `cd fullstack-apponte`
3. Instale as dependências do projeto: `npm install`
4. Abra o arquivo config.js e altere os dados do banco. Linha 4: `mongodb://apponte:adm123@ds253468.mlab.com:53468/apponte`
PS: Este passo não é necessário no momento, uma vez que o banco de teste ja esta configurado.
5. Rode a aplicação dentro do console: `node server.js`
6. A aplicação ficará disponível em `http://localhost:8080`
7. Para uma instância em um base nova, será necessário chamar a URL `http://localhost:8080/install`
PS: Esta URL cria um usuário administrador (admin:apponte)

8. Em outra aba do terminal, acesse a mesma pasta do projeto
9. Entre na pasta do app ionic: `cd ionic`
10. Instale as dependências do projeto: `npm install`
11. Rode a aplicação dentro do console: `ionic serve`. Automaticamente uma janela de seu navegegar irá abrir com o aplicativo.






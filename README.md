# aulas


// FORMAS DE FAZER BACKEND
- Backend Tradicional => Monolítico
Vantagem: Fácil de iniciar
Desvantagem: difícil de escalar quando o sistema cresce

- Backend Moderno => microserviço
Vantagem: escalabilidade e manutenção separada 
Desvantagem: mais complexidade e curso de infraestrutura

- Backend Headless => API

// ENTENDENDO O QUE É API,  SDK E FORMATO DE RESPOSTA
- API: Aplication Programming Interface - conjunto de regras que
permitem que um sistema converse com outro

lojadojhon.com.br -> página inicial da loja
lojadojhon.com.br/carrinho
lojadojhon.com.br/produto-xyz

138.123.123.122/produto
127.0.0.1/xyz
localhost/xyz

-SDK: software Development Kit - um pacote de ferramentas e
bibliotecas fornecidas por uma empresa para facilitar o uso da API

-Formatos de Respostas 
-- XML / JSON



instalações

 npm init -y

 npm i -D typescript

 npx tsc --init

 npm i -D ts-node

// NODE
// NPM

npm init -y8npx tsc --init -> configuração do typescript

{
  "compilerOptions": {
    "target": "es2020",
    "module": "commonjs",
    "strict": true,
    "esModuleInterop": true,
    "forceConsistentCasingInFileNames": true,
    "skipLibCheck": true,
    "outDir": "./dist"
  },
  "include": ["src", "test"]
}

------------------------------------------------------------------------------------------------------------

instalações:
npm init -y
npm i -D typescript
npx tsc --init //criar ts config
criar um novo cript. EX:'start": "node -import=tsx --watch  ./src/server.ts
npm i express
npm i -D @types/express
ligar servidor: npm start
npm i helmet 
npm i -D @types/helmet


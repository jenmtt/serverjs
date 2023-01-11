# Projeto Individual
- https://www.npmjs.com/package/json-server

O que fazer?
1. Desenvolver um servido json (json-server). É um servidor que serve dados no formato json. 
2. Precisa ter 3 ou mais rotas; 
3. Preciso ter 4 ou + atributos (dados);
4. Cada rota deverá conter os métodos GET, POST, PUT, DELETE.
5. O servidor deverá estar hospedado (deploy) no render.com. 

Passo a passo

npm install -g json-server // Instalar globalmente. 
criar um arquivo no dp-son

{
    "postagens" : [
     { "id" : 1 , "título" : " json-server " , "autor" : " typicode " }
   ],
   "comentários" : [
     { "id" : 1 , "body" : " algum comentário " , "postId" : 1 }
   ],
   "perfil" : { "nome" : " typicode " }
 }
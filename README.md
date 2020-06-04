# NextLevelWeek
Aplicação da NLW - Back End + Front End + React Native (Mobile)

# Instruções Back End (Server)
criar pasta do projeto (pasta Server) e acessar.

instalar dependências (dentro da pasta Server):
npm init -y
npm install express
npm install @types/express -d
npm install ts-node -d
npm install typescript -d
npm install ts-node-dev -d
npm install knex
npm install sqlite3
npx knex --knexfile knexfile.ts migrate:latest
npx knex --knexfile knexfile.ts seed:run
npm install cors
npm install @types/cors -d

para executar a aplicação:
npx tsc --init
npx ts-node src/server.ts
npn run dev

# Instruções Front End (Web)
criar pasta do projeto (pasta Web) e acessar.

instalar dependências (dentro da pasta Web):
npx create-react-app web --template=typescript
npm install react-iconsnpm install react-router-dom
npm install @types/react-router-dom -d
npm install leaflet react-leaflet
npm install @types/react-leaflet -d
npm install axios

para executar a aplicação:
npm start

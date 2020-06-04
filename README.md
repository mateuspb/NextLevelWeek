# NextLevelWeek
Aplicação da NLW - Back End + Front End + React Native (Mobile)

# Instruções Back End (Server)
criar pasta do projeto (pasta Server) e acessar. \n
 \n
instalar dependências (dentro da pasta Server): \n
=> npm init -y \n
=> npm install express \n
=> npm install @types/express -d \n
=> npm install ts-node -d \n
=> npm install typescript -d \n
=> npm install ts-node-dev -d \n
=> npm install knex \n
=> npm install sqlite3 \n
=> npx knex --knexfile knexfile.ts migrate:latest \n
=> npx knex --knexfile knexfile.ts seed:run \n
=> npm install cors \n
=> npm install @types/cors -d \n
 \n
para executar a aplicação: \n
=> npx tsc --init \n
=> npx ts-node src/server.ts \n
=> npn run dev \n
 \n
# Instruções Front End (Web) \n
criar pasta do projeto (pasta Web) e acessar. \n
 \n
instalar dependências (dentro da pasta Web): \n
=> npx create-react-app web --template=typescript \n
=> npm install react-iconsnpm install react-router-dom \n
=> npm install @types/react-router-dom -d \n
=> npm install leaflet react-leaflet \n
=> npm install @types/react-leaflet -d \n
=> npm install axios \n
 \n
para executar a aplicação: \n
=> npm start \n

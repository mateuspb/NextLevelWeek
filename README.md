# NextLevelWeek
Aplicação da NLW - Back End + Front End + React Native (Mobile)

# Instruções Back End (Server)
criar pasta do projeto (pasta Server) e acessar. </br>

instalar dependências (dentro da pasta Server): 
 => npm init -y 
 => npm install express 
 => npm install @types/express -d 
 => npm install ts-node -d 
 => npm install typescript -d 
 => npm install ts-node-dev -d 
 => npm install knex 
 => npm install sqlite3 
 => npx knex --knexfile knexfile.ts migrate:latest 
 => npx knex --knexfile knexfile.ts seed:run 
 => npm install cors 
 => npm install @types/cors -d 
 
para executar a aplicação: 
 => npx tsc --init 
 => npx ts-node src/server.ts 
 => npn run dev 
 
# Instruções Front End (Web) 
criar pasta do projeto (pasta Web) e acessar. 
 
instalar dependências (dentro da pasta Web): 
 => npx create-react-app web --template=typescript 
 => npm install react-iconsnpm install react-router-dom 
 => npm install @types/react-router-dom -d 
 => npm install leaflet react-leaflet 
 => npm install @types/react-leaflet -d 
 => npm install axios 
 
para executar a aplicação: 
 => npm start 
 
 # Instruções React Native (Mobile)
criar pasta do projeto (pasta mobile) e acessar.

instalar dependências (dentro da pasta Server): 
 => npm install -g expo-cli
 => expo init mobile
       tipo -> blank(typescript)
 => cd mobile
 => expo install expo-font @expo-google-fonts/ubuntu @expo-google-fonts/roboto
 => npm install @react-navigation/native
 => expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view
 => npm install @react-navigation/stack
 => expo install react-native-maps
 => expo install expo-constants
 => expo install react-native-svg
 => npm install axios
 => expo install expo-location
 => expo install expo-mail-composer

para executar a aplicação:
 => npm start

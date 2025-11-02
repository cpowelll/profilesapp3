--use vite to create a react application
npm create vite@latest profilesapp -- --template react
cd profilesapp
npm install
npm run dev


--run the site locally
cd profilesapp3
npm install
npm run dev

--deploy cloud resources into an isolated development space
npx ampx sandbox


--generate the GraphQL client code to call your data backend. 
npx ampx generate graphql-client-code --out amplify/auth/post-confirmation/graphql

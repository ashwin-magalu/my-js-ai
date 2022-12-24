# Steps:

## In Client

1. To create an app use command npm create vite@latest client --template vanilla
2. Select Vanilla framework
3. Select JavaScript variant

## In Server

1. Run the command npm init -y
2. Run the command npm i cors dotenv express nodemon openai
3. Visit OpenAI website (https://openai.com/api) and create an account
4. Click on Your profile pic in the right top corner and click on View API keys
5. Click on Create new secret key button and copy and paste your secret key in .env file that you created inside server folder with the key name as OPENAI_API_KEY

## Deploying server code

1. Visit https://render.com/
2. Create a new account using github
3. Go to dashboard (https://dashboard.render.com/) and click on +New dropdown and select Web Service option
4. Connect your repository uploaded to Github
5. Add name and other details as you like
6. Set root directory as server, build command as yarn and start command as npm run server
7. Select Free instance type and click on Create
8. Add environment variable in the deploy pipeline

## Deploying client code

1. Use vercel to deploy client code

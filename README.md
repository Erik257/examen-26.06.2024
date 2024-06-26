docker build -t simple-express-app .

docker run -d -p 3001:3000 simple-express-app

http://localhost:3001/
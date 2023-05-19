from node:15.0.1
workdir /usr/src/app
copy package*.json ./
run npm i
copy . .
expose 20
cmd ["node", "src/app.js" ]

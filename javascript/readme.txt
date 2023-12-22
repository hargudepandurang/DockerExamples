  731  npm install
run npm install so package-lock.json will be gerenated.
then run below.

  732  docker build -t my-nodejs-app
  733  docker build -t my-nodejs-app .
  734  docker run -p 3030:3000 my-nodejs-app
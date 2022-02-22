# websocket-server-nodejs
This is a repository to experiment with websocket servers. The main stack to be used will be nodejs

# Steps to create this package from scratch
## Step 1: 
```sh
npm init
```

## Step 2: 
```sh
touch index.js
echo "console.log('Hello world')" >> index.js
```

## Step 3: 
Create hot reloading using nodemon
```sh
npm i nodemon
```

Add the following line to the scrips section of package.json: 
```javascript
"start": "nodemon index.js"
```

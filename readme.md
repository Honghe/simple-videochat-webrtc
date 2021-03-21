# Simple Video Chat WebRTC

### By using [simple-peer](https://github.com/feross/simple-peer), this web app connects video chat between two clients.

## How To Use

Install dependencies - npm install  
Start - npm start  

For development run watchify - npm run watch  

Open localhost in two browser tabs for testing. On the same machine, don't open tabs in two different browsers as it will fail to provide camera access to 2 different applications(browsers) simultaneously.   
Deploy it and open url in two separate devices for real-world usage.

To generate a certificate use (-nodes: Don't encrypt the output key):
```
openssl req -newkey rsa:4096 -nodes -keyout key.pem -x509 -days 365 -out cert.pem
```
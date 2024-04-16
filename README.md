# NodeJs, helloworld API for test propouses.

This is a simple API that returns a welcome message.

## Run your local environment
## Hola

### Clone the repository
```bash
git clone https://github.com/edgaregonzalez/nodejs-helloworld-api.git
```

### Install dependencies
```bash
npm install
```

### Run the tests
```bash
npm test
```

### Start the server
```bash
npm start
```

### Make a request
```bash
curl http://localhost:3000
```
# CI/CD

### Comenzamos instalando dependecias npm

### Instalamos Ngrok y ejecutamos el siguiente comando para que tenga salida por el puerto 80 
```bash
ngrok http http//localhost:8080
```

### Una vez corrido deberia mostrarnos por la terminar algo similar a esto 
![image](https://github.com/Kidbuut/nodejs-helloworld-api/assets/120615998/2650903d-1c7c-4388-b4ae-b1edea8efa28)

### Accedemos a Jenkins con el link que nos genero Ngrok
![image](https://github.com/Kidbuut/nodejs-helloworld-api/assets/120615998/241b9d7e-a973-45cd-8a32-eb2f81d35572)

### Una vez este todo finalizado con Ngrok debemos configurar el Webhook en Github, para esto nos vamos al apartade de settings 
![image](https://github.com/Kidbuut/nodejs-helloworld-api/assets/120615998/c2f90c9d-9575-4244-89a0-0d676df9c9df)
### Seguidamente a Webhooks
![image](https://github.com/Kidbuut/nodejs-helloworld-api/assets/120615998/aa85d461-305e-488f-91a0-540a351adee4)
### Una vez ahi tenemos que crear un nuevo Webhook 
![image](https://github.com/Kidbuut/nodejs-helloworld-api/assets/120615998/07462c41-ff1b-4957-90e4-b2186b6328f7)






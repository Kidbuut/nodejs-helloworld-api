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

### Comenzamos instalando dependecias npm con los siguientes comando en una terminal de linux

### Instalar dependecias
```bash
npm install
```

### Ejecutamos la prueba
```bash
npm test
```

### Iniciamos el servidor
```bash
npm start
```

### hacemos la solitud de salida por el puerto 3000
```bash
curl http://localhost:3000
```

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

### El siguiente paso sera configurar Tools en Jenkins 

![image](https://github.com/Kidbuut/nodejs-helloworld-api/assets/120615998/28a7783b-f7c2-4913-8390-f5daa728e57c)

### Verificar que la version del nodejs instalada en tu VM sea la misma configurada, esto lo hacemos con el siguiente comando 
```bash
node -v
```

![image](https://github.com/Kidbuut/nodejs-helloworld-api/assets/120615998/11a0847c-9fb7-42ba-b3ed-1f2cb14c2f68)

### En Jenkins tendriamos que configurar el plugins de nodejs y configurarlo con la version instalada en nuestra VM, en mi caso es la version 21.7.3

![image](https://github.com/Kidbuut/nodejs-helloworld-api/assets/120615998/84fac77e-1388-4e46-9f19-0ec4236a0056)

### Una vez finalizado todo los pasos estamos listos para recibir commits. 

![image](https://github.com/Kidbuut/nodejs-helloworld-api/assets/120615998/488b6d1e-b196-4730-96f8-7a942026bd01)



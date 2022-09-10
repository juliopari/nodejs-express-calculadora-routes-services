# nodejs-express-calculadora-routes-services

## 1. Instalar dependencias
```
npm install
```

## 2. Ejecutar
```
npm run dev
```

## 3. Docker build
```
docker build -t nodejs-calculadora:v1 .
```

## 3. Docker run
```
docker run -p 4000:3000 nodejs-calculadora:v1
```

## 3. Enviar a Dockerhub
```
docker login –-username juliopari –-password *****
docker tag nodejs-calculadora:v1 juliopari/nodejs-calculadora:v1
docker push juliopari/nodejs-calculadora:v1
```

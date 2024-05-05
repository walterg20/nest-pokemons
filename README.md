<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Ejecutar en desarrollo
1. clonar el Repositorio
2. Ejecutar
```
  npm install
```
3. Tener Nest Cli Instalado
```
  npm i -g @nestjs/cli
```

4. Levantar la base de datos
```
docker-compose up -d
```
5. Clonar el archivo ```.env.template``` y renombrar la a ```.env```

6. llenar la variable de entorno definidas en el ```.env```

7. Levantar el proyecto
```
  npm run start:dev
```


7. Recontruir base de dato con la semmilla
```
http://localhost:3000/api/v2/seed
```

## Stack usado 
* MongoDB
* Nest


## License

Nest is [MIT licensed](LICENSE).

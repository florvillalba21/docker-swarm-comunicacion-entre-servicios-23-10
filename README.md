# Descargar dependencias correspondientes

Ingresar a las rutas de cada carpeta y utilizar el siguiente comando

```bash
npm i 
```

## Crear las imagenes correspondientes para cada servicio

```bash
docker build -t imagen ./ruta
```

## Levantar los servicios

```bash
docker stack deploy -c services.yml nombre-servicios
```

## Ingresar al sitio web

```bash
http://localhost:3002
```

# Rodar um servidor em background

### Iniciar container em segundo plano

```bash
docker container run -d --name ex-daemon-basic -p 8080:80 -v <Pasta da maquina host>:<Pasta a ser mapeada dentro do container> nginx
```

### Parar container

```bash
docker container stop <nome do container>
```

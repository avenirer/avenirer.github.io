Vezi toate containerele care ruleaza

```
docker ps
```

Vezi toate containerele care ruleaza sau au rulat in trecut

```
docker ps --all
```

Opreste si sterge (elimina) toate containerele:

```
docker system prune
```

Creeaza un container 

```
docker create <nume-container>
```

Porneste container

```
docker start <id-container>
```

Vizionare loguri

```
docker logs <id-container>
```

Oprire container nefortata, cu clean-up (daca nu se opreste in 10 secunde, se face docker kill)

```
docker stop <id-container>
```


Oprire container fortata (asemenea unui buton de oprire hardware)

```
docker kill <id-container>
```

Executa comenzi in interiorul unui container 

```
docker exec -it <id-container>
```

Cheama un terminal al containerului pentru a executa comenzi (sh = shell; se iese cu Ctrl+d)

```
docker exec -it <id-container> sh
```

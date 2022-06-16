Budowanie obrazow:

```
docker compose -f docker-compose.dev.yml build
```

Wypchniecie obrazow do repozytorium:

```
docker compose -f docker-compose.dev.yml push
```

Uruchomienia obrazow: 

```
docker compose -f docker-compose.dev.yml up
```
Usuwam tutaj sekcje build i zostawiam tylko image z odpowiednimi obrazami.

```
docker compose up --build
```

Utworzenie swarma:

```
docker swarm init
```

Deploy do swarma:

```
docker stack deploy -c docker-stack.yml zadanie2
```

Sprawdzenie dzialania serwisow:

```
docker service ls
```

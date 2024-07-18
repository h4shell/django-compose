# Template Docker Compose per Python 3.12 e Django 5

Questo template fornisce un ambiente Docker Compose preconfigurato per eseguire un server Django 5 con Python 3.12. È utile per avviare rapidamente un progetto Django in un ambiente Dockerizzato.

## Prerequisiti
- Docker installato sul tuo sistema
- Docker-compose plugin

## Utilizzo
1. Clona questo repository sul tuo computer.

```bash
git clone https://github.com/h4shell/django5-compose.git
```

2. Posizionati nella directory del progetto.

### Avvio del server Django
Esegui il seguente comando per avviare il server Django:

```bash
docker compose up -d
```
Esegui lo script init.sh per installare le dipendenze python all'interno del container

```bash
./scripts/init.sh
```

Infine ti basta digitare lo script start.sh per avviare il server di sviluppo di django

```bash
./scripts/start.sh
```

# Usage

Rename the .env.example to .env and update the necessary variables.
(Note: some env variables such as PUID/PGID and TZ might not have any effect in non-linuxserver.io containers) 

Then, run the appropriate docker stack as follows:

```bash
docker-compose -f heimdall/docker-compose.yaml up -d
```


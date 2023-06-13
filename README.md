# Loadtest

Setup `LOADTEST_*` env vars, create a `.env` file at the root of the repo with:

```conf
LOADTEST_BACKEND_URL=https://api.group26.socra-sigl.fr
LOADTEST_CONSTANT_CONCURRENT_USERS=20
LOADTEST_DURATION=2
```

To run:

```sh
docker compose run loadtest
```

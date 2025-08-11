# ntfy stack

## Usage

```sh
# set these variables first
#   TS_API_CLIENT_ID
#   TS_API_CLIENT_SECRET
./pre-deploy.sh
docker compose up -d
```

## Development

```sh
# install pre-commit hooks
pre-commit install
# view complete compose file
docker compose config | bat --language yaml
# deploy application (see Usage section)
./pre-deploy.sh
docker compose up -d
```

## Licenses

- [LICENSE](LICENSE)
- [ntfy](https://github.com/binwiederhier/ntfy/blob/main/LICENSE)

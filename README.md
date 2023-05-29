# onlyoffice-docs

Simple onlyoffice-documentserver hosted on fly.io

## Setup

- Install flyctl
- Auth flyctl
- `fly deploy`
- `fly scale memory 1024`
- `fly scale count 1`
- `fly secrets set JWT_SECRET=randomString`
- `fly tokens create deploy -x 999999h` -> save as `FLY_API_TOKEN` in Github Actions


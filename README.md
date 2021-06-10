# pelican-github-pages
make github pages by pelican

## USAGE

### Docker compose

```bash
docker-compose build

docker-compose up -d
```

### Init pelican

```
docker exec -it python3 pelican-quickstart
```
### Write contents

```bash
cd src
touch firstpost.md
```

write post at text editor

### Make html & serve local

```bash
make html
make serve
```

access `http://localhost:8000` and check pages

`BUT I CAN'T ACCESS LOCAL SERVER IN MY DOCKER CONTAINER! WHY~~~~~~`

## Thanks

- <https://qiita.com/saira/items/71faa202efb4320cb41d>
- <https://zuma-lab.com/posts/docker-python-settings>

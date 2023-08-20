# コードの説明

```yml
version: "3.9"

services:
  web:
    build: . #カレントディレクトリにあるDockerfileがbuildされてimageげできてここから下のパラメーターをもとにrunされる。
    ports:
      - '3000:3000'
    volumes:
      - '.:/rails-docker'
    tty: true
    stdin_open: true

```

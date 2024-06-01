# FastAPI

## Cyclic

It was used deployed on cyclic.sh yet it shutdown :(

## koyeb

https://peaceful-reena-hobbynoncommecrial-d0246e50.koyeb.app/

## Run Locally

Prerequisites:

- pyenv
- python 3.10.11

Install: `bin/install`

- creates virtual env
- installs dependencies from `requirements.txt`

Run: `bin/dev`

- runs a `uvicorn` server in reload mode

Run: `bin/start`

- runs a `uvicorn` server

## Try the server

Schema docs: [http://localhost:8181/docs](http://localhost:8181/docs)

Get an item:
`curl -i -XGET http://localhost:8181/item/1`

List items:
`curl -i -XGET http://localhost:8181/items/`

Post an item:
`curl -i -XPOST http://localhost:8181/items/ --data '{"item_id":1,"name":"Bob"}' -H 'content-type: application/json'`



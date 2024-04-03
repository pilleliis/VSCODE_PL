# VSCODE_PL
This is our project root folder. Readme.md file is typical first file.


docker run -d -p 8080:8088 -v ${PwD}:/data:rw -e "SUPERSET_SECRET_KEY=8y7tftkyg76fiuygliuh" --name superset my/superset:duckdb

docker exec -it superset superset fab create-admin --username admin --firstname Superset --lastname Admin --email admin@superset.com --password admin

docker exec -it superset superset db upgrade

docker exec -it superset superset load_examples

docker exec -it superset superset init


## AIRFLOW

1. O docker compose precisa ter versão acima de 1.26:

sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

2. Iniciar bancos
docker-compose up airflow-init

3. subir os containers

docker-compose up

4. dar permissão para sua pasta de dags
sudo chown -R root:<seu usuario> /home/<seu usuário>/Desktop/composes/airflow/dags



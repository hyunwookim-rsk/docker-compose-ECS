# docker-compose-ECS
Use docker-compose to ECS

## Getting started


```
# install python dependency
python3 -m venv ecs_env
source ecs_env/bin/activate
pip3 install -r requirements.txt
aws configure
```

Install awscli V2 [link](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)

```
# create docker context
docker context create ecs myecs
docker context ls
docker context use myecs
```

## Reference

- [setup aws cli](https://devops4solutions.com/configure-aws-cli/)
- [Deploy Docker container in ECS using docker compose](https://devops4solutions.medium.com/deploy-docker-container-in-ecs-using-docker-compose-7976989637de)

## VENV Commands

```
## Create env
python3 -m venv ecs_env

## Enable env
source ecs_env/bin/activate

## Disable env
deactivate

## List up installed package list
pip3 list

## Export requirements
pip3 freeze > requirements.txt

## Import requirements
pip3 install -r requirements.txt
```
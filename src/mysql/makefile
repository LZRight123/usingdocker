
default:
	ehco "input target"


test:
	docker run -it --rm --name mysql_test \
	-e MYSQL_ROOT_PASSWORD=liangze123 \
	mysql \
	bash


docker_run:
	docker run -p 3306:3306 --name mysql \
	-v ~/Github/docker/src/mysql/conf:/etc/mysql \
	-v ~/Github/docker/src/mysql/logs:/var/log/mysql \
	-v ~/Github/docker/src/mysql/data:/var/lib/mysql \
	-e MYSQL_ROOT_PASSWORD=123456 \
	-d mysql 

docker_compose:
	docker-compose up -d
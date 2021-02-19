

default:
	echo "输入target"

# 验证
config:
	docker-compose config 


# up
up: 
	docker-compose up -d


debug:
	docker run -it --rm --name debugnginx nginx  bash

cpnginxshare:
	docker cp debugnginx:/usr/share/nginx/ ./usr/share/
	
cpnginxconfig:	
	docker cp debugnginx:/etc/nginx ./etc
docker container run -d --name nginx -p 80:80 -v $(pwd):/usr/share/nginx/html nginx

docker container exec -it nginx bash

cd /usr/share/nginx/html/
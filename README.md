# docker-test example
### Installation
<pre>
cd/home
git clone https://github.com/kimgy0/docker-test.git
cd Docker-Practice
</pre>

### Run
<pre>
#Login For Private Docker Repository
docker login
docker pull kgy8294/docker-practice
docker run -p 80:80 -v /home/Docker-Prcatice/Project:/var/www/html kgy8294/docker-practice
</pre>

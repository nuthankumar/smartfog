
java -version

mvn -version

git clone 

cd .\smartfog\smartfog_containers\app1\

mvn dependency:tree

mvn clean install

mvn spring-boot:run               # to run on host

docker build -t app1:v1 .

docker run app1:v1                # to run on Docker

cd .\smartfog\smartfog_containers\app2\

mvn dependency:tree

mvn clean install

mvn spring-boot:run               # to run on host

docker build -t app2:v1 .

docker run app2:v1                # to run on Docker


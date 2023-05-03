docker build -t api1 -f /root/Docker/Dockerfile.api1 .

docker run -p 5000:5000 api1

docker build -t api2 -f /root/Docker/Dockerfile.api2 .

docker run -p 5001:5001 api2

docker build -t api3 -f /root/Docker/Dockerfile.api3 .

docker run -p 5002:5002 api3



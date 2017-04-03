# UE4MasterServer Docker Container

https://github.com/RyroNZ/UE4MasterServer

# Setup
git clone https://github.com/DaveM2011/UE4MasterServer.git

docker build -t bigdave2011/ue4masterserver .

docker run -d --restart=unless-stopped --name ue4masterserver p- 8081:8081 -t bigdave2011/ue4masterserver

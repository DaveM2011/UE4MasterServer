# UE4MasterServer Docker Container

# Setup
git clone git@github.com:DaveM2011/UE4MasterServer.git

docker build -t bigdave2011/ue4masterserver .

docker run -d --name ue4masterserver p- 8081:8081 -t bigdave2011/ue4masterserver

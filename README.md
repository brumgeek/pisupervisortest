# pisupervisortest

Supervisor test docker file for raspbery pi based on setting from [docs.docker](https://docs.docker.com/articles/using_supervisord/)

# Build 
docker build -t <<yournamei>>/supervisord .

# Run
docker run -p 22 -p 80 -t -i <<yourname>>//supervisord

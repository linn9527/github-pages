# github-pages

Docker for github pages

Usage:

1. Docker command

Download the image ``` docker pull toddylin/github-pages:latest ``` or build youself

Go into you workspace and run ``` docker run --rm  -p 4000:4000 -v ~/SourceTreeRepo/toddlam:/src/site toddylin/github-pages:lastest ``` 

Open your browser , visit `http://127.0.0.1:4000`

2. Docker compose

Copy the file ```example/docker-compose.yml``` to you workspace

Run ```composer up```

Open your browser , visit `http://127.0.0.1:4000`



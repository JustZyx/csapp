# TinyWebServer
A tiny web server to handle with static and simple dynamic requests

# Features
* single process
* GET method
* static resource requests，such as picture,html,etc

# Compile
```
gcc -o tiny tiny.c csapp.c -lpthread
cd ./cgi-bin/
gcc -o adder adder.c
```

# Run
```
./tiny 1024
```


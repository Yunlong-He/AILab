
It should be good choice to use Nvidia GPU Cloud, which contains many docker images for you. Before using it, you need to do following:

1. install OS, like Ubuntu, on a PC with GPU, and donnot use that GPU for monior output
2. install GPU driver
3. before pulling images, register nvidia developer user 
4. register NGC user, generate API key in "SETUP"
4. install nvidia-docker
6. docker login with API key
7. pull images

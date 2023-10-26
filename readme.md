```sh
sudo docker run -it --rm --runtime=nvidia -v "$(pwd):/tf/notebooks" -p 8888:8888 tensorflow/tensorflow:latest-gpu-jupyter
```
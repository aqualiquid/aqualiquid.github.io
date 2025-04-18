# aqualiquid.github.io

docker pull sonoisa/deep-learning-coding:pytorch1.12.0_tensorflow2.9.1
docker run -d -it \
  --mount type=bind,source=/Users/wookyungan/Desktop/docker-3d-ml,target=/workspace \
  -p 8888:8888 \
  -p 6006:6006 \
  --name deep-3d-env \
  --restart always \
  sonoisa/deep-learning-coding:pytorch1.12.0_tensorflow2.9.1

# An L-CAS ROS2 docker image with OpenGL remote rendering using VirtualGL and TurboVNC

run with `docker run -p 5801:5801 -u ros -v /dev/dri:/dev/dri --gpus=all -it --rm test /bin/bash`

then run `/opt/VirtualGL/bin/glxspheres64` inside the container and be amazed.

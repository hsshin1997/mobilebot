
docker image build -t tb3 .

docker run -it --user ros --network=host --ipc=host -v $PWD:/workspace tb3



docker run -it --user ros --network=host --ipc=host -v $PWD:/workspace -v /tmp/.X11-unix:/tmp/.X11-unix:rw --env=DISPLAY tb3

# ROS
Jazzy

# Gazebo
Harmonic


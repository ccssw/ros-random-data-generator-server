# ROS Random Data Generator Server
ROS server to generate random 32 bits numbers based on libsodium function ```randombytes_random(void)```.
More info [here](https://doc.libsodium.org/generating_random_data).

Installation instructions [here](https://doc.libsodium.org/installation#compilation-on-unix-like-systems). 

## RUN
```
$source ./devel/setup.bash
$roslaunch random_data_generator_server random_data_generator_server.launch
$rosrun sample_client sample_client
$rosservice call /randombytes_random
```

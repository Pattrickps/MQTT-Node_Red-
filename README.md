# MQTT-Node_Red-

# Why Mqtt

The Internet of Things (IoT) has recently gained massive traction. IoT challenges enterprises, small companies, and developers with new problems to solve. While HTTP is the de-facto protocol for the human web, communication between machines at scale requires a paradigm shift— steering away from request/response and leading towards publish/subscribe. This is where the ultra-lightweight, massively scalable, and easy-to-implement protocol MQTT enters the picture.

# how to set galileo ip address

The foolowing links provide all the informations http://www.instructables.com/id/Intel-Galileo-Share-LaptopPC-WiFi-to-Galileo-over-/?ALLSTEPS http://www.instructables.com/id/Galileo-connect-to-Linux-OS-with-an-ethernet-cable/?ALLSTEPS 

# do this for setting MQTT client from iot.eclipse.org

go to this site for getting the MQTT CLIENT LIBRARIES https://eclipse.org/paho/clients/golang/ ,configure your environment and install Go now install the version control tool for “Go Get” from http://git-scm.com/download/linux note:iot.eclipse.org:1883 itself is a broker.u need not create a broker,just create the client in your system after running the above commands in linux,u will be asked to install mosquitto client in ur system-sudo apt-get install mosquitto-clients now to publish a message to the broker(from the client set up in your system)-type this in the linux terminal- mosquitto_pub -h iot.eclipse.org -p 1883 -t topic_name -m "hello my first mqtt msg"

# set MQTT

the folowing link shows how to setup Mosquitto in Intel Galileo https://software.intel.com/en-us/blogs/2015/02/20/building-and-running-mosquitto-mqtt-on-intel-edison 

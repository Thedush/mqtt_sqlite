sudo apt-get update
sudo apt-get upgrade
sudo apt-get install python-pip python-flask git-core
sudo pip install flask
sudo pip install paho-mqtt
sudo apt-get install mosquitto mosquitto-clients

testing
mosquitto_sub -h localhost -t test
mosquitto_pub -h localhost -t test -m "hello world"
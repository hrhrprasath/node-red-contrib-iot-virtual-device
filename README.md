# node-red-contrib-iot-virtual-device
This module provides a set of nodes in Node-RED to rapidly implement simulated IoT device behavior and use it to run many device instances.



[Read here](https://developer.ibm.com/iotplatform/2016/10/14/new-iot-dev-tools/) how to deploy a sample application to IBM Bluemix
 <img src="http://developer.ibm.com/iotplatform/wp-content/uploads/sites/24/2016/10/2016-10-13_14-36-22.png"/> 




## Install
Run the following command in your Node-RED user directory (typically `~/.node-red`):
```
npm install node-red-contrib-iot-virtual-device
```

### Nodes
<img src="https://developer.ibm.com/iotplatform/wp-content/uploads/sites/24/2016/10/Virtual-IoT-Device.png"/>
- **_Device Schema_** (configuration node) to define the device type
- **_Start Device_** to create a new instance of a device type
- **_Generate Event_** to send events to the IoT platform
- **_Set Properties_** to set properties of a device instance 
- **_Device Function_** to write customized behavior using a specific device instance properties
- **_Device Listener_** to react on changes in device instances state (e.g. property change)


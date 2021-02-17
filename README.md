# nodered-nissanconnect

Here are three NodeRed-Subflows that can be used to connect to the NissanConnect-Service (only the "new" service, > Mid 2019).
The subflows basically contains all the stuff from [dartnissanconnect](https://gitlab.com/tobiaswkjeldsen/dartnissanconnect).

Import NissanConnectSession, NissanConnectAction and NissanConnectStatus as Subflows in your NodeRed-Instance.

The "DemoFlow" shows how to use the Nodes. Dont forget to edit the MQTT-Node in the Status-Subflow. Also dont forget to edit the config-parameters (user, pass and timezone) in the DemoFlow.

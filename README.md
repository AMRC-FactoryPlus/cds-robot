# Factory+ Serial Robot Common Data Structure

The CDS is a common order and format of variables taken from different devices to ensure data/metadata is gathered in a consistent format when stored and shared across the the Factory+ architecture.

This initial draft was created from the Robot Companion Specification (https://opcfoundation.org/developer-tools/specifications-opc-ua-information-models/opc-unified-architecture-for-robotics) that has already been defined for OPC UA. This OPC UA data structure has been simplified for our use of MQTT/Sparkplug.

List of datatypes used for the variables in this CDS:
- String
- Boolean
- Int32
- UInt8, UInt16 and UInt32
- Double

These datatypes are what is currently being used. Any other Sparkplug compliant datatype can be used for "User_Defined" variables.

Example variable: an axis position tag would be located at `RoboticSystem/KukaRobot1/MotionDevices/Device1/Axes/Joint1/ActualPosition`.

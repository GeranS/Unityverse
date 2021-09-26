**Tags:** #Unityverse #UnityverseManual
**Related:** 
# Working
The Flight Assist Module is a Main Computer module integrated during Computer Core construction. It's coupled to the Engine Control Module and Thrust Control Module, and limited secured connections to the Reactor systems.

## Diagnosing Issues
Should the Flight Assist exhibit unusual or unwanted behaviour, there are various steps the engineering team should pursue to determine the cause of the malfunctions.  

### Erratic or Unpredictable Behaviour
1. If the system is erratic or unpredictable, check connections between inertial sensors and the Flight Control Module.
2. If the connections are not faulty, ensure inertial sensors are working properly. See Maintenance Manual for instructions.
3. If the sensors are not faulty, replace Flight Assist Module.

### Unresponsiveness
1. If the system is unresponsive, reboot the Flight Assist Module.
2. If rebooting does not solve the issue, or the issue soon returns, check Flight Assist Self-Diagnosis systems for faults.
3. If the Self-Diagnosis system is working properly, check the helm's controls.
4. If the helm's controls are working properly, replace Flight Assist Module.

### Limp Mode
1. Should the system give the message `Limp Mode Active`, replace Flight Assist Module.

### Intermittent System Outages
1. If the Flight Assist System suffers from intermittent outages, check power coupling between Computer Core Power Distribution Module and Flight Assist Module.
2. If this does not solve the issue, replace Flight Assist Module.

### Flight Assist Module replacement not available
1. Should no Flight Assist Module replacement be available, the engineering team should engage Manual Flight Mode by bridging the appropriate data pins in the Flight Assist Module housing connector.
	1. Bridge data pin A1 to B2
	2. Bridge data pin A2 to C7
	3. Bridge data pin A31 to A32
	4. Bridge data pin C35 to C36  

Warning, Manual Flight Mode is an emergency measure only, do not engage if replacement Flight Assist Module replacement is available or existing module is still partially working.
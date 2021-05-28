# -LPG-Gas-Leak-Detection-Systems-Based-on-Wireless-Sensor-Networks
<h1> Introduction </h1>

Fires due to gas explosions in Jakarta in 2018 increased to 95 incidents, compared to 2016 which experienced 45 incidents. The explosion of gas cylinders continues to increase every year due to the large use of LPG gas cylinders in the community, the gas cylinders then experience a physical decline in quality which can cause danger in every use of the gas cylinder. The absence of early detection of gas leaks can also result in accidents such as fires and explosions that lead to huge losses.

The cause of the explosion of the gas cylinder was due to several factors, including leaks in the hose, tube, or the regulator that was not properly installed. When there is a leak, there will be a strong smell of gas. This gas will later explode when there is an ignition or electric spark or fire. Explosions can be avoided if there is early treatment if a leak occurs in the gas cylinder.

The importance of this LPG gas cylinder leak detector device will greatly assist in the process of preventing an explosion. Wireless sensor network technology can be used to transmit data captured by sensors to a node, so that effective monitoring can be carried out if several LPG gas sensors are placed in several points of the room, especially in high-rise buildings.

Therefore, in this final project, the author will build a prototype implementation system that can be used as a detection tool for centralized LPG gas leakage in real time using wireless sensor network technology. This gas leak detection system uses Arduino Uno as a data processor from the sensor. The sensor used is the MQ-6 sensor which functions as a detector for the concentration of LPG gas in the air. For the transmission module using the LoRa Shield 915 MHz module. There are two subsystems of the system to be built, the node sensor and node gateway. The sensor node functions to process data from the sensor, then sends the data to the gateway node. If there is a gas leak, the exhaust fan and siren connected to the sensor node will be active. The gateway node functions to receive data from both sensor nodes. The data is displayed on the LCD screen. If a gas leak occurs, the gateway node will send an SMS notification to registered cellphones via the SIM800L module.

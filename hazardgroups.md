We have created 8 different hazard trees each related to a specific area of UAV safety 



__HG1: Hazards related to UAV collisions__
[[Hazard Tree]](human-interaction-hazards/collisions.md)

Collisions must be avoided between multiple UAVs, UAVs and other objects, and UAVs and the terrain. Collisions occur when a UAV flies too close to the ground or loses geolocation so that it crashes into the ground or buildings.  They can also occur when an operator assumes manual control during the mission without having full situational awareness of the UAV or without correct skills to operate the UAV.  Finally, midair collisions occur when UAVs collide in flight.
___

__HG2: Hazards related to Loss of communication with the UAV__
[[Hazard Tree]](human-interaction-hazards/communication.md)

One of the most common causes of accidents with UAVs is caused by loss-of-signal preventing the remote pilot (RPIC) from sending commands to the UAV or receiving status updates. RPICs communicate with their UAV by sending commands through a hand-held-controller (i.e., throttle, forward, backward, sideways, turn) or through use of a computer system (e.g., MissionPlanner, QGroundControl, or custom built software) operating over an alternate communication technique or frequency. Hazard mitigations are dependent upon the operating context -- specifically whether redundant communication paths exist, and whether the loss of signal is caused by a fault on the UAV or a communication failure.
___

__HG3: Hardware and sensors__
[[Hazard Tree]](human-interaction-hazards/sensors.md)

Hardware and sensor failures can cause numerous problems in the UAV's behavior. Failures can occur with diverse components such as propellers, transmitters, autopilots, batteries and connectors, GPS units, cameras, parachutes and more.
___

__HG4: Hazards associated with general situational awareness and operator empowerment during a mission__
[[Hazard Tree]](human-interaction-hazards/missionawareness.md)

Situational awareness is critical when operating UAVs. The operator needs awareness of the current state of the mission, comprehension of what is happening, and the ability to make correct decisions based on the current missions state. Hazards that impact situational awareness include UI design flaws that introduce problems such as information overload, attentional tunneling, excessive complexity, and/or encourage the operator to fall out of the loop and lose situational awareness.

___

__HG5: Hazards related to planning and managing flight routes__
[[Hazard Tree]](human-interaction-hazards/missionplanning.md)

Mission planning can be achieved through manually or automatically generating flight routes, where hazards can be introduced through creating, storing, and retrieving flight routes. In some systems missions are planned through setting modeling and setting goals. In such cases, hazards may be introduced through faulty algorithms related to goal optimization and task assignments. 

___

__HG6: Preflight Configuration and Prelaunch hazards__
[[Hazard Tree]](human-interaction-hazards/preflightchecks.md)

Many accidents are caused by problems in preflight checks. For example, (1) turning off the GPS Fix arming check whilst running indoor maintenance tests, and forgetting to reset the check, or (2) setting the RTL altitude above the legal limit. Many prearming checks could be automated through the software, while others require consistent preflight checks, and could be supported by checklists and best practices.
___

__HG7: Hazards related to flight authorization and other regulations__
[[Hazard Tree]](human-interaction-hazards/prohibited-airspace.md)

UAV flights must be in compliance with government and local ordinances and regulations. In the USA all commercial pilots must seek authorization for flights in controlled airspace. Activities such as logging or sharing data with the NASA infrastructure all serve to support compliance and safety, but exhibit clear tradeoffs against privacy.

___

__HG8: Weather related hazards__
[[Hazard Tree]](human-interaction-hazards/weather.md)

UAVs can only be flown in certain weather conditions with sufficient visibility and cloud cover above a minimum altitude. Numerous hazards are introduced when remote pilots deliberately or accidentally fly their UAVs in inclement weather.

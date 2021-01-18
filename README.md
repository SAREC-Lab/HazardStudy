## Mapping User Hazards for Emergency Response Missions with UAVs


### Hazard Categories

| Hazard Group | Description |
|:--|:--|
|[HG1 - Collisions](human-interaction-hazards/collisions.md)| Hazards related to collisions between multiple UAVs and/or UAVs and other objects|
|[HG2 - Communication](human-interaction-hazards/communication.md)| Loss of communication with the UAV |
|[HG3 - Hardware/Sensors](human-interaction-hazards/sensors.md)| Hardware and sensors |
|[HG4 - Mission Awareness](human-interaction-hazards/missionawareness.md)|Hazards associated with general situational awareness and operator empowerment during a mission| 
|[HG5 - Mission Planning](human-interaction-hazards/missionplanning.md)| Hazards related to planning and managing flight routes |
|[HG6 - Preflight Configuration](human-interaction-hazards/preflightchecks.md)|Prelaunch hazards|[preflightchecks.md]
|[HG7 - Regulatory Compliancev](human-interaction-hazards/prohibited-airspace.md)| Hazards related to flight authorization and other regulations|
|[HG8 - Weather related](human-interaction-hazards/weather.md)| Weather related hazards |



<br><br><br><br>



### Main Use Case

The use case describes... Multiple UAVs dispatched to search for victim in river or finding the victim under the ice.

[UC1 River and Ice Search & Rescue](usecases/main/RiverRescue.md ) 



### Supporting Use Cases

| Use Case      | Description                  | Link  |
| ------------- |-------------                    | -----     |
| SC1           | Activate and Arm | [ActivateAndArm.md](usecases/supporting/ActivateAndArm.md)|
| SC2           | Active Tracking  | [ActiveTracking.md](usecases/supporting/ActiveTracking.md)|
| SC3           | Area Flight Route Coverage | [AreaFlightRouteCoverage.md](usecases/supporting/AreaFlightRouteCoverage.md)|
| SC5           | End Mission  | [EndMission.md](usecases/supporting/EndMission.md)|
| SC8           | Image Capture and Analysis  | [ImageCaptureAndAnalysis.md](usecases/supporting/ImageCaptureAndAnalysis.md)|
| SC10          | Lease Airspace |[LeaseAirspace.md](usecases/supporting/LeaseAirspace.md)|
| SC11          | Synchronized Takeoff  | [SynchronizedTakeoff.md](usecases/supporting/SynchronizedTakeoff.md)|
| SC12          | Victim Confirmation  | [VictimConfirmation.md](usecases/supporting/VictimConfirmation.md)|

<a name="GeneralExceptions"> </a>

### General Exception Cases apply across all other use cases 

| Use Case      | Description                  | Link  |
| ------------- |-------------                    | -----     |
|   EC1         | Loss of Signal         | [LossOfSignal.md](usecases/general_exceptions/LossOfSignal.md) |
|  EC2   | Geofence Vicinity Breach |[GeofenceIncursion.md](usecases/general_exceptions/GeofenceIncursion.md)||
|  EC3   | Low Battery |[LowBattery.md](usecases/general_exceptions/LowBattery.md)|





# DroneSimulation_IA51-P20-G7
Repository for UTBM Work Project of Drone Simulation for IA51 P20 Group 7

Setup : 
- Install SARL Version 10.1 with JDK 11 and AirSim with Unreal 4.25
- Clone the AirSim to Java API from https://github.com/alexandrelombard/airsim-jvm-api, copy MultirotorClient.kt and RpcLibAdaptorsBase.kt from this git in airsim-jvm-api\src\main\kotlin\fr\utbm\airsim\api then build it with gradlew build install
- Import project on SARL as a SARL Maven Project (+ Maven Update check force update if not working ?)

With the help of the work from :

@misc{alombardSarlAirsim19,
    author = {Alexandre Lombard},
    title = {S{A}{R}{L} {A}ir{S}im interface},
    year = {2019},
    publisher = {GitHub},
    journal = {GitHub repository},
    howpublished = {\url{https://github.com/alexandrelombard/sarl-arisim-interface}}
}

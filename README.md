# DroneSimulation_IA51-P20-G7
Repository for UTBM Work Project of Drone Simulation for IA51 P20 Group 7

## Project description
In the context of a course at UTBM, we developed a Multi-Agents System to Simulate Autonomous Drones behaviors in Unreal Engine.

## How to run the project?
- Run executable.jar with a JRE and AirSim with Unreal 4.25 installed with an environnment setup (You can use the default one Blocks.sln)

## Requirements
- Install SARL Version 10.1 with JDK 11 and AirSim with Unreal 4.25
- Clone the AirSim to Java API from https://github.com/alexandrelombard/airsim-jvm-api, copy MultirotorClient.kt and RpcLibAdaptorsBase.kt from this git in airsim-jvm-api\src\main\kotlin\fr\utbm\airsim\api then build it with gradlew build install
- Import project on SARL as a SARL Maven Project (+ Maven Update check force update if not working ?)

## With the help of
- Alexandre Lombard

## Authors 
- Malek "M003T" Fardeau-Spire
- Enzo "Skydax-IT" Licata
- Théo "Tyriaax" Lieffroy

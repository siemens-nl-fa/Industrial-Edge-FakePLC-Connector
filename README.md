# FakePLC Connector
The fakeplc connector generates data from the [Tank Application](https://github.com/industrial-edge/miscellaneous/tree/main/tank%20application)


###### tags:
* machineState | Int
* numberProduced | :Int
* numberFaulty | Int
* actLevel | Real
* actTemperature | datatype:Real
* energyConsumptionFillingTank | Real
* waterConsumptionFillingTank | Real
* energyConsumptionHeatingTank | Real
* energyConsumptionFillingBottle | Real

## Scenario
![image](https://github.com/siemens-nl-fa/Industrial-Edge-FakePLC-Connector/assets/104070599/4f3dc760-3ad7-4c63-abab-2728a78172c9)

## App on device
Required apps for a minimum setup is FakePLC Connector, Databus and IIH Essentials.

![image](https://github.com/siemens-nl-fa/Industrial-Edge-FakePLC-Connector/assets/104070599/f61c846b-8855-4038-bbd1-cdc32f9f4718)

## Settings Page
For more information at own connectors please refer to [common payload format](https://github.com/industrial-edge/common-databus-payload-format)
Here you can setup connectivity. by default it connects to the ie-databus broker at ie/# and user/password: edge/edge

![image](https://github.com/siemens-nl-fa/Industrial-Edge-FakePLC-Connector/assets/104070599/8a839556-345c-47b8-806c-c8484fb66b03)

## Tags Page
Here you can setup your own tags, by default the tank application is used.

![image](https://github.com/siemens-nl-fa/Industrial-Edge-FakePLC-Connector/assets/104070599/6ab91f3d-334d-4128-9032-5480d2c77bf8)

## Setup Databus
please setup the databus as shown here [link](https://github.com/industrial-edge/S7-Connector-data-handling-getting-started/blob/main/docs/Installation.md)



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

# Installation

## Step 1 - Setup Databus
Please setup the databus as shown here [link](https://github.com/industrial-edge/S7-Connector-data-handling-getting-started/blob/main/docs/Installation.md)

## Step 2 - Install FakePLC Connector
Import the [fakeplc_connector.app]() file into your IEM (industrial edge management)

![image](https://github.com/siemens-nl-fa/Industrial-Edge-FakePLC-Connector/assets/104070599/2c3747de-7c01-47d5-8097-3b12ec6b5af0)

## Step 3 - Install and Use the IIH Essentials App
- Install IIH Essentials
- Open IIH Essentials
- Go to Settings (Navigation) > Databus Settings > Set broker url to : tcp://ie-databus:1883, username to : edge, passwod to : edge and save
- Go Connectors (Navigation) > A new suggestion should appear > Edit > Give it the name "Fakeplc Connector" > Activate status > Save > Now it should be connected
- Go to Assets (Navigation) > Add Multiple variables > Select all from FakePLC Connector and Save > Preview data > Checkbox Last Values and see the new Data.


![image](https://github.com/siemens-nl-fa/Industrial-Edge-FakePLC-Connector/assets/104070599/9975d331-aa73-4a65-adb6-1176e8b131f9)

![image](https://github.com/siemens-nl-fa/Industrial-Edge-FakePLC-Connector/assets/104070599/23942e05-fab7-4c56-87c5-e9e1742adfda)







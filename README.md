# Engine-Management-System
## Problem statement
To design and implement an MBD-based system that computes the appropriate fuel-injector pulse duration, idle-engine control, and spark advance.

## Motivation
* Optimize Performance: EMS helps optimize the performance of the engine by ensuring that it operates efficiently under various conditions. It can control variables like air-fuel mixture, ignition timing, and 
  turbocharger boost pressure to maximize power output and fuel efficiency.
* Emissions Control: One of the most critical reasons for EMS design is to control emissions and meet environmental regulations. An effective EMS can monitor and adjust engine parameters to reduce harmful 
  emissions, such as nitrogen oxides (NOx) and particulate matter.
* Fuel Efficiency: EMS plays a crucial role in improving fuel efficiency by managing fuel injection, ignition, and other parameters. This not only reduces operational costs for the owner but also contributes to 
  lower fuel consumption and reduced greenhouse gas emissions.
## Objectives
* To find fuel-injector pulse duration
* To find idle-engine control
* And also to find spark advance.
## Electronic Control Unit
It is an electronic device which has base numbers and parameters filled in its memory. With multiple sensors around a vehicle feeding the ECU data it can manage and control the electronic systems efficiently by giving orders to improve their output.
## How does it work?
An electronic control unit receives input from one or several parts of the vehicle and uses that information to take action if needed. For example, an airbag ECU receives information from crash sensors and seat sensors. When there is a crash, the ECU decides which airbags to deploy depending on where passengers are sitting. Then it tells the actuators to deploy them. Then the actuators convert the electrical signal into
the physical value needed, using valves, injectors or relays.Fundamentally, the engine ECU controls the injection of the fuel and, in petrol engines, the timing of the spark to ignite it. It determines the position of the engine’s internals using a Crankshaft Position Sensor so that the injectors and ignition system are activated at precisely the correct time. While this sounds like something that can be done mechanically (and was in the past), there’s now a bit more to it than that. Vehicles may contain over 100 ECUs that in addition to essential functions, like engine performance and power steering, control comfort and security features, such as parking assistance, memory seats and airbag deployment.
### Fuel mass flow rate:
* Q=𝑀𝑎𝑝/(A/F)
### Fuel injection pulse width:
* Tp=Q/K
Where,
* Q=Fuel mass flow rate
* K=Parameter of injector
* K= 1.4
* Tp=Map/((A/F)*K)
* Density, e=1.293 kg/m3
* Area, A=0.005024 m2
* Velocity, v= 2𝜋𝑅𝑃𝑀/60
* Radius r=40 mm
* F= MAF/(r*(𝑁/2)*(𝐴/𝐹))
* A=MAF/(𝑟(𝑁/2))
  |Engine speed|Engine load |Duty cycle|
  |-------------|------------|----------|
  |500-1000 |10%| 5|
  |1000-1500 |30% |10|
  |1500-2000 |70%| 30|
  |2000-3500 |80% |40|
  |3500-5000|90%||
#### Fuel injection pulse width
   ![Screenshot (105)](https://github.com/HARSHITHA123-TECH/Engine-Management-System/assets/83593454/febd0560-6c30-4de4-8c97-de50b14056b7)
#### Mass air flow rate
   ![Screenshot (109)](https://github.com/HARSHITHA123-TECH/Engine-Management-System/assets/83593454/b979924a-80d1-41d1-92b2-e3637d2d1207)
  
#### Throttle position
  
  ![Screenshot (111)](https://github.com/HARSHITHA123-TECH/Engine-Management-System/assets/83593454/6ff76cd9-5a63-4fff-8090-759026cfb682)
## Results
![Screenshot (60)](https://github.com/HARSHITHA123-TECH/Engine-Management-System/assets/83593454/33e797b6-0050-41e4-884c-302424d17385)
![Screenshot (61)](https://github.com/HARSHITHA123-TECH/Engine-Management-System/assets/83593454/9deb42ce-9345-4ffb-99d7-d515542bcdd2)

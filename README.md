# blockchain-vehicle-telemetry
A react app that uses blockchain to secure your vehicles telemetry data, and empower it! (Only if you want to)

### What is telemetry?
-> According to Google telemetry is - “the process of recording and transmitting the readings of an instrument.”
-> Definition of vehicle telemetry - “A vehicle telemetry system automatically records and transmits data from inaccessible sources, and allows remote access to information and services relating to the operation and performance of the vehicle.”

### What sort of data does it include?
-> These days vehicles are getting more and more complicated, the number of sensors per car has doubled in the last decade, which leads to more data being generated.
-> These sensors are present primarily for safety, hence a large amount of the data is external - real-time data on location, weather, and road conditions, as well as the speed, acceleration, and movement of other vehicles on the road.
-> Fleet operators mostly use this sort of data, owners recognizing the huge benefits of near real-time monitoring and management of their vehicles, regardless of location. 
-> Combining data gathered from multiple individual journeys - the impact of driver habits on fuel consumption helps fleet managers make more efficient and informed decisions
-> A large amount of internal data exists as well. This is used for vehicle diagnostics and refers to real-time data from the engine bay - o2 sensors, fuel/air pressure sensors, temperature gauges, throttle position, brake pressure, etc. 
-> This data is mostly used by vehicle manufacturers typically during the warranty period.
-> The most common use case is fault detection where an error report would be compiled and sent to the manufacturer.
-> In most cases, data is not continuously sent. Only in cases of surprise events such as a breakdown, or accidents is data sent to the manufacturer or insurance companies.

### Potential use cases
-> The fleet sector is a major driver in the evolution of telematics, with owners recognizing the huge benefits of near real-time monitoring and management of their vehicles, regardless of location. 
-> The idea of usage-based insurance exists, whereby the costs are dependent upon the type of vehicle used, measured against time, distance, behaviour and place.
-> Provides cheaper premiums for safer responsible drivers and vice versa
-> However, only often provided as an alternative to regular fixed premiums as it requires documentation of driving habits which raises privacy concerns, as a result not as popular.
-> Documented telematics can be used to improve used car sales - check whether a vehicle has been abused - even if it is low mileage

### Hurdles
-> The biggest hurdle for making telemetry data more useful is data security. Consumers oftentimes will say no to sharing their driving/vehicle data due to privacy reasons.
-> Monetary benefits help alleviate this problem - lower premiums, and higher resale values, but are not permanent solutions
-> Another reason for slow growth in this area is the difficulty regarding data transparency. Most consumers don’t know what exactly constitutes their vehicle telemetry, and as a result, are less likely to share it.
-> Lack of data standardisation - each manufacturer follows their own data standard - as a result, it becomes difficult & expensive to compare and contrast data from different manufacturers.
-> Data standards can also help end users/consumers understand what is being shared
-> Having access to and being able to standardise data from multiple sources is the key to making smart business decisions.

### To Do!
* Secure method to upload untampered Vehicle Telemetry to React App (Maybe OpenXC?) 
* Uploaded data must be timestamped 
* If there are gaps in the data record, show it
* Upload collected data to blockchain (On user consent)
* Once in blockchain, only requests to read data

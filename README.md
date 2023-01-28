# FactorioContainerSystemPrint
a list of factorio blueprint for a scalable factory on the cityblock model. I personnally refer to thoses module as container like in docker. the goal is to provide a set of module blueprint so thats its easy to start quickly and expand the factory.

# Features

- bulk logistic is done over rail.
- RHD rail system (like most car in the world except england)
- auto building of container once robot drone are unlocked
- scalable
- automatic load balancing. Train will only go to station that are full/empty (more under the train blueprint)
- each container has its own line of defense.
- train with one loco and two wagon

# Disclamer and acknoledgements
part of thoses design are a patch work of otherdesign who are not by me.
saddly thoses blueprint have been in my game for so long i cant even remeber where i took them but hey if you recognise part of your work, add yourself here.

# Contributing
if you feel like you improved the design and want to share it with the others, feel free to open a pull request.
if your change are not compatible with the rest of the module, make a fork instead and I will happily list it here

# Blueprint

## Genesis Container
this is the first one you should build. 
the core component are low tech and you can start building it right away. at first you might want to use 4 lane to import the iron and copper ore, the coal and the rocks. later one you might want to use the train.
the container will produce all the item you minght need in the beginning (electric miner, belt, robot arm, wall, landfill, energy, ammo and it have a basic red and green science setup.
the troughput is quite low (just under 50 red and 50 green / minutes) and you should upgrade whenever you researched all the bacic green and red science.
![image](https://user-images.githubusercontent.com/15912256/215102312-358356f1-9c61-4af2-9399-d52f0ca335c2.png)

click here to see the string : 
### [Genesis_Container](Genesis_Container.txt)

## coal Smelter Container
#### Input

- ore or iron
- coal

#### Output

- copper / iron plate or steel

#### Max troughput

- Not measured. feel free to do it and publish the result there

## electric Smelter Container
![image](https://user-images.githubusercontent.com/15912256/215142702-2382280c-d2ff-43ae-a36f-d157cfcdd717.png)

#### Input

- ore or iron
- 34.56 MW

#### Output

- copper / iron plate or steel (and brick)

#### Max troughput

- 7200 item / minute (1440 item / min for steel)

click here to see the string : 
### [ElectricSmelter_Container.txt](ElectricSmelter_Container.txt)

## Train Garage and Refulelling Container
![image](https://user-images.githubusercontent.com/15912256/215136268-700aff88-d610-40a6-8b89-4c1e53bb963d.png)

click here to see the string : 
### [TrainGarage_Container.txt](TrainGarage_Container.txt)

click here to see the string : 
###

## Green Circuit Container

click here to see the string : 
###

## Red Circuit Container

click here to see the string : 
###

## Blue Circuit Container

click here to see the string : 
###

## all science Container

click here to see the string : 
###

## Plastic and explosive Refinery Container

click here to see the string : 
###

## Sulfuric Acid and Lubricant Refinery Container

click here to see the string : 
###

## ammo factory Container
click here to see the string : 
###

## Belt, Arm, PowerLine, miner and Assembler Factory Module

click here to see the string : 
###

## Wall, Concrete, Oven, Factory Module

click here to see the string : 
###

## Robot, Roboport, chest Factory Module

click here to see the string : 
###

## Nuclear Fuel Processor Container

click here to see the string : 
###

## Nuclear Reactor Container

- 450 Mw output
- fully automatic with a master switch

![image](https://user-images.githubusercontent.com/15912256/215154829-12909552-2305-440f-8ff8-347dcf9f28ba.png)

click here to see the string : 
### [NuclearReactor_Container.txt](NuclearReactor_Container.txt)

## Atomic Bomb Factory Container

click here to see the string : 
###

## Solar panel, battery, laser Factory Container

click here to see the string : 
###

## Solar Panel with accumulator Container

- 604 solar panel, 515 accumulator, 0.85 ratio
- 25.36 MW average power

![image](https://user-images.githubusercontent.com/15912256/215139519-ffedc3c2-d590-4861-9c71-e2d9b7b64868.png)

click here to see the string : 
### [SolarPanelAccumulatorPowerPlant_Container.txt](SolarPanelAccumulatorPowerPlant_Container.txt)


## Rocket factory and Silo Container

click here to see the string : 
###

## Artillery Shell Factory Container

click here to see the string : 
###

## Container empty template
-6 Input or output
![image](https://user-images.githubusercontent.com/15912256/215141829-df80554a-2723-4831-8f7c-fc83f945d14d.png)

click here to see the string : 
### [emptyTemplate3I3O_Container.txt](emptyTemplate3I3O_Container.txt)


## Wall and Artillery
- self healing
- ammo delivered over logistic network
#### Straight Segment
![image](https://user-images.githubusercontent.com/15912256/215137620-143b36fa-af4d-4267-aaf9-64d22f297086.png)

click here to see the string : 
### [StraightFireWallSegment.txt](StraightFireWallSegment.txt)

#### Corner :
![image](https://user-images.githubusercontent.com/15912256/215137976-4fbd2692-21f0-4218-9135-76c167911d2c.png)

click here to see the string : 
### [CornerFireWallSegment.txt](CornerFireWallSegment.txt)

## Rail with powerlane
Note regarding the track : They are Right handed, so it mean the train goes the same way as you would drive a car in most of the world (your right hand -> sidewalk, lefthad -> inverse traffic

Note Regarding the station name : inlet mean you dump train stuff here, outlet mean you fill your train here. Each inlet family must the have the same name for the load balacing to work. the train will do a simple loop like -> Refueling -> Xoutlet -> XInlet -> Refueling -> ...
where X is the name of the ressource.

Note Regarding the load balancing : each station has a simple logic circuit that disable the station if the inlet is not empty / outlet not full so that train can fully load / unload when they are request.

Note regarding Train size : train are made with one locomotiv and 2 freight wagon. that mean 8k items per train.

Note regarding inlet and oulet : in their most efficient configuration (24 stack inserter per train) thats 14'400 item / min so you empty/fill a train in a bit more than 30 sec and you should be able to saturate 8 lane of yellown belt if you manage to have one train per minutes (66 sec) on the station

#### Outlet/loading station
![image](https://user-images.githubusercontent.com/15912256/215125790-b34e8401-dbae-4362-81bc-ef3d3e498234.png)

click here to see the string : 
### [OutletStation.txt](OutletStation.txt)

#### Outlet/loading FLUID station
![image](https://user-images.githubusercontent.com/15912256/215130994-f0e22031-8a6f-468b-b96f-32ade9f01b8e.png)

click here to see the string : 
### [OutletFluidStation.txt](OutletFluidStation.txt)


#### Inlet/Unloading station
![image](https://user-images.githubusercontent.com/15912256/215129569-362e44e8-a192-4991-aedb-cb2550dce5de.png)

click here to see the string : 
### [InletStation.txt](InletStation.txt)

#### Inlet/Unloading FLUID station
![image](https://user-images.githubusercontent.com/15912256/215128440-73fe3888-78ae-4c54-bac6-3857422180e0.png)

click here to see the string : 
### [InletFluidStation.txt](InletFluidStation.txt)

#### Straight

![image](https://user-images.githubusercontent.com/15912256/215124668-3c314770-bbf5-4ae9-a86b-32839ff773b3.png)

click here to see the string : 
### [TrackI.txt](TrackI.txt)


#### Crossing
![image](https://user-images.githubusercontent.com/15912256/215120925-eb23f6f3-ce68-47c4-a6b8-febe14940ee6.png)

click here to see the string : 
### [TrackX.txt](TrackX.txt)


#### T
![image](https://user-images.githubusercontent.com/15912256/215123914-dd6871ba-0289-4cd7-9217-6452b4518f2c.png)

click here to see the string : 
### [TrackT.txt](TrackT.txt)


#### L
![image](https://user-images.githubusercontent.com/15912256/215125208-38104fe3-fadc-42bd-9bdf-0f4639a0cb51.png)

click here to see the string : 
### [TrackL.txt](TrackL.txt)


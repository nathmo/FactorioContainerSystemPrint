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
- limited requirement in hardware (mostly no high tier part, green, red and blue science are enough)
  
# Disclamer and acknoledgements
part of thoses design are a patch work of otherdesign who are not by me.
saddly thoses blueprint have been in my game for so long i cant even remeber where i took them but hey if you recognise part of your work, add yourself here.

# Contributing
if you feel like you improved the design and want to share it with the others, feel free to open a pull request.
if your change are not compatible with the rest of the module, make a fork instead and I will happily list it here

# TODO

- improve genesis module

# Blueprint

## Genesis Container
this is the first one you should build. 
the core component are low tech and you can start building it right away. at first you might want to use 4 lane to import the iron and copper ore, the coal and the rocks. later one you might want to use the train.
the container will produce all the item you minght need in the beginning (electric miner, belt, robot arm, wall, landfill, energy, ammo and it have a basic red and green science setup.
the troughput is quite low (just under 50 red and 50 green / minutes) and you should upgrade whenever you researched all the bacic green and red science.
if you aldready have a base you can bypass these and just build the mall

![image](https://user-images.githubusercontent.com/15912256/215102312-358356f1-9c61-4af2-9399-d52f0ca335c2.png)

click here to see the string : 
### [Genesis_Container](Genesis_Container.txt)

## Genesis Container Step 2
this is an upgrade for the first genesis container. it should allow you to unlock all the research for others module (green + red)
and make little of blue science and cliff explosive

![image](https://user-images.githubusercontent.com/15912256/216284212-9828dc2d-7c88-41c8-b193-9f4014ada4eb.png)

click here to see the string : 
### [GenesisStep2_Container](GenesisStep2_Container.txt)

## coal Smelter Container
![image](https://user-images.githubusercontent.com/15912256/216281878-263dc2fe-0f80-4bcb-bd9a-dedccce24b59.png)
it is coal powered.
#### Input

- ore or iron plate
- coal

#### Output

- copper / iron plate or steel

#### Max troughput

- 7200 item/min (1200 Steel)

click here to see the string : 
### [CoalSmelter_Container.txt](CoalSmelter_Container.txt)

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
![image](https://user-images.githubusercontent.com/15912256/215359252-a2f9e262-c2e3-45dd-a99c-996967d971c5.png)

#### Input

- iron
- copper
- 24 MW

#### Output

- green circuit

#### Max troughput

- 5670 item / minute

click here to see the string : 
### [GreenCircuitFactory.txt](GreenCircuitFactory.txt)

## Red Circuit Container
![image](https://github.com/nathmo/FactorioContainerSystemPrint/assets/15912256/d4223eb5-9592-40e6-8c81-fcde4df4be1f)

#### Input

- iron
- copper
- plastic
- 11 MW
#### Output

- red circuit

#### Max troughput

- 360 item / minute

click here to see the string : 
### [RedCircuitFactory.txt](RedCircuitFactory.txt)

## Blue Circuit Container
![image](https://user-images.githubusercontent.com/15912256/215359812-7e79ca2b-d167-4835-ab0a-8fbcac88a513.png)

#### Input

- iron
- copper
- plastic
- 12 MW
#### Output

- blue circuit

#### Max troughput

- 360 item / minute

click here to see the string : 
### [BlueCircuitFactory.txt](BlueCircuitFactory.txt)

## all science Container
![image](https://user-images.githubusercontent.com/15912256/215360400-b85f045a-03c7-45d3-9cc5-4d175ad7039f.png)

click here to see the string : 
### [AllScienceModule.txt](AllScienceModule.txt)

## Plastic and explosive Refinery Container
![image](https://user-images.githubusercontent.com/15912256/215360262-79242b1a-9379-42b0-a210-e4ba22212eeb.png)

click here to see the string : 
### [PlasticAndExplosiveRefinery_Container.txt](PlasticAndExplosiveRefinery_Container.txt)

## Sulfuric Acid and Lubricant Refinery Container
![image](https://user-images.githubusercontent.com/15912256/215359983-c9a42364-7b1d-4179-8358-86285664510e.png)

be careful. it require an external pipeline for water and oil

click here to see the string : 
### [SulfuricAcidAndGreaseRefinery_Container.txt](SulfuricAcidAndGreaseRefinery_Container.txt)

## ammo factory Container
![image](https://user-images.githubusercontent.com/15912256/215358494-30561b28-663b-4e6f-9cc7-bd136402bbf5.png)



click here to see the string : 
### [ammoFactory_Container.txt](ammoFactory_Container.txt)

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

![image](https://user-images.githubusercontent.com/15912256/215359117-45921a59-96e7-4e74-a64a-7e563b1e7f80.png)


click here to see the string : 
### [NuclearEnrichment_Container.txt](NuclearEnrichment_Container.txt)


## Nuclear Reactor Container

- 450 Mw output
- fully automatic with a master switch

![image](https://user-images.githubusercontent.com/15912256/215154829-12909552-2305-440f-8ff8-347dcf9f28ba.png)

click here to see the string : 
### [NuclearReactor_Container.txt](NuclearReactor_Container.txt)

## Atomic Bomb Factory Container

![image](https://user-images.githubusercontent.com/15912256/215358354-53468ed3-e60a-4b34-8ab6-1951264ae81c.png)


click here to see the string : 
### [AtomicBombFactory_Container.txt](AtomicBombFactory_Container.txt)

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

![image](https://user-images.githubusercontent.com/15912256/215358751-c5d0bd1d-6f5d-4c42-b073-44b4a1d2434b.png)

click here to see the string : 
### [rocketFactorySilo.txt](rocketFactorySilo.txt)

## Artillery Shell Factory Container
![image](https://user-images.githubusercontent.com/15912256/215360147-41aa9669-f059-49c3-a35e-a6eff6afbdf8.png)


click here to see the string : 
### [ArtilleryShellFactory_Container.txt](ArtilleryShellFactory_Container.txt)

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


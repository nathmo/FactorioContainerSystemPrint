# FactorioContainerSystemPrint
a list of factorio blueprint for a scalable factory on the cityblock model. I personnally refer to thoses module as container like in docker. the goal is to provide a set of module blueprint so thats its easy to start quickly and expand the factory.

# Features
- bulk logistic is done over rail.
- RHD rail system (like most car in the world except england)
- auto building once robot drone are unlocked
- scalable
- automatic load balancing. Train will only go to station that are full/empty (more under the train blueprint)
- each container as its own line of defense.
- train with one loco and two wagon

# Disclamer and acknoledgements
part of thoses design are a patch work of otherdesign who are not by me.
saddly thoses blueprint have been in my game for so long i cant even remeber where i took them but hey if you recognise part of your work, add yourself here.

## Genesis Container
this is the first one you should build. 
the core component are low tech and you can start building it right away. at first you might want to use 4 lane to import the iron and copper ore, the coal and the rocks. later one you might want to use the train.
the container will produce all the item you minght need in the beginning (electric miner, belt, robot arm, wall, landfill, energy, ammo and it have a basic red and green science setup.
the troughput is quite low (just under 50 red and 50 green / minutes) and you should upgrade whenever you researched all the bacic green and red science.
![image](https://user-images.githubusercontent.com/15912256/215102312-358356f1-9c61-4af2-9399-d52f0ca335c2.png)

## coal Smelter Container
#### Input
- ore or iron
- coal

#### Output
- Metal plate or steel

## electric Smelter Container

## Train Garage and Refulelling Container

## Green Circuit Container

## Red Circuit Container

## Blue Circuit Container

## all science Container

## Plastic and explosive Refinery Container

## Sulfuric Acid and Lubricant Refinery Container

## ammo factory Container

## Belt, Arm, PowerLine, miner and Assembler Factory Module

## Wall, Concrete, Oven,  Factory Module

## Robot, Roboport, chest Factory Module

## Nuclear Fuel Processor Container

## Nuclear Reactor Container

## Atomic Bomb Factory Container

## Solar panel, battery, laser Factory Container

## Solar Panel with accumulator Container

## Rocket factory and Silo Container

## Artillery Shell Factory Container

## Container empty template

## Wall and Artillery

## Rail with powerlane
Note regarding the track : They are Right handed, so it mean the train goes the same way as you would drive a car in most of the world (your right hand -> sidewalk, lefthad -> inverse traffic

Note Regarding the station name : inlet mean you dump train stuff here, outlet mean you fill your train here. Each inlet family must the have the same name for the load balacing to work. the train will do a simple loop like -> Refueling -> Xoutlet -> XInlet -> Refueling -> ...
where X is the name of the ressource.

Note Regarding the load balancing : each station has a simple logic circuit that disable the station if the inlet is not empty / outlet not full so that train can fully load / unload when they are request.

Note regarding Train size : train are made with one locomotiv and 2 freight wagon.

#### Outlet/loading station
![image](https://user-images.githubusercontent.com/15912256/215125790-b34e8401-dbae-4362-81bc-ef3d3e498234.png)

<details>
  <summary>String</summary>
  ```
0eNqlmNtuozAQht/F11DFB06Rdp9gpb3ZuypCBJzWWjDImGqjKO++BtKUINPa04tWgti/f2Y+8Hgu6FgPvFNCarS/oIr3pRKdFq1Ee9QOuuYaBUiUrezR/vmCevEii3ocqs8dN2OE5o0ZIYtmvFKFqNHVTJAV/4f2+Bp8OUWbOTLsddstJhLrxDeh9GDu3OfOI8Lfi5nUa+afxUx2PQSISy204PPDThfnXA7NkSvzNPfZp6LXoZA9V9r8EKCu7cUcswsySmGSkacoQGfzIDh6iswalVC8nIfEo8OVNLlLN7wSQxPy2gxXogy7tubWFfB9BTatILl4eT22gxq9E3ywrEI/Hl9zXoflK+/1F+KzfZN/Ofvvx0F4/Kd4tYySMFfp9XC9WhZmi4WL8u/nodv5hS5aaBuUXl51OFFokU6zd2GbyRiU3sTFYwKSjl2kU0BOY5+c0sWi43W2keMMYCTxg+vRiMmi3QnewXBzijfGMHEnTjABwJxYY0BByGVOLhlIO3XSjgAYpT4YZWuM4i2MYoCVzMeKIfjRCyFbXhIYdW4xT2HibrBkAKQzWwzIDoId2Tntv/gbGzDBlg04YLFtCybEH6rbI7hCFa+hSjagIhSUd8eIMv+8E2y1GYHyTp1cgjZ9Qpy0E0CqiU+qCVmneqsAI4Ay4RZBVy/JygtlW14yGHZOQaewvd+NFooBTFNbDCgBcedUEFPQ1k+YkzYDcMS8OFqXeXSrzKOAUoF4HWcMwo9eGN7yEsOwcws6bPN3pCUFMG09P9EMxJ1TYcxge79TRc8wgCO/I9S6zmNbdR6DlAdepyiG114MAKVQ5SD0XD9sWQNWC245gHUIHOEBtAiI9VTF4u+Uialrn4YlAMPWmpl9vN0VL0XFVVi2zVHIQrfqc7sUP0aWTYhp1db5kb8Wb8IITB3DSTY3v1XiTt9JqF7nX3T+BlXIMYat4mgG2OR+7EOSaLfbjTearlCT0z36aea1g+4Gi+xWd+/XLNudjbtB6vyk2iYX0mig/amoe371eG/GVzZAZOPnaPO1AZx/qLUOjnYAJWv1EWFb99VKw00mcmKh57LKdZtPorcQB/MS+bhEx6vcrzXbcz2r9XktGmHyptXwrnm758WDR8JX38Xpkx2Mn6dbd/x5pPnHAuLDrV9uizigsWOCPnakp3dmv2jTB6gujrxe9uffuOonCZJiZjbAJI7M39gZ+g+vHcqz
  ```
</details>


#### Outlet/loading FLUID station
![image](https://user-images.githubusercontent.com/15912256/215130994-f0e22031-8a6f-468b-b96f-32ade9f01b8e.png)

<details>
  <summary>String</summary>
  ```
 0eNqll01vozAQhv/KymeoMIYQkHaPe1qpl71VESLBSa0Fg/xRbRTlv+8Y0sI2RsHuoVWdeB5mXr8zLhe0bzTtBeMKFRdUU3kQrFes46hAPxvN6m/PWjVUoQCxQ8clKl4uSLITrxoToM49hZ1M0RZ28Ko1K1GxBl0hgNf0LyrwNXgYIlUnqhMNVcX/zEJja+gbE0rDJ1P0sCN8nkUSp8jfs8jkugsQ5YopRsdyh8W55LrdUwH1zLKGUk+vKhwqDlDfSTZqd0FACgnJA3SGP3CaX01Cn0jxB8mAeAgq9FZMNmECBMegRNeUe/pavbFOmG2S8rpUXTlwUHGsGkmDkVoaak/r0k0NSdVIk2XDWgb2UEK/M2+frUf+Qtcxc04PpjRpYrD5JWg9F5nBags7mThoeIBZxtedCZaquvny5WiM+V3q5qgFO4TVgdW7brSpRWVid5lN5+QpfVd6+5TCQ2smxoRvXvyETnyskNmskHolmUKSFtjGJy0rKfMhERtp+0GqKZwXFeGha/eMV1Cu3fNTmWTB9TdSCd/V7MNWRyakxZqDaWbGnLsHjQ8Ai5k5mEVRZNZtX4khvQL9gEBwWK/dPG8o/Rny01yVR9G1JePAuDWoQ0vk0AMBihe+HTrEonnuZar4zvm+nYsX8sKRj62wFTVN4163D6Zn9LmyjY04TeWewQHbiOmkVmRvQUw8SkystwSepkxLa6bbkDZQgPFu3zX0QfMk+VA0p5DCvtPCXGkk2dmek66XMtmuknLjIuXAtFEyJ0q+QNn6HIh1VuPcQajNGqHi6L8SQ9WFJwFDo37QqwPdxsOPJZtRsgWKUycs5kKcKEu5+Fy1iR3l4vNk1fFtPI/vjp7Y6G7+TxYE9PK/9SqPXfwfrxGQRE5+JfYSCXYSaoni5vp4geI1/61XHPna/Mf38x9b5z9x6YtVVylxm/94QUo3/y9cyMTH/wQuZHgbHN5Vi9mrcoCaak+b+3fkNyrk+D/TFkZZHmebFH4wXCP/ADUb9yk=
  ```
</details>

#### Inlet/Unloading station
![image](https://user-images.githubusercontent.com/15912256/215129569-362e44e8-a192-4991-aedb-cb2550dce5de.png)


<details>
  <summary>String</summary>
  ```
0eNqdWV1vqzgQ/S9+hisMHgzR7g+40mqf9u0qighxW2sJIGOqrar89zUhTVOuSX0SqUkhzDnjM3g+wjvbN6PqjW4t27yzgxpqo3uru5Zt2M+2UZZFTNddO7DNr3c26Oe2aqYr7Vuv3CXaqqO7oq2O05GpdMNOzqA9qP/Yhp+ib02ss2njwXb9jWHqNXzVxo7uzNV2viL+eWOZQZZ/31iK0zZiqrXaajUv9nzwtmvH414Zt5qr9VEd9HiMVaNqa3Qd912jHHbfDXpW7p05wJik+EERe3P/8iL5QY6rVfr5Zd+NZmLIku3k7YImvdI8VYONnT7t0HfGxnvVWB9Lnn+y8DPLQRvn2fma1MOQwQwSZBBfGXQ7KGPdF994nyyxhQebAGwJYuewMgJURsIMBDIUgD4C1KcEsAnE5gksTQZKwzlMkaIUKSBRikqUAeAZCr7YtKNLi+bZdO5zXR5+jyS6Zvy2Hy3zcRIckOROQHIfBb6n+R0Kr3ISCEuChqVA/acClaiEKUqQIk3CJbr1P0iilAPgJQoO12OSqDhwQaYcpQAqMqEVOQVKMqElOYX3LxEqDrB/CS1raeFrdX3N4geuLBcuR8z139Z0zW6vXqpX3ZnJaFDtYWe73RmVbZ6qZlDRzLGbOHp12AU3wv9MjfCg7Iw27Bp91G4gsGb8wLycC4f8i51OZ8/beSHDZMOnN6MOt/21dkepS0G1NvXoGM7Hp+1kPdjqMor8mqaGP+uuarb6PJX4pP7MYwdVa1e+4ro77nVb2c4bTMmvkv92n/hFv+Du3HcHfV3VkzaDR5mvg87kO5sVccuaxi2euNd04thX5uzjhv3hDLrRunoJKT2h9G/OrbG1uyfTHXdzzZ1vCyAQ2aR8xNK1OBVTYHwzRQJPR/lnnr/o/2U64pHIfPNR9pntB6tUE9cvavhuMLoQhIsQfT2Rry07DXZGPujMcmvwpW98zbfsxreq/jd0VJJFSF7LBIKeo+gUrKt4NMj5QkiRrAmZBztDjzrzW1RpzRmJ6E6o7gWCLlD0MljI9EEhXRAXURUrQook2Jns0ajSMqrlmjMc0T0DdRcpgp6i6Bme+vnd1O+KCQlf7hciOGbJozErlzeQXIsZIaomqKrBSYeKR/eKXCyV1kqJkMHOlI86I5a6r9VcgeSoW3/CdC8R9AJEp+CkQ4vmxQcW3AnRo82HWBZJWqtLhOQYQrsNQnoZQrsNEnAGI3E3g/lbVwruaujRRmJ1C1OOKIj2DSS/PAOKL7OLD/pe8fL9okq3292BP7/Y+PycyTfQyQ9oGQBcAsAEAOcJAJwhwBwA5ghwGg6clwhwBgAjwcsFAAwFjwBgKHg5AAwFT4YDExQ8YOcRFDxg5xESPAnsPFoP3jaaf7vZ3Dwcj1hT7VVz81T8VZlhNii4kGUqc3J/XJ5O/wOuDScy
  ```
</details>


#### Inlet/Unloading FLUID station
![image](https://user-images.githubusercontent.com/15912256/215128440-73fe3888-78ae-4c54-bac6-3857422180e0.png)

<details>
  <summary>String</summary>
  ```
0eNqlV8FunDAQ/ZXKZ4iwgWVB7bVSpKqn3qIIseBNrIJBxkRdrfj3js0mS5Khi2mkjQR4nt97HnvGZ3KoB94pITXJzqTifalEp0UrSUa+14OovtzLmmviEVG2sifZw5n04kkWtRmvTx2HgULzBkbIojFPqhA1GSFAVvwPyejo3QzpdauKJ+7rQv6ehTI09EUoPcCba7Qd4d/PIkOnyJ+zyGh89AiXWmjBJ7n24ZTLoTlwBXpmrEHq07P2rWKPdG0vJuvOBJD8JEk9cgIZYTIaPh+A2BtQJ4AeEr9nd/EFYX8XYxihC0aKY0RvGA2vxND4vOalVqL0u7bGMYN3mBDPwYdDOyjjGKOPyCzxlenQdCgqnWn1SCUU0LADdgjebsMypJj8xMHCKMAt3LtgUBwjXW2QZXHTIBq4OxRRjBmlLvIYLo+6pHsULoCE601iq0yKNpgUotRiF33Rgr6dC0i8AJKsNyleZdJ+g0k4tdRF3w7XxwIXkGQBhP7HqWeZfTj1IuzQY2z9UiRrloKFG5YCrz6Ri4sL5Yc5Jf1C/WErkj68CeKQ9Okqp7ckPVpg2DXpK16Kiiu/bJuDkAV0PShc8qo2Dt4ThTWDLkyrts4P/Ll4EQBg2zYLm8O3ykL15u1RqF7nn5qgo+nqZi3QUB8Hk/YFYJg+yLR50IdpU0Hgz7xoukJZshn5CpHtoLsBQV5qr35MsN0JCA5S50fVNrmQgEGyY1H3fJymlZNMS56af4pX8w4M+GVhMMJGI2zp8w4+o41SgDebWJ5Eb/bTj5nCVhM1q14KVQ5C22e6RGxDPxmjZTpkWyQuVKJww0ETo4Ux3FBiY5xTvEXgp3OVYdDXM8hwlD5M8M9DJE5W7cyeyyrXbW5BL9nuTVPkZoqOV+v30S+zj3quJ7Q+r0UjYAtpNbxiXt45bc1xc0ozk9LASBeXC+ODPVu+vTtSHoW9P2KeJxsSA2oZ3M/s7TGb3V09UhcHXn+6tL5w1U+LvqdRkrJkF8OPAspfUUfYoA==
  ```
</details>

#### Straight

![image](https://user-images.githubusercontent.com/15912256/215124668-3c314770-bbf5-4ae9-a86b-32839ff773b3.png)


<details>
  <summary>String</summary>
  ```
  0eNqdmc2O2jAYRV9l5HWQ8E/shHUX7bbtrkIVMNbUmhBQCKMixLvXgVGLptfTfneBRFB8uImO4mvnrNbdMe6H1I9qcVaP8bAZ0n5Mu14t1OePHx6+DqvN88OXcVilpx+jqlTa7PqDWnw7q0N66lfdNGw87WM+P41xm8/oV9vpKI/o1CUP6B/jT7XQl+qfQ9bpaRa7uBmHtJntd128G2/g+Jc0jMf8y2/E7YzZp7uR9rKsVOzHNKZ4S349OH3vj9t1HHK0P6Nfr3N2DV+p/e6QbjfjrDJpFuq6Uqf8pbaXKc8bkHnnShDMvMJcDtvH/Mfr3XGYIpp2CfD2/3O69r2cjrhgjUA1kQiCvDyRaxEoyBNhUEMkCgjUEokgSM+JSDUkaSITJhkiE3RSE3YXSITeDlqpCb8LJEJwC73UhOEFEqG4xWYSjmOSIRy30ExDOF4gEY5bPD8QjhdIhOMWmmkIxwskwnEDzTSE4wUS4bjBZrbc5G78X5N75edwep8TVw2zWqLRGOi+NUQmTLJEJui+dUQmTKqJTNB964lMmBTkmTR03zbyTAVSS2SCZjrC8QKJcFxDMx3heIFEOK5xQyccL5AIxzU00xGOF0iE41BMRyiOQYThUMuaEByDmFUpBBF6YxBhN1SyJuTGIMZtCGLUhiC52ZgjFxtz5F7DO+3nVPsBGxtVA/c2vLyu46Dysg5l9/Kqjjnyog4fB15e0zFHXtLhA9PLKzrmyAs6nlO8fA2KQUG+BMUzb5ArXQDJncb9JMilLoDkVuMWF+RaF0Byr3HXDXKxCyC52XhFEORmY1AjNxuvmxq52QWQ3Gy8umzkZhdAcrPxGryRm10Ayc3GeyGN3OwCSG423jFquD0Va97WCryh0sq7+JRzWd1eSy3u3o1VqlutY1d6KfYSh8OVZhrtQmuCr/NnelL9Aljv5YY=
  ```
</details>

#### Crossing
![image](https://user-images.githubusercontent.com/15912256/215120925-eb23f6f3-ce68-47c4-a6b8-febe14940ee6.png)
<details>
  <summary>String</summary>
  ```
  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
  ```
</details>

#### T
![image](https://user-images.githubusercontent.com/15912256/215123914-dd6871ba-0289-4cd7-9217-6452b4518f2c.png)

<details>
  <summary>String</summary>
  ```
  0eNqdmU9v4jAQxb9K5XOC4v8k5x5We1z1tkIrCFZrKQQUQrUV4ruvIYWFdNrO49BDqvjH84zH8wb2YtHswqaLbS+qvViGbd3FTR/XrajErx+PD08PP3f16TkTsV63W1H93ottfG7nzXFF/7YJ6dXYh1V6o52vjk/dPDbikBa0y/BXVPKQfbtkEZ/z0IS672Kdb9ZNuFqvyPWvset36T8XxPBG/nS1Uh9mmQhtH/sYBuWnh7c/7W61CF2S9n91n1Q/v/T5SXwmNuttHOKwF4mUe2sz8ZaQ8nCUM+KoLzZCsdTASjsTbUgfu1jvuqNAW2TWzogP0HyhpvxCqLlw6l33Gpafb9cNFJckLmMXhkNQWYJpbxKf1y/z2Obv+SLJk/dQqomlNDo8KZrieO5ezZTcqyGYUzwPpLbyNmafR8v462h9q08WePDIJEiJ75QGKVyRJ0F31AANMtiBNfacAj9OgabwFtjwoNPIW6ynsA7G6pKh1uPpKcmo3lEaNKgEQJbcKHVLqQLM+qXwSk7hKQmrHmddUljFvcScGaDmFqooqMZC4dTkrHgcClKz4YfCSTIU1ElV9/YZU9B9Rjl2M6RjS54DdtdJvZ6CkmcXqS1NRpTEluwOSWul7ildcFubO1eY0eNjRZ1aLcFTW2B4heG1w/BA93J+AHOwSK1ZPhboYU7zsQ6/GThYj3dcDhaoOgukrIQ7LgdrEOfHT5lBRiR+yoyC3QILi3hEfsqMwZs7B2vxa52DBarMACkDqkwDKQOqTAMpA6pM81NmC2zSd8NoaabjSV9RU76V4HhuC4ZkhVewZ0z9Gr9v/Pcuzxpwah+HgPIk1mJZ0w7KmgON6cVOf5gsyEB7EC8/xZOxmcLGxErGqSthY8LBugI2JiyshI0JC6tgY8LCatiYsLAGNiYsrIUvChbWwdcaC+thY8LCTmFjwsLi35VwsL6AjQkLK2FjwsIq2JiwsBo2JiysgY0JC2vhsdt++EbZUWCwux27DoL3XN2XgZsCz7LhB6Xq6getTDTzRWiIX7JeQ7cdIjmVxpcqdaD0J/3h8A8d/8nP
  ```
</details>

#### L
![image](https://user-images.githubusercontent.com/15912256/215125208-38104fe3-fadc-42bd-9bdf-0f4639a0cb51.png)


<details>
  <summary>String</summary>
  ```
  0eNqV1btugzAUBuBXic4MUmx8AdZ26NCp6lZFFRcrtUoMMiZqhHj3GojSJHIKHjKQcD792D9xD3nViUZLZSDtoRRtoWVjZK0ghbeX581Tp4+i3LzrrPjeJFsIQBa1aiH96KGVe5VV45w5NcIOSCMO9g6VHcYrnckKBjugSvEDKRqCxZFc7kNRicJoWYRNXYmreeycP0ptOvvNhZjvCF+vJqNhF4BQRhop5uTTxelTdYdcaBvtMl1MjxtO0QNo6lbOa9GDdcKY4ABOkBJm8VJqG3T6lY3R7kz8l8hYbv9lHqoRn1V6q2KHGnmodLVKPNRotUo9VLRaZetVcl6B5FblDpX/U0FX3nMPYisrYUPkdafHaiG2c+jx6n7Fk0vxbWLkMJO1ZsScpquzaOu9ZRQtbxlCHmwys3R5zxD2fG1pvLysyOMNI+esfHBBxB9KnBD1hhhyQsyv5GQuDsP3JeeujiPuHzNyxow9oOgC2b/46SxJr060AKosF9XDo+wodDu3NkaEJ5gzaj/I7ucvGRlQNQ==
  ```
</details>

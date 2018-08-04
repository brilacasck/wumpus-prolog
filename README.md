# The Wumpus World in Prolog

The Wumpus world problem deals with an **AI robot** navigating its way through a 4x4 puzzle to try and find gold.

The robot must safely navigate its way around bottomless pits of death and evil Wumpus creatures to locate the gold hidden on the board.

After it has successfully found the gold, it must safely navigate its way back to the starting point. The robot must use its light sensors and the signals sent to it at each square to determine which way to properly navigate to reach its goal.

***However, we change the dynamic of the world as following*** :

  * The world is rectangular (square) grid which is in the close space and it has widthxlength rooms. 
  * The goal of the agent is to go to outside using one of the exits which are in some rooms.
  * The exit is guarded and the only way for the agent to use the exit is to answer a question about the world to the gaurd, otherwise he will lose the game.
  * There is a flashlight or a light bulb in some of the rooms and agent can not enter any room that there is no light in it (whether by turning on the light bulb or by holding the flash light in his hand).
  * The agent also has some energy (power) which is going to be consume after each step that he will take and this energy consumption is related to wheather his hand is empty or not.
  * There is food in some rooms which agent can eat to increase his energy.
  * There is a giant in some of the rooms and the agent can only defeat the giant when he has a weapon otherwise he will die.
  * The sound of giant shout can be heard from adjacent rooms so when the agent will hear the shout, it means that there is giant in at least one of the adjadcent rooms. 
  
**Here is a picture of the world :**


![wumpus](http://i63.tinypic.com/9tenvd.jpg)


This code is implemented in prolog.

[Prolog](https://en.wikipedia.org/wiki/Prolog) is a general-purpose logic programming language associated with artificial intelligence and computational linguistics.

There are many different versions of prolog but the one that we used is [swi-prolog](http://www.swi-prolog.org/).

<hr />

## Dependency

SWI-Prolog is available in diffrent platforms.

you could find and download the version that you want from [here](http://www.swi-prolog.org/download/stable).

but for **Ubuntu** you can use the PPA as follow:

```
sudo add-apt-repository ppa:swi-prolog/stable
sudo apt-get update
sudo apt-get install swi-prolog
```

and for executing the code. Open a terminal and change the current directory to the directory in which there are is the source file (the code also needs the data.db file for configuration). Then run the **swipl** command to start SWI-Proglog and then for compiling and running the code you should enter the following to the terminal: 

```
['wumpus.pl'].
start.
```

<hr />

## TEST

You can **Run** the test online here: [play](https://showcase.brilacasck.ir/wumpus-prolog)

***Note That***

 - This is an online wumpus-game just for one testcase ( just a demo )
 - The codes for running GUI for this prolog codes isn't mentioned anywhere
 - If you realy need to get the **complete codes** both prolog and UI, just contact us: [email](mailto:brilacasck@gmail.com)

<hr />

## Authors

  - Amirhossein HassanKhani ( [@amirhossein-hkh](https://github.com/amirhossein-hkh) )
  - Alireza Kavian ( [@alirezakay](https://github.com/alirezakay) )

  
## Org.

  - ***[Brilacasck](https://brilacasck.ir)*** 
  
## Team
  
  - ***HAKA TEAM***

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details


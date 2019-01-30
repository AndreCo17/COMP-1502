# Assignnment 1 -  Creating a Hockey Time Keeper's Database

This documentation will outline the design of the first phase of the assignments in this course this semester. 
For this first phase we will create the basic components needed to keep track the individual player's data 
and allow the time keeper to add to the players' performance and keep track of them. With this in mind, as users 
of this program; we are able to interact with the public interface. Having the ability to load a list of players,
add a new player, list the players' roster information and list the players' stats. The timer keeper should also 
be able to record a player's shot, a goal with one or two assists, and a power play goal, with one or two assists.

## The Classes

### Interface

In the interface class, we are able to interact with program with the use of basic menus including options like:

* List Player Roster
* List Player Stats
* Add player
* Record a shot for player
* Record a goal for the first player, optionally assists for the second and third
* Record a power play goal for the first player, optionally assists for the second and third


### Player

The player class is repsonsible for managing information about every player in the women's inferno hockey team. 
When created, their will be two types of information, roster and play information. 

Roster will include basic individual players' information including:

* Their name
* Date of birth
* Home town
* Weight
* Height
* Number
* Positions of each player

Play information is an essential component of hockey where information about players and what they have done in the games they have played throughout their career. And this includes:

* Player jersey number (#)
* Assists (A)
* Goals (G)
* Player points (P) - ( Goals Scored and Assists )
* Power play goals (PPG)
* Power play assists (PPA)
* Power play points (PPP) - ( Power Play Goals (PPG), Power Play Assists (PPA) )
* Shots taken (S)
* Shooting percentage (S%)

### Methods in the player class

### Constructors
`public Roster()`

`public Recreation()`

`public Copy()`

### Mutator /setter methods

* `public void setName(String name)` -  .  
* `public void setDob(String dob)` -  .  
* `public void setHometown(String city)` -  .  
* `public void setWeight(String weight)` -  .  
* `public void setHeight(String height)` -  .  
* `public void setJerseyNum(String num)` -  .  
* `public void setPos(String pos)` -  .  

### Accessor / getter methods

* `public String getName()` - returns the value of the instance variable "name".  
* `public String getDob()` - returns the value of the instance variable .  
* `public String getHometown()` -  .  
* `public String getWeight()` -  .  
* `public String getHeight()` -  .  
* `public String getJerseyNum()` -  .  
* `public String getPos()` -  .  




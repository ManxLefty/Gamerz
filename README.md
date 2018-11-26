# Title: Gamerz (temporary)

# Contributors: Claire Picken, Iver (Sadie J. Warburton), Maura McGowan, Selah Finklestein
# Date: November 23, 2018
# Description: Group project for computer science.

from random import randint
# from graphics import *

class Player:
  def __init__(self, name):
    self.name = name
    
    
class Juicebox(Player):
  def __init__(self, name):
    super().__init__(name)
    self.name = "Timmy a.k.a. 'Juicebox'"
    self.description = "Timmy, nicknamed 'Juicebox' at school for his perpetual possession of a juicebox,
    typically of grape flavour.  Timmy was dared by his friends to enter this spooky house.  They sent him 
    with a flashlight, thank goodness.  However, to Timmy's great dismay, he flips the switch as the door slams 
    behind him and the flashlight hardly flickers before burning out.  Timmy feels panic rise up in his throat 
    but he swallows it with the conviction that this will impress other kids enough that they might want to be friends with him."
    self.max_hp = 50
    self.attack_power = 20
    self.defensive_power = 30
    self.fainted = False
#    self.num_revives = 0


class Bones(Player):
  def __init__(self, name):
    super().__init__(name)
    self.name = "Salem Bones"
    self.description = "An intimidating witch, though small in stature.  Dapper clothes."
    self.max_hp = 75
    self.attack_power = 20
    self.defensive_power = 5
    self.fainted = False
#    self.num_revives = 0


class Desdemona(Player):
  def __init__(self, name):
    super().__init__(name)
    self.name = "Desdemona Crowe"
    self.description = "A tall, thin, misty woman who almost seems to fade when you break focus on her."
    self.max_hp = 40
    self.attack_power = 30
    self.defensive_power = 30
    self.fainted = False
#    self.num_revives = 0


class Floor:
  def __init__(self):

class Room:
  def __init__(self):
#    size = (LENGTH, WIDTH)

class Library(Room):
  def __init__(self):

class Study(Room):
  def __init__(self):

class Observatory(Room):
  def __init__(self):



class Monster:
  def __init__(self, room):
  
  def attack(self, player):
    self.player = player
    player.defend()
    
class Banshee(Monster):
  def __init__(self, room):
      super().__init__(room)
      
  





def main():
  
  
if __name__ == "__main__":
  main()

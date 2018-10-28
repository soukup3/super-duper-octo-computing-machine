# X-Team 11 Food-o-Finder Project Proposal

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

When people go to fast food restaurants, they often don't know the best items on the menu and what to pair them with. Our plan is to implement a Food-o-Finder that helps customers decide the best meal combinations given an entree at a specific restaurant.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

Food-o-Finder

2. Output: Describe the output your program will produce.  Include and example format of the output produced.

The program will output all possible food combinations at a user-specified restaurant given an entree in the order of popularity. 

Restaurant: McDonalds

Entree: Big Mac

1- Big Mac + Drink + Sundae

2- Big Mac + Drink + Fries

3- Big Mac + Drink + Apple Pie

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

The names of popular fast food chains, their menus. 
Example input: "McDonalds", "Big Mac"

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

A webpage with buttons to choose from, the first button is the choice of the restaurant, the second one is for the choices of the entrees. Then all the possible combinations contain this entree will show up in an order of popularity.

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

Name each interface or class and briefly describe its function or purpose.

The menu items are implemented using Graphs (our main class). We will create an inner class for a hash table implemented with an array that holds the restaurant names. Another inner class for a hash table implemented with an array list will hold the all possible entrees.


## Edit and Submit this file and any figures referenced by this document.


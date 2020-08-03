- Design subscription-based sports website which can display scores, game status, history for any games.
- Design for online card game say like poker or any other game. 
- Design Truecaller.
- Design a geographically partitioned multi-player card game, that supports multiple players, multiple games at a time.
 Each game will have one contractor like ones we have in a bar, He can play a game or just watch it. Integrate payment systems.
 - design a system to fast lookup cars on the market according to the user's geo-position.
 - Design an airport service that will be used to allocate a free runway when the plane is about to land. Data structure for the same. What if the runway is not available? Message passing between control center and the plane. Focus on low-level design and code. Can the same runway be allocated to two different planes (locking)? Database storage needed?
 - Design a Ride Sharing Application where drivers can offer rides (origin, destination, no of seats), riders can request rides ( origin, destination, no of seats) and there is an algo to decide which driver should be given the trip in case of a collision ( maximum overlapping one).
 - Design a task planner. Different types of tasks are present – bug, feature and story. And their attributes are given. Also a Sprint which is a collection of tasks.
- Implement a finite state machine.
– The machine should have one start state and can have multiple end states.
   - It should be extensible (I should be able to add any number of states or transitions at any time)
   - I should be able to set notifications on or off for any state or for the whole state machine
- Design a system like Jira. It should have the following functionalities :
  - User should be able to create Task of type Story, Feature, Bugs. Each can have their own status.
  - Stories can further have subtracts.
  - Should be able to change the status of any task.
  - User should be able to create any sprint. Should be able to add any task to sprint and remove from it.
    - User should be able to print
    - Delayed task
    - Sprint details
    - Tasks assigned to the user
- Design a stock exchange system. There is a list of stocks given with following attributes 
  - order_id
  - time
  - stock name
  - type(BUY/SELL)
  - quantity
  - price
  
  You need to output list of stocks in the following format sell_id, buy_id, quantity, price which will get executed. 
- code a TextPad with following functionality:
  - display() – to display the entire content
  - display(n, m) – to display from line n to m
  - insert(n, text) – to insert text at line n
  - delete(n) – delete line n
  - delete(n, m) – delete from line n to m
  - copy(n, m) – copy contents from line n to m to clipboard
  - paste(n) – paste contents from clipboard to line n
  - undo() – undo last command
  - redo() – redo last command
  
   expected the textpad to be in memory(not as file) and also  expected to handle error gracefully and the program to be menu driven.

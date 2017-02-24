Sudoku Solver GUI
==================

For the Ringier Innovation Day 2017.


Goals:
------
- Have a react GUI and play with it.
- initial state, press button "solve".
- Solve.

Nice to have:
- Show how its been solved.


Learnings on the way (notes during the day):
----------------------
Board consists of components - maybe a good idea trying react?
Idea: Board --> Grid --> Cell as base structure.
React does not use styles?
How to compose components? --
Where does the state belong? Probably to the parent?
How do child components access the parents state?
Give up and use vanilla js instead, and react only as a starter template.

Goals reached?
--------------

- React GUI: yes, but using vanilla js after initing. React more complicated than thought initially.
- Solving: yes
- showing the way to solve: Only w/ console.log, not iteratively --> maybe a topic for next innovation day :) ?


Conclusion
==========

Innovation day was much fun, not all goals reached as plannned. React seems really promising for composing components (board, grid, cesll). Structure worked out well, but state handling is difficult (best way to propagate state changes to children not figure out during that day).



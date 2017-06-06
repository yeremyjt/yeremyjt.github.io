---
layout: page
title: My Code
subtitle: My recent coding projects
---

These are my most recent coding projects:

### Sudoku
I wrote an API that solves a 3 by 3 Sudoku board through three strategies:

- Find possibilities in each cell
- Process of elimination by box, column, and row
- Remove possibilities in cell

I then run the 2nd and 3rd strategies iteratively until the board is solved.

The code is found at [github.com/yeremyjt/sudoku](https://github.com/yeremyjt/sudoku)

Work in progress:

- Web UI is currently being written in Angular
- A fourth strategy needs to be implemented in order to solve a 4 by 4 grid.

#### Technologies:

- Java
- Springboot
- MySQL

### Gift Exchange
We have a sibling gift exchange every Christmas with my siblings. This used to be done by hand
by my sister, but she asked me if I could automate this, so I did. I wrote an API that assigns
sets of givers and receivers at random prevents repetition in such sets for at least two years.
It persists the data through a MySQL database.

The code is found at [github.com/yeremyjt/gift-exchange](https://github.com/yeremyjt/gift-exchange)

#### Technologies:

 - Java
 - Springboot
 - MySQL

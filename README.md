# Conway's game of life

## Introduction
Conway's Game of Life is a cellular automaton developed in 1970 by the mathematician John Horton Conway. It is a zero-player game, i.e. its development is determined by its 
initial state and requires no further input. You interact with the Game of Life by creating an initial configuration and observing how it evolves. 

**You can find a .exe file, inside the Release section of Github, if you want to try the project!**
<p align="center">
  <img width="512" height="512" alt="Conway-GIF" src="https://miro.medium.com/v2/resize:fit:640/format:webp/1*6wS-kXlOCBsAJciygkJtDA.gif" />
</p>


## Rules
The Game of Life is played on a grid of square cells. Each cell can be in one of two states: alive or dead. The state of each cell in the next generation is determined by the following rules:

- Underpopulation: any living cell with fewer than two living neighbours dies.
- Survival: Every living cell with two or three living neighbours lives on in the next generation.
- Overpopulation: Every living cell with more than three living neighbours dies.
- Reproduction: Every dead cell with exactly three living neighbours becomes a living cell.

## User interaction
Run the python file and use the following commands:
- Mouse interaction: Clicking on the grid toggles the state of the cells (alive or dead).
- Keyboard controls:
  - Spacebar: Starts or pauses the simulation.
  - Key C: Deletes the grid and resets all cells to dead.
  - Key G: Creates a new random configuration of living cells.
  - Left Arrow Key: Decrease the simulation speed.
  - Right Arrow Key: Increase the simulation speed.
  - Up Arrow Key: Zoom in by increasing the cell size.
  - Down Arrow Key: Zoom out by decreasing the cell size.

#### Main loop
Game loop: The main loop of the program controls the frame rate, checks for user input, updates the cell states and redraws the grid.

<p align=center">
  <img width="1024" height="924" alt="image" src="https://github.com/user-attachments/assets/cc870e86-0224-42e0-86af-946a8f6d1582" />
</p>

## Applications and simulations
Conway's Game of Life, while simple, has profound implications and applications in various fields:

### Computer science
- Algorithm development: The Game of Life is used to teach and explore algorithms, data structures, and computational theory.
- Artificial life: It serves as a model for the study of artificial life by simulating how simple rules can lead to complex behaviors and structures.

### Mathematics
- Complex systems: It shows how local interactions can give rise to global patterns, making it a valuable tool for the study of complex systems and emergent phenomena.
- Fractals and Chaos Theory: The game of life is used to study concepts of fractals and chaos theory due to its unpredictable and diverse patterns.

### Biology
- Population dynamics: It can simulate basic population dynamics and interactions within ecological systems.
- Cellular processes: The rules may be analogous to biological processes such as reproduction, survival and death in cellular structures.

### Physics
- Statistical Mechanics: The game of life is used to model systems of statistical mechanics and investigate how microscopic rules lead to macroscopic phenomena.

### Art and design
- Generative art: Artists use the Game of Life to create generative art and explore the aesthetic potential of algorithmic processes.
- Pattern formation: Designers investigate the formation of patterns and structures in order to apply them in various creative fields.

## Contributes
- Official site for playing Conway's Game of Life: https://playgameoflife.com/
- Wikipedia if you want to learn more: https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life


# CS 686
<p>Assignments for CS686, Intro to AI. Includes:

- **A1**:
  - Q1: **TSP** with A* search algorithm, heuristic functions, and heuristic function comparison plots
  - Q2: **Sudoku puzzles** with CSP algorithm solvers of different versions (standard backtracking search, forward checking, and heuristics (most restricted variable, most constraining variable, least constraining variable)), and plots of number of initial values v.s. average number of variable assignments for each initial value.
</p>

## Setup

### Version Control with Git
From [here](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)

### Environment
From [here](http://vision.stanford.edu/teaching/cs131_fall1718/assignment.html)
To set up a virtual environment with name .env, run the following inside the homework directory
<pre><code>
  sudo pip install virtualenv        # You will need to do this only once
  virtualenv -p python3 .env         # Creates a virtual environment with python3
  source .env/bin/activate           # Activate the virtual environment
  pip install -r requirements.txt    # Install all the dependencies
  # Work on the assignement for a while...
  deactivate                         # Exit the virtual environment when you're done
</code></pre>
 
<p> Note that every time you want to work on the assignment, you should run source .env/bin/activate (from within your assignment folder) to re-activate the virtual environment, and deactivate again whenever you are done.</p>

### Notebooks
From [here](http://cs231n.github.io/ipython-tutorial/)

### Structuring Assignment Submissions Inspo
From [here](https://github.com/jfranchetto/cs486/tree/master/a2)

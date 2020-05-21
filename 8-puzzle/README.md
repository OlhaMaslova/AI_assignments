# 8-puzzle

The N-puzzle game consists of a board holding N = m^2 − 1 distinct movable tiles, plus one empty space. There is one tile for each number in the set {0, 1,..., m2 − 1}. In this assignment, we will represent the blank space with the number 0 and focus on the m = 3 case (8-puzzle).

## Goal: 
In this combinatorial search problem, the aim is to get from any initial board state to the configuration with all tiles arranged in ascending order {0, 1,..., m^2 − 1}

## Implemented:
1. bfs (Breadth-First Search)
2. dfs (Depth-First Search)
3. ast (A-Star Search)

Argument Example: {0,8,7,6,5,4,3,2,1}

## To execute:
        $ python3 puzzle.py bfs 0,8,7,6,5,4,3,2,1

## Sample Output:
1. path_to_goal: ['Down', 'Right', 'Down', 'Right', 'Up', 'Up', 'Left', 'Down', 'Down', 'Right', 'Up', 'Up', 'Left', 'Down', 'Down', 'Left', 'Up', 'Up', 'Right', 'Down', 'Down', 'Left', 'Up', 'Right', 'Down', 'Right', 'Up', 'Left', 'Up', 'Left']
2. cost_of_path: 30
3. nodes_expanded: 181423
4. search_depth: 30
5. max_search_depth: 31
6. running_time: 5.76226425
7. max_ram_usage: 279.339008


![Image of terminal](https://github.com/OlhaMaslova/AI_assignments/blob/master/8-puzzle/terminal.png)

## Implementation Details
Implemented custom data structures combining benefits of a hashmap and:
  1. queue
  2. stack
  3. heap

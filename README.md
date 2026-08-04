# AI-LAB2a-BFS
Implementation of Breadth First Search for finding a target node in a tree

## My Approach
Start with a queue holding just the path [A]. At each step, take the path from the front of the queue, look at its last node, and if it's not the goal, add its children as new, longer paths to the back of the queue. Because we will always take from the front and add to the back, you end up clearing out an entire level of the tree before moving to the next one — so the search spreads outward level by level, and the first time you hit the goal, you're guaranteed it's via the shortest path.

## Files
- AI_LAB2a.py - the code
- notes - my handwritten notes for this lab

## How to run
```
python3 AI_LAB2a.py
```
## Code Snippet of the output for the problem
<img width="940" height="250" alt="image" src="https://github.com/user-attachments/assets/ef4ccda0-a819-448a-8626-10dc9ffc7a82" />

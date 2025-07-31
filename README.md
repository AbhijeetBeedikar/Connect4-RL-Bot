# Connect4-RL-Bot

An agent trained using Monte Carlo Search Trees constructed based on an Upper Confidence Bound Policy to play connect4. 
In this code, the agent can play against a human player or a random agent. With further modification it can play with other agents as well.
The agent is constructed such that it updates the MCST that it uses to make moves upon encountering new board configurations as it plays against an external agent, so it learns while playing

# MCTS trees

mcts_tree_10: The MCST developed from the agent playing 10 games with itself 

mcts_tree_25: The MCST developed from the agent playing 25 games with itself

mcts_tree_50: The MCST developed from the agent playing 50 games with itself

mcts_tree: mcts_tree_50 updated over a few additional games against a human

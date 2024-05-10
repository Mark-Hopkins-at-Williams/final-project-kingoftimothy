# CSCI 381 Final Project

Group members:
- Timothy Kim
- Trung Nguyen


Overview:
AlphaZero Implementation from https://arxiv.org/pdf/1712.01815 and https://discovery.ucl.ac.uk/id/eprint/10045895/1/agz_unformatted_nature.pdf

model_2.pt is the trained TicTacToe model model_7_ConnectFour.pt is the trained ConnectFour model

To use it, open TicTacToe.ipynb or ConnectFour.ipynb depending on what you want to look.
You can run all the boxes except the box that trains the models because we already uploaded the models we trained. You can have the AI play against each other on the bottom box of the notebook and can change different hyperparameters in the args as well as the number of Monte Carlo Tree Search iterations. The higher iterations requires more computing power but is more stronger in its decision making. The second to last box in either game notebooks is your ability to play against the AI for either game. If you want to train future models, you can adjust the hyperparameters and number of iterations of MCTS and run it. The code is optimized to be able to use GPU processing if available and uses CPU otherwise.

Link to Slideshow (Animated): https://docs.google.com/presentation/d/13aqQzVzzsL9_TbsLZzXpBIPbP4ZQOduHwyFVb8AEFFY/edit?usp=sharing

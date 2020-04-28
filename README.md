# Othello AI RLplayer
A Reinforcement learning player for the Othello or Reversi game.
Implementation of Q learning to play othello. Uses a double deep neural network and backpropagation for the Q function.
Implemented also Prioritized Experience Replay as memory. Implemented in python 3 with use of TensorFlow and Keras.
This was done as a project for a class in artificial intelligence in Unibo.

Game and SmallGame reprensent the game ambient, for a 8x8 board and a 4x4 board.
AIPlayer reprensent a simple player who uses casual valid moves.
DDQNAgent and SmallAgent reprensent the real RL agent; one for the 8x8 board and one for the smaller 4x4 board.
OthelloMain is the file where you can make the reinforcement learning and try play games against casual AIPlayer. Also are implemented different plotting function.

At last there is a report and a presentacion that i'm sorry but are written in Italian only.
A special thanks to the tutors and professor of the course for helping me; also thanks to this tutorials that helped me make this project:
http://realerthinks.com/creating-othello-tutor-step-1-making-playable-game/
https://jaromiru.com/2016/09/27/lets-make-a-dqn-theory/

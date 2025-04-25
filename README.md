# DataRes-RL.io
# WINTER 2025
## Game Ideas:
* Slither.io:
 * advantages:
   * only three inputs: left, right, boost
   * Can use images of game for training, no explicit gamestates needed.
   * Stanford CS Slither.io [Example](https://cs229.stanford.edu/proj2019aut/data/assignment_308832_raw/26588099.pdf)
   * RL [environment](https://gymnasium.farama.org/index.html)
* Connect4:
   * [environment](https://drive.google.com/drive/folders/16GSzgFau7pEjVV54gfqv04atl7KXIXas?usp=drive_link) (Coded by Larsen)
   * Larry Checkers Deep Q Learning [example](https://github.com/leighannelem/checkersRL_math156_24/blob/main/nb.ipynb)
   * Fully implemented Connect4 deep Q learning [example](https://github.com/neoyung/connect-4/blob/master/connect_X.ipynb)
   * To-Do's:
        * Make training loop for DeepQNet: Henry
             * Suggestion: make a function to take a gradient step given a batch of transitions, then use that for the training loop.
        * Make policy function for selecting an action given the values that the Q function outputs: Larsen
        * 

## Training Ideas:
* [Deep Q Learning](https://huggingface.co/learn/deep-rl-course/en/unit3/deep-q-algorithm) (read [Q-Learning](https://huggingface.co/learn/deep-rl-course/en/unit2/q-learning) first)
* Feed in screenshots of the game to choose the policy, learn policy values using temporally spaced screenshots of the game screen (see the Hugging Face deep Q learning example).

# SPRING 2025




<h1 style="text-align:center"> ChessAI </h1>
<p align="center">
<img src="https://github.com/Aditya-y9/COC_Project_X_ChessAI/assets/122613756/115ef908-24c8-4f61-9c20-ecab6fb383ec" alt="animated" height="300" width="500"  />
</p>

## Index
<ul>
    <li><a href="#demo">Demo</a></li>
    <li><a href="#about-the-project">About the Project</a></li>
    <li><a href="#tech-stack">Tech Stack</a></li>
    <li><a href="#file-structure">File Structure</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#features">Features</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#theory-and-approach">Theory and Approach</a></li>
    <li><a href="#future-scope">Future Scope</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
    <li><a href="#contributors">Contributors</a></li>
  
## Demo


#### Demo Video Link:
https://drive.google.com/file/d/1-EqixFDe9Iy7AqRsp5VVrwxX8uG5FjgJ/view?usp=sharing

### Demo GIF

<p align="center">
  <img src="https://github.com/Aditya-y9/COC_Project_X_ChessAI/assets/122613756/8b88e1c7-14c4-41bc-89e4-63fb4c08e287" alt="animated" height="300" width="500" />
</p>
<p align="center" font-size="30px">AI Move</p>

<p align="center">
  <img src="https://github.com/Aditya-y9/COC_Project_X_ChessAI/assets/122613756/85e2aa95-1bfb-467f-ba0d-e7e296b0f49e" alt="animated" height="400" width="500" />
</p>
<p align="center">Home Screen</p>

<p align="center">
  <img src="https://github.com/Aditya-y9/COC_Project_X_ChessAI/assets/122613756/df4df40b-a94b-41ce-919f-d022c4f9ba2d" height="400" width="400">
</p>
<p align="center">Our Chess Board</p>

<p align="center">
  <img src="https://github.com/Aditya-y9/COC_Project_X_ChessAI/assets/122613756/05a6666d-c55c-4cac-944f-7690ec610cf5" height="400" width="400"/>
</p>
<p align="center">Chess Board With Pieces</p>

<p align="center">
  <img src="https://github.com/Aditya-y9/COC_Project_X_ChessAI/assets/122613756/327727a2-ae72-46b8-aed3-c2e70753db65" alt="animated" height="300" width="500" />
</p>
<p align="center" font-size="30px">Undo Move</p>

<p align="center">
  <img src="https://github.com/Aditya-y9/COC_Project_X_ChessAI/assets/122613756/d7018ca7-8171-45f9-acf5-31e5aac8928c" alt="animated" height="300" width="500" />
</p>
<p align="center" font-size="30px">Castling Move</p>

<p align="center">
  <img src="https://github.com/Aditya-y9/COC_Project_X_ChessAI/assets/122613756/e232a89e-ffec-4ee7-9b10-e0920ce1b626" alt="animated" height="300" width="500" />
</p>
<p align="center" font-size="30px">Checkmate</p>


<p align="center">
  <img src="https://github.com/Aditya-y9/COC_Project_X_ChessAI/assets/122613756/7f2becfc-fb0b-42ec-9f69-40759a327391" alt="animated" height="300" width="500" />
</p>
<p align="center" font-size="30px">Stalemate</p>


<p align="center">
  <img src="https://github.com/Aditya-y9/COC_Project_X_ChessAI/assets/122613756/7b4a1d8d-c8db-4bcc-8dcb-306a35b984bb" alt="animated" height="300" width="500" />
</p>
<p align="center" font-size="30px">Enpassant Capture</p>

<p align="center">
  <img src="https://github.com/Aditya-y9/COC_Project_X_ChessAI/assets/122613756/e45163ba-631f-4081-8e5c-86af09f3bfae" alt="animated" height="300" width="500" />
</p>
<p align="center" font-size="30px">Reset Game</p>




## About the Project

### Aim: 
#### To create a highly intelligent AI opponent for players to play using the NegMax algorithm for evaluation of different possible moves and then choosing the best on the basis of evaluation score.

### Description:
#### The project is a chess AI that can play against a human player. The AI uses the NegMax algorithm with alpha-beta pruning to determine the best move at each gamestate.
<text>
    The project is written in Python and uses the pygame library for the GUI. The AI uses the NegMax algorithm with alpha-beta pruning to determine the best move at each gamestate. The AI is also able to play against itself.
    The AI understands each game state by assigining an evaluation score to each possible gamestate.
    The AI considers the following factors when assigning an evaluation score to a gamestate:
    <ul>
        <li>Material</li>
        <li>Positional Advantage
        <ul>
            <li>Control of the center</li>
            <li>Control of the center files</li>
            <li>Control of the center ranks</li>
            <li>Control of the center diagonals</li>
            <li>Control of the center squares</li>
            <li>Control of the center squares</li>
        </ul>
        <li>King Safety
            <li>Castling</li>
            <li>King's
            <ul>
                <li>Position</li>
                <li>Number of pieces attacking it</li>
                <li>Number of pieces defending it</li>
            </ul>
            <li>Number of pieces defending the King</li>
            <li>
            Double Pawns
            </li>
            <li>
            Queen Mobility
            </li>
            <li>
            King Mobility
            </li>
            <li>
            Freedom of Movement
            </li>
            <li>
            Knight Support
            </li>
        </li> 
Based on these factors, the AI assigns an evaluation score to each gamestate. 
Then the AI uses the NegMax algorithm with alpha-beta pruning to determine the best move at each gamestate.
</text>

## Tech Stack
This project is built using the following technologies:
<ul>
    <li>Python</li>
    <p align="center">
  <img src="https://github.com/Aditya-y9/COC_Project_X_ChessAI/assets/122613756/802f19c6-b6b2-44a3-b04a-11b7ae36348b" height="200" width="250">
</p>

<li>
    Pygame
<p align="center">
  <img src="https://github.com/Aditya-y9/COC_Project_X_ChessAI/assets/122613756/6082b663-abee-46ba-a51f-b0a8c16aa4cc" height="150" width="300">
</p>

<ul>
<ul>
        <li>Pygame is a Python library that is commonly used for developing 2D games. It provides a set of modules that allow developers to create games and multimedia applications. Pygame is built on top of the Simple DirectMedia Layer (SDL) library, which provides low-level access to audio, keyboard, mouse, joystick, and graphics hardware.</li>
        <li>Pygame is a popular choice for game development because it is easy to learn and use, and it provides a lot of functionality out of the box. It includes modules for handling graphics, sound, input, and networking, among other things.</li>
        <li>In the context of the provided code excerpt, Pygame is being used to build a chess game.Pygame is a Python library that is commonly used for developing 2D games. It provides a set of modules that allow developers to create games and multimedia applications. Pygame is built on top of the Simple DirectMedia Layer (SDL) library, which provides low-level access to audio, keyboard, mouse, joystick, and graphics hardware.</li>
        <li>Pygame is a popular choice for game development because it is easy to learn and use, and it provides a lot of functionality out of the box. It includes modules for handling graphics, sound, input, and networking, among other things.</li>
        <li>Pygame is being used to build a chess game.</li>
    </ul>
    </ul>
<ul>
    </li>
    <li>Numpy
        <p align="center">
  <img src="https://github.com/Aditya-y9/COC_Project_X_ChessAI/assets/122613756/3f695572-3d21-4d97-9d47-4122b85923d3" height="150" width="300">
        </p>

<ul>
    <li>NumPy, short for Numerical Python, is a fundamental package for scientific computing in Python.</li>
    <li>It provides support for arrays, matrices and a large library of high-level mathematical functions to operate on these arrays.</li>
    <li>NumPy's array object is more efficient and faster than Python's native list.</li>
    <li>It is an open-source module and is used in a wide range of applications including linear algebra, Fourier transform, and matrix computations.</li>
    <li>NumPy is also interoperable and can seamlessly and speedily integrate with a wide variety of databases.</li>
    <li>It is a key package in the field of machine learning, data analysis, and complex visualizations.</li>
    </li>
    </ul>
</ul>

## File Structure
```
.
├── Notes
    |── RohanC1.pdf
    ├── AdityaC1P1.pdf
    ├── AdityaC1P2.pdf
|── MiniProjects
    |── Aditya
        |── NatureOrientedGeneticAlgorithm
            |──code
               ├── main.py
               |──...
        |── Flappy Bird
            |──... 
    |── Rohan
        |── Genetic_Monkey_Shakespeare_Simulation
            |──...
        |── Snake Game
            |──...
|── README.md
├── CHESS_AI-PROJECT_REPORT.pdf
├── ChessAI
    ├── images
       ├── ...
    ├── AI.py
    ├── engine.py
    ├── main.py

.
``` 
## Getting Started
### Prerequisites
<ul>
    <li>Python 3</li>
    <li>Pygame</li>
    <li>Numpy</li>
</ul>


### Installation
<ol>
    <li>Clone the repository</li>
    <li>
    Select whether you want to play versus computer, against another player locally, or watch the game of two computers
    From the Appropriate flag in the main.py file
    <code>
    '''
    playerone = True
    playertwo = False
    Indicates that the player is playing against the computer
    True indicates that the player is a human player
    False indicates that the player is a computer player
    '''
    </code>
    </li>
            <li>Install pygame
                    <ul>
                        <li>On the Terminal, run:</li>
                    <code>pip install pygame</code>
                    <li>Pygame should get installed</ul>
                <li>Run main.py</li>
                <li><code>python main.py</code>
                <li>The Home Screen of the Game should appear on your screen</li>
            </ol>
        </ul>
</ol>

### Features
<ul>
    <li>Play against the computer</li>
    <li>Play against another player locally</li>
    <li>Watch the game of two computers</li>
    <li>Live Valid Move Checking</li>
    <li>Castling</li>
    <li>En Passant</li>
    <li>Promotion with its own menu</li>
    <li>Checkmate</li>
    <li>Stalemate</li>
    <li>Undo Moves</li>
    <li>Reset Game</li>
</ul>

### Usage
<ul>
    <li>Run main.py</li>
    <li>The Home Screen of the Game should appear on your screen</li>
    <li>Follow the message on the screen
    <ul><code>
    Press any key to start the game
    </code>
    </ul></li>
    <li>The Game Screen should appear on your screen</li>
    <li>Click a Chess piece to highlight it Valid Landing Squares</li>
    <li>Click a Valid Landing Square to move the Chess piece to that square</li>
    <li>Use<code>Ctrl + Z</code> Button to undo a move</li>
    <li>Use<code>Ctrl + R</code> Button to reset the game</li>
    <li>If Pawn Promotion occurs for the pawn of the human player, follow the instructions on the on-screen menu to do pawn promotion to your chosen piece</li>
    <li>Play the game until Checkmate or Stalemate occurs</li>

</ul>

## Theory And Approach

#### Negamax Algorithm
<strong><ins>Game Tree:</ins></strong> The algorithm starts by generating a game tree, which is a representation of all possible moves from the current position. Each node in the tree represents a possible game state, and each edge represents a move.

<strong><ins>Evaluation Function:</ins></strong> For each leaf node (end game state), the algorithm uses an evaluation function to assign a numerical value. This value represents the "goodness" of the game state for the AI. In chess, the evaluation function might consider factors like material balance, king safety, pawn structure, etc.

<strong><ins>Negation Principle:</ins></strong> The Negamax algorithm is based on the principle that the value of a position to a player is the negation of the value of that position to the other player. This simplifies the implementation of the algorithm, as it only needs to consider the perspective of the AI, not the opponent.

<strong><ins>Search:</ins></strong> The algorithm performs a depth-first search of the game tree. When it reaches a leaf node, it propagates the score back up to the parent node, negating the score at each level. This is based on the assumption that each player will choose the move that maximizes their minimum score (hence "minimax").

<strong><ins>The Best Move:</ins></strong> Once all scores are propagated, the AI chooses the move that leads to the highest score.

#### Alpha Beta Pruning
Alpha-beta pruning is an optimization technique for the Negmax algorithm. It reduces the number of nodes that need to be evaluated in the game tree by eliminating branches that don't need to be searched because they can't possibly influence the final decision.

Here's how it works in the context of the provided code:

<strong><ins>Alpha and Beta:</ins></strong> Alpha is the best value that the maximizer currently can guarantee at that level or above. Beta is the best value that the minimizer currently can guarantee at that level or above.

<strong><ins>Pruning:</ins></strong>: During the search, the algorithm keeps track of the best scoring option found so far. If it finds a move that scores higher than what the opponent could potentially achieve (<ins>beta</ins>), it stops evaluating the remaining moves (<ins>break</ins>), as the opponent would never allow this situation to occur.

<strong><ins>Updating Alpha:</ins></strong> If the score of the current move (<ins>maxScore</ins>) is greater than the current best (<ins>alpha</ins>), the best score is updated. This is because the maximizer has found a better move.

<strong><ins>Score Negation:</ins></strong> The score is negated when passed to the recursive call because the perspective changes from maximizer to minimizer or vice versa.

<strong><ins>Alpha Beta Inversion:</ins></strong> Alpha and beta values are inverted when passed to the recursive call because the roles of the maximizer and minimizer are swapped.

In summary, alpha-beta pruning allows the algorithm to ignore parts of the search tree that are irrelevant to the final decision, which can greatly improve efficiency in games with large search trees, like chess.

#### Pygame

1. **Initialization**: Pygame is first initialized using `pygame.init()`. This function initializes all the modules required for Pygame.
2. **Creating a Game Window**: Pygame creates a game window or screen using `pygame.display.set_mode()`. This is where all the game objects, animations, and text will be displayed.
3. **Game Loop**: Pygame runs a game loop where the game events are continuously checked and game objects are updated and drawn on the game window.
4. **Event Handling**: Pygame handles different types of events like keyboard input, mouse movement, button clicks, etc. These events are used to control the game characters or to trigger certain game actions.
5. **Drawing and Updating Game Objects**: Pygame provides functions to draw game objects on the game window. It also provides functions to update the game window so that the changes become visible.
6. **Sound and Music**: Pygame has modules to play sound effects and music. This adds to the overall game experience.
7. **Timing**: Pygame provides a way to track and control time. This is used to control the speed of game characters or to introduce delay in certain game actions.
8. **Collision Detection**: Pygame provides simple collision detection. This is used to detect when game characters or objects collide with each other.
9. **Game Over**: Pygame provides functions to end the game and quit the game window.


## Future Scope
<ul>
<li>
More Use of Genetic Algorithm in The AI part</li>
<li>Better tuning of Parameter weights</li>
<li>A database to store player information</li>
<li>More Game Modes</li>
</ul>

## Acknowledgements
Project Mentor <a href="https://github.com/siddheshsingh26">Siddeshsingh Tanwar</a> for
his support and guidance throughout the duration of the project.

<a href="https://github.com/CommunityOfCoders">Community of Coders(COC)</a>
for providing us with the opportunity to work on this project.

## Contributors
<ul>
    <a href="https://github.com/Aditya-y9" ><li>Aditya Yedurkar</li> </a>
    <a href="https://github.com/Rohan20-10" ><li>Rohan Parab</li> </a>











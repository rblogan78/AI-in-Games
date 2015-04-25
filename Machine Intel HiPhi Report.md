COMP3330 - Machine Intelligence - HiPhi Report
==============================================

# Abstract #

The evolution of artificial intelligence(AI) in gaming has its origins in the earliest conversions of popular board games from physical to digital formats. From the early 1950’s when Claude Shannon designed AI for the first Chess games and Arthur Samuel created a self-playing, learning checkers program, the development and refining of intelligent agents or non-player characters(NPCs) has woven itself into the fabric of game development. This presentation will cover how AI in gaming has evolved over the past decades from basic finite state machines, path finding, and information processing when given incomplete information, as well as the innovative steps and advancements in machine learning techniques to design the AI we see today in lifelike characters with behavioural traits, and the possibilities for the future.

# Introduction #

Video Games form a rapidly growing industry moving towards an artistic form that both programmers and players can appreciate ([Wexler, 2002](http://www.cs.rochester.edu/~brown/242/assts/termprojs/games.pdf)). The term "Game AI" encompasses programming and design practices, including path-finding algorithms, neural-networks, models of interaction, state machines, and decision trees, all with the common goal of providing some intelligent behaviour ([Mateas, 2003](http://lmc.gatech.edu/~mateas/publications/MateasDIGRA2003.pdf)). Game AI aims to establish the belief in a living entity within the computer that can act independently of the player.

# Relevance to Machine Intelligence #

* The computer science department at UC Berkeley has developed an implementation of Pac-Man using Python to illustrate basic Artificial Intelligence concepts, such as state-space searching, probabilistic inferencing, and reinforcement learning. ([Berkeley, n.d.](http://ai.berkeley.edu/project_overview.html))

# Key Historical Facts Timeline #

Game AI shares its foundations with the rise of digital processing. Claude Shannon and Alan Turing started developing chess programs as early as 1950. Board games were the popular choice for experimenting with Artificial Intelligence due to their nature of perfect information - the entire state of the game can be captured by the computer. They are typically non-trivial search problems with no well-defined path to a given solution as the involvement of an opponent introduces a degree of uncertainty ([Middleton, 2002](http://web.stanford.edu/group/htgg/sts145papers/zmiddleton_2002_1.pdf)).

During the early years of video games, AI was not a feature due to the simplicity of the games produced, and human centred design.

## 1940 ##
* In 1949, Claude Shannon published the paper *Programming a Computer for Playing Chess* in which he describes how a machine can decide how to move such that it can minimise the possible loss in the worst case scenario ([Shannon, 1949](http://www.pi.infn.it/~carosi/chess/shannon.txt)). His reasons for using chess as the basis for his paper include:
    * The legal move-set and the end goal is well defined
    * It is neither a trivial problem, nor too difficult to calculate a viable solution
    * There is a element of skilful thinking involved
    * The discrete structure of chess fits well into the design of computers 

## 1950 ##
* A computerised version of Nim was published in 1952, and was able to consistently win games against players 95% of the time ([The New Yorker, 1952](http://www.newyorker.com/magazine/1952/08/02/it))

## 1960 ##
## 1970 ##

* Atari release Pong in 1972, a table tennis simulator that could be played between two people, but ore importantly, with a computer controller opponent. The core intelligence was established using discrete logic, and hence was "hardcoded" into the game.

> If the Al player simply stopped tracking the ball every eight frames [due to a skip in
> adjusting its vertical position every eight frames], it would be hopelessly 
> out of sync within a few seconds. To prevent this, the Al follows a secondary ball-tracking 
> plan near the top and bottom of the playfield. If the ball collides with one of these walls 
> when the paddle is also aligned with it, the paddle readjusts, recovering from any drift that 
> had accumulated since the ball last struck the wall. The result is a stochastic misalignment 
> and realignment of computer paddle and ball

(Monfort, Bogost, 2009)

* Space Invaders (1978) introduced a new form of intelligence through stored patterns.

## 1980 ##

* Pac-Man, released in 1980, introduced AI patterns in maze environments, with individual personalities assigned to each enemy. 

## 1990 ##

* Dragon Quest, a role playing game developed by Chunsoft for the NES in 1990, introduced an element of Artificial Intelligence through its "tactics" system. This allowed players to provide battle strategies to their party members such as healing, attacking, etc. ([Reeves, 2011](http://www.gameinformer.com/b/features/archive/2011/02/14/a-warrior-s-quest-a-retrospective-of-square-enix-s-classic-rpg-series.aspx)). Later instalments of the Dragon Quest series allowed tactics to be set for individual team members, rather than party wide.
* Real Time Strategy (RTS) games emerged
* Creatures, Artificial Life

## 2000 ##

* The Sims, a life simulation game, is released.
* TrueSkill, a Bayesian skill rating system developed by Microsoft, is launched for xbox in 2005. It estimates the skill level of the player based on their average perceived skill value, and the degree of uncertainty the system has in the player's skill ([Microsoft, n.d.](http://research.microsoft.com/en-us/projects/trueskill/)). It is still used in matchmaking games today
* Colin McRae Rally 2 (2001) - Makes use of neural networks to train competing drivers 
    * Racing Line
    * Path Finding

## 2010 ##

# Applications in Research #

The primary goal of Game AI is to entertain. As such, developers tend to avoid using true "academic" AI, opting for short-cuts and efficiency, whilst maintaining some level of intelligence in the system.

# Bibliography

1. http://www.cs.rochester.edu/~brown/242/assts/termprojs/games.pdf
2. http://www.newyorker.com/magazine/1952/08/02/it
3. http://lmc.gatech.edu/~mateas/publications/MateasDIGRA2003.pdf
4. http://web.stanford.edu/group/htgg/sts145papers/zmiddleton_2002_1.pdf
5. http://books.google.co.uk/books?id=DqePfdz_x6gC&lpg=PP1&dq=racing+the+beam&pg=PA40&hl=en#v=onepage&f=false
6. http://www.gameinformer.com/b/features/archive/2011/02/14/a-warrior-s-quest-a-retrospective-of-square-enix-s-classic-rpg-series.aspx
7. http://research.microsoft.com/en-us/projects/ijcaiigames/
8. http://www.ai-junkie.com/misc/hannan/hannan.html
9. https://sites.google.com/site/myangelcafe/articles/history_ai
10. http://www.pi.infn.it/~carosi/chess/shannon.txt
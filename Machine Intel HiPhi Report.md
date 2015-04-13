COMP3330 - Machine Intelligence - HiPhi Report
==============================================

# Abstract #

The evolution of artificial intelligence(AI) in gaming has its origins in the earliest conversions of popular board games from physical to digital formats. From the early 1950’s when Claude and Shannon designed AI for the first Chess games and Arthur Samuel created a self-playing, learning checkers program, the development and refining of intelligent agents or non-player characters(NPCs) has woven itself into the fabric of game development. This presentation will cover how AI in gaming has evolved over the past decades from basic finite state machines, path finding, and information processing when given incomplete information, as well as the innovative steps and advancements in machine learning techniques to design the AI we see today in lifelike characters with behavioural traits, and the possibilities for the future.

# Introduction #

Video Games form a rapidly growing industry moving towards an artistic form that both programmers and players can appreciate ([Wexler, 2002](http://www.cs.rochester.edu/~brown/242/assts/termprojs/games.pdf)). The term "Game AI" encompasses programming and design practices, including path-finding algorithms, neural-networks, models of interaction, state machines, and decision trees, all with the common goal of providing some intelligent behaviour ([Mateas, 2003](http://lmc.gatech.edu/~mateas/publications/MateasDIGRA2003.pdf)). Game AI aims to establish the belief in a living entity within the computer that can act independently of the player.

# Relevance to Machine Intelligence #

* The computer science department at UC Berkeley has developed an implementation of Pac-Man using Python to illustrate basic Artificial Intelligence concepts, such as state-space searching, probabilistic inferencing, and reinforcement learning. ([Berkeley, n.d.](http://ai.berkeley.edu/project_overview.html))

# Key Historical Facts Timeline #

Game AI shares its foundations with the rise of digital processing. Claude Shannon and Alan Turing started developing chess programs as early as 1950. Board games were the popular choice for experimenting with Artificial Intelligence due to their nature of perfect information - the entire state of the game can be captured by the computer. They are typically non-trivial search problems with no well-defined path to a given solution as the involvement of an opponent introduces a degree of uncertainty ([Middleton, 2002](http://web.stanford.edu/group/htgg/sts145papers/zmiddleton_2002_1.pdf)).

During the early years of video games, AI was not a feature due to the simplicity of the games produced, and human centred design.

## 1950 ##

* A computerised version of Nim was published in 1952, and was able to consistently win games against players 95% of the time ([The New Yorker, 1952](http://www.newyorker.com/magazine/1952/08/02/it))

## 1960 ##
## 1970 ##

* Atari release Pong in 1972, a table tennis simulator that could be played between two people, but ore importantly, with a computer controller opponent. The core intelligence was established using discrete logic

> If the Al player simply stopped tracking the ball every eight frames [due to a skip in
> adjusting its vertical position every eight frames], it would be hopelessly 
> out of sync within a few seconds. To prevent this, the Al follows a secondary ball-tracking 
> plan near the top and bottom of the playfield. If the ball collides with one of these walls 
> when the paddle is also aligned with it, the paddle readjusts, recovering from any drift that 
> had accumulated since the ball last struck the wall. The result is a stochastic misalignment 
> and realignment of computer paddle and ball

(Monfort, Bogost, 2009)

## 1980 ##

* Pac-Man, released in 1980, introduced AI patterns in maze environments, with individual personalities assigned to each enemy. 

## 1990 ##

Dragon Quest, a role playing game developed by Chunsoft for the NES in 1990, introduced an element of Artificial Intelligence through its "tactics" system. This allowed players to provide battle strategies to their party members such as healing, attacking, etc. ([Reeves, 2011](http://www.gameinformer.com/b/features/archive/2011/02/14/a-warrior-s-quest-a-retrospective-of-square-enix-s-classic-rpg-series.aspx)). Later instalments of the Dragon Quest series allowed tactics to be set for individual team members, rather than party wide.

## 2000 ##
## 2010 ##

# Applications in Research #

# Bibliography

1. http://www.cs.rochester.edu/~brown/242/assts/termprojs/games.pdf
2. http://www.newyorker.com/magazine/1952/08/02/it
3. http://lmc.gatech.edu/~mateas/publications/MateasDIGRA2003.pdf
4. http://web.stanford.edu/group/htgg/sts145papers/zmiddleton_2002_1.pdf
5. http://books.google.co.uk/books?id=DqePfdz_x6gC&lpg=PP1&dq=racing+the+beam&pg=PA40&hl=en#v=onepage&f=false
6. http://www.gameinformer.com/b/features/archive/2011/02/14/a-warrior-s-quest-a-retrospective-of-square-enix-s-classic-rpg-series.aspx
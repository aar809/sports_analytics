# NUS MComp Capstone Project 2022
## Sports Strategy Analytics using Player Clustering & Probabilistic Model Checking

Prepared by: Aaron L H Chan <br>
Advised by: Professor Jin-Song Dong <br>
December 2022 <br>

### Abstract
Tennis has consistently been ranked as one of the world’s most popular sports, but efforts to push the sport into the new age of advanced data analytics have seemingly lagged far behind other popular sports, such as basketball, football, and baseball. Although many recent works have pushed the envelope in the right direction, lack of data availability for lower-tiered tennis players remains a major roadblock for generating accurate match outcome predictions. Building on top of previous research work done by Dong et al., our goal is to take the existing concepts of probabilistic communicating sequential processes (PCSP) and the process analysis toolkit (PAT) model checker, and expand its usage to lower-tiered tennis players through a concept we call data generalization by clustering. To test the effectiveness of our approach, we first cluster players based on play style using three distinct game components: service game, return game, and rally game. Next, we employ a 3-step iterative experimental process to select the most optimal feature sets and machine learning algorithms to use for player clustering. Lastly, we evaluate the cluster results using metrics such as intra-inter cluster distance, evaluation against a controlled feature set, and finally, player-cluster data replacement in the original PCSP model to determine how accurately our clustered representation resembles the players themselves.

<img width="450" alt="image" src="https://user-images.githubusercontent.com/19891445/205842000-ddaca1fb-db7d-4168-a011-afbdf5826e2b.png"> 

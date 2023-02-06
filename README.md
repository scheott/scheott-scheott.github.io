# Kelly Criterion Betting Game
## Introduction
The Kelly Criterion is a formula that determines the theoretical optimal betting size. I first heard about this number when I was researchihng the statistics of gambling and immediately was interested. As you can see below the Kelly Criterion maximizes the growth rate based on ((P(Success) * (Decimal Odds - 1)) - P(Failure)) / (Decimal Odds - 1)

![alt text](https://github.com/scheott/scheott.github.io/blob/main/Kelly_bet.png "Kelly Criterian Math")

My motivation behind this game was to visualize the Kelly Criterian and be able to see over time how well this method workds.

## The Game
The game I made in html, allows you to choose bwtween Aaron Rodgers, Patrick Mahomes, and Tom Brady. They each have there respective average yards per game and you can either guess over or under. The computer will randomly generate a number between 200 and 400. I picked those numbers so it's easier to visualize when the chance of winning is > 50%. You can choose how much you want to bet of your starting $500 bankroll, the computer will always choose the Kelly Criterion. After each bet there is a line graph that will update as your bankroll and the computers bankroll changes.

You can play the game here
[I'm an inline-style link with title](https://scheott.github.io/ "here")

## Findings
Overall this game was a success, it allowed me to see the impact that this number has and it's also pretty fun to play. Below you can see how well this formula works
![alt text](https://github.com/scheott/scheott.github.io/blob/main/Kelly.png)

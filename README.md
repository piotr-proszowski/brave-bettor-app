# Brave Bettor

## Context

Sport betting is a fascinating activity. There is a sport event which will end with some result. 
People guess the what will be the outcome and depends on it they win or loose money. I don't know single person that would have plus balance.

There are also betting platforms like [STS](https://sts.pl) or [Efortuna](https://efortuna.pl) that offer sport bets. They are real winners of sport betting - they win no matter of outcome. In other words - they drink the juice.

So how is it possible? 

Let's imagine that Real Madrid plays against Barcelona next week. Bookmaker takes all the data he gathered about this sport event and some crazy algortihms (or some smart guys) come to conclusion what odds are for some facts. Then this knowledge is published in form of initial bet offer, which can be presented like that:

`Real Madrid 2.20` | `X 1.86` | `Barcelona 2.68`

So it seems that if bettor bets 1000$ on Barceona and it will be the real outcome bookmaker looses more than 1000$. However, there is a huge chance that there will be more bettors than only one, right? Bookmaker knows it so when there is too much people is betting on Barcelona he will adjust bet offer to encourage other bettors for betting to second option.

`Real Madrid 2.80` | `X 1.86` | `Barcelona 1.92`

Those adjustments happen all the time:
- when some news go out (i.e about player injury) 
- when there is too much bettors on one site

So when bookmaker has similar amount of money put on each option he just... drinks the juice :) From each win he takes 12%, so in this case he takes all the money from two options and pay it to bettors who won.

So bookmakers leverage the fact that there is a lot of bettors.
Can bettor leverage the fact that there is more than one bookmaker?
In theory - yes. There is a term called Arbitrage/Sure Bets.

Resources on that matter:
- [How I made €2,000 in ONE month using mathematical sure bets](https://www.youtube.com/watch?v=fnpQWrZMg9I)
- [Arbitrage betting](https://en.wikipedia.org/wiki/Arbitrage_betting)
- [The Ultimate Guide To Sure Betting Sports Arbitrage](https://www.rebelbetting.com/the-ultimate-guide-to-sure-betting-sports-arbitrage)

## Goal

Brave bettor is a system that periodically scans bet offers from various bookmakers, looks for profit opportunities (like arbitrage bets) and automatically places bets.

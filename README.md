# Roulette-Betting-System
This system is pretty simple.

You bet the column (12 winning numbers) which pays out 3 to 1.

If you win you go back to the mininum.

If you lose you double your previous bet.

So for example:
Bet 5 (min), lose
Bet 10, lose
bet 20, lose
bet 40, lose
bet 80, lose
bet 160, win.

Winning: +480 = 160 * 3
Losses:  -315  = 5 + 10 + 20  + 40 + 80 + 160
Total: +165

I must have messed up because I am getting postive returns....which has to be impossible.

Below are my results for 10,000 simulations. For some reaosn Python doesn't let me use a recusive function more than 1000 so I manually stop it after 950 "spins".

starting bal: 10000
minbet: 5
maxbet: 1000

Max Profit: 57415
Max Spin: 966
Max Bet: 3990
Min Ending Balance: -10000
Min Spin: 951
Min MaxBet: 2000
Mean Return: 22112.9245
Mean Spin: 966
Mean MaxBet: 3990


I figure we an expand on the this betting model. I would like to use this to create charts and pull as much information as we can get. I would also like to use numpy as much as possible.

Another note is that this takes forever to run. Need to make it much more effecitent as I would like to run this simulation 500k times.

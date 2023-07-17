# sim03
#### Utility to test the move similarity of any two UCI chess engines (by Don Dailey) 

"It does this by running 2000 positions from random games and noting how often the moves agree and as output returns the percentage of moves that match."

https://komodochess.com/downloads.htm

https://komodochess.com/pub/sim03_win.zip

#### Results

This is a simple test w/ default settings.  Results should be easy to replicate. Basic questions are: which engine (or engines) is engineX most similar to? Out of 2000 positions, how often (what percentage?) do the two engines agree on best move?

|                       |
| --------------------- |
|[Berserk-4.6.0.md](reports/Berserk-4.6.0.md)|
|[Clover-3.1.md](reports/Clover-3.1.md)|
|[Eman-7.00.md](reports/Eman-7.00.md)|
|[Ethereal-10.55.md](reports/Ethereal-10.55.md)|
|[Ethereal-11.50.md](reports/Ethereal-11.50.md)|
|[Ethereal-12.75.md](reports/Ethereal-12.75.md)|
|[Ethereal-13.07.md](reports/Ethereal-13.07.md)|
|[Fat-Fritz-(in-Lc0).md](reports/Fat-Fritz-(in-Lc0).md)| 
|[Fire-8.2.md](reports/Fire-8.2.md)|
|[Fire-8.nn.md](reports/Fire-8.nn.md)|
|[Fire-zero.md](reports/Fire-zero.md)|
|[Igel-3.0.5.md](reports/Igel-3.0.5.md)|
|[Koivisto-6.0.md](reports/Koivisto-6.0.md)|
|[Komodo-13.02.md](reports/Komodo-13.02.md)|
|[Lc0-V0.28.0.md](reports/Lc0-V0.28.0.md)|
|[Mayhem-6.3.md](reports/Mayhem-6.3.md)|
|[Minic-3.22.md](reports/Minic-3.22.md)|
|[Nemorino-6.00.md](reports/Nemorino-6.00.md)|
|[Rebel-15.md](reports/Rebel-15.md)|
|[rofChade-3.0.md](reports/rofChade-3.0.md)|
|[RubiChess-2.2.md](reports/RubiChess-2.2.md)|
|[Seer-2.5.0.md](reports/Seer-2.5.0.md)|
|[ShashChess-20.1.md](reports/ShashChess-20.1.md)|
|[SlowChess-2.9.md](reports/SlowChess-2.9.md)|
|[Stockfish-8.md](reports/Stockfish-8.md)|
|[Stockfish-9.md](reports/Stockfish-9.md)|
|[Stockfish-10.md](reports/Stockfish-10.md)|
|[Stockfish-11.md](reports/Stockfish-11.md)|
|[Stockfish-12.md](reports/Stockfish-12.md)|
|[Stockfish-13.md](reports/Stockfish-13.md)|
|[Stockfish-14.md](reports/Stockfish-14.md)|
|[Stockfish-15.md](reports/Stockfish-15.md)|
|[SugaR-1.6.md](reports/SugaR-1.6.md)|
|[Tucano-8.00.md](reports/Tucano-8.00.md)|
|[Uralochka-3.37c.md](reports/Uralochka-3.37c.md)|
|[Wasp-5.00.md](reports/Wasp-5.00.md)|


#### Results (sorted by most similar pairs...click on link above for more detail):

|                       |            |                       |
| --------------------- | ---------- | --------------------- |
|Stockfish-14.1|64.70%|ShashChess-20.1|
|ShashChess-20.1|64.70%|Stockfish-14.1|
|Stockfish-15|64.31%|Stockfish-14.1|
|Stockfish-13|63.91%|Eman-7.00|
|Eman-7.00|63.91%|Stockfish-13|
|Stockfish-10|62.96%|SugaR-1.6|
|SugaR-1.6|62.96%|Stockfish-10|
|Stockfish-9|60.55%|Stockfish-10|
|Stockfish-11|60.39%|Stockfish-10|
|Stockfish-12|59.97%|Stockfish-13|
|Stockfish-8|59.55%|Stockfish-9|
|Nemorino-6.00|56.60%|Stockfish-12|
|Seer-2.5.0|56.42%|Koivisto-6.0|
|rofChade-3.0|56.39%|Stockfish-13|
|Fat-Fritz-(in-lc0)|55.66%|Lc0-v0.28.0|
|Lc0-v0.28.0|55.66%|Fat-Fritz-(in-lc0)|
|Clover-3.1|55.61%|Koivisto-6.0|
|Koivisto-6.0|54.30%|Stockfish-13|
|Berserk-4.6.0|53.68%|SugaR-1.6|
|Rebel-15|53.57%|Koivisto-6.0|
|RubiChess-2.2|53.12%|Eman-7.00|
|Wasp-5.00|52.76%|Koivisto-6.0|
|Ethereal-13.07|52.90%|Stockfish-10|
|Uralochka-3.37c|52.88%|Seer-2.5.0|
|Ethereal-11.50|52.61%|Berserk-4.6.0|
|Igel-3.0.5|52.20%|Stockfish-13|
|Ethereal-10.55|52.05%|Stockfish-8|
|Ethereal-12.75|51.65%|SugaR-1.6-64|
|Minic-3.22|51.60%|Seer-2.5.0|
|Komodo-13.02|51.18%|Stockfish-9|
|Fire-8.2|45.01%|Stockfish-8|
|SlowChess-Blitz-2.9|44.72%|Lc0-v0.28.0|
|Fire-8.NN|43.34%|Stockfish-12|
|Tucano-8.00|32.34%|SlowChess-Blitz-2.9|
|Fire-zero|31.88%|Lc0-v0.28.0|
|Mayhem-6.3|30.84%|Fat-Fritz-(in-lc0)|

#### Full matrix:

 ![alt tag](https://raw.githubusercontent.com/FireFather/sim03/master/matrix.png)

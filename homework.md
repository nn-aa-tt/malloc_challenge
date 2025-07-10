# malloc challenge
## best_fitの実装
要求されているメモリの大きさより大きい空き領域のうち、最も小さいものを選ぶ。   
十分な空き容量のうち最初に見つけたものを選ぶfirst_firよりメモリを無駄なく使える。
|challenge| challenge1 | challenge2 | challenge3 | challenge4 | challenge5 |  
|---|---|---|---|---|---|
|first_fir|7ms<br>70%|9ms<br>40%|106ms<br>7%|13415ms<br>15%|9942ms<br>15%|
|best_fir|878ms<br>70%|6141ms<br>40%|749ms<br>51%|5873ms<br>72%|3405ms<br>75%|

## free_list_binの実装
空き容量が2048以下のものと2048より大きいもので分類して、空き容量の探索の時間短縮を図った。


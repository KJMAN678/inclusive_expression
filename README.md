# serial_suite_number
python の for 文の内包表現と、フォーマット済み文字列を組み合わせてトランプのカード（スート＋数字）を簡潔な記述で作るテクニックです。  

cards = [f"{suit}{num}" for suit in ("♠", "♡", "♢", "♣") for num in range(1, 14)]  

これで♠1～13、♡1～13、♢1～13、♣1～13の配列を作成することができます。  

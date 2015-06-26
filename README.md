# chess

This is the classical game of chess built in ruby to be played in console. It uses multiple levels of inheritance to keep the pieces' move logic DRY. Pieces check validity of move & possible moves through try/catch that removes all disallowed moves. Checkmate also implemented through similar conditionals, which was made DRY by using existing methods targetted at each player's king. 

# chessai
This is a chess bot.
This bot can play against you, play on it's own, and also play against the stockfish engine if it's properly installed in your system and the path to the engine is correctly configured in the code where it says path_to\stockfish.exe
in the bottom part of the code you'll see the notes...
# man vs engine
# self battle
# engine vs stockfish
In this code currently the man vs engine part is the working code, by running the code you can play against it.
If you want the engine to do a self battle then you should make the man vs engine part the comment and then uncomment the self battle part's code.
Similarly, do it for the engine vs stockish code to work.
Also you can modify the value of the depth variable which can be given values from 1 to 4 (But do remember that by increasing the value the engine will take more time to respond to the move made. The recommended vale of depth is 2 or 3).
This bot doesn't have a gui, it's a uci/terminal based engine.
You can modify the code to have a gui either by using pyqt5 library or automate it using pyautogui by using some third party apps chess board.

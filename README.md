In this project, I helped write the program to display and play the battleship game on the NUC140 board. A simple 5x5 map would be created using Notepad with different icons ("-" for water/empty spots or "x" for ships) representing the ship and the empty spot. The program which is around 700 lines long was written together by me and my two teammates, I helped writing the games hit or miss logic and with the coordinate selection logic while my teammates will do other parts like welcome screen or end game logics while doing program checks. The game's program will be written using Keil uVision which can be used to load the program into the NUC140 board via USB connection. The game's map created using Notepad can be loaded into the board when the game is started using a separate UART module and using terminal.exe software.

The game starts with a welcome screen and allows the user to load the map to start the game, select coordinates using the onboard buttons on the side, a separate button to shoot and an two 7-LED segments to display the numeric x-y coordinates and number of remaining shots. The game will end if the user has managed to destroy all 5 ships (by hitting all ship icon coordinates) or run out of shots.



UART module used to load the map from the PC and trasmit to the NUC140 board
![battleship1](https://github.com/CongMinh0805/FinalLabBattleShip/blob/main/Images/battleship2.jpg)



Hardware connection using NUC140 board and UART module:
![battleship1](https://github.com/CongMinh0805/FinalLabBattleShip/blob/main/Images/battleship1.jpg)

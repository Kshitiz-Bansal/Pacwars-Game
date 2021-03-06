# PAC-WARS

PAC-WARS is a combination of two classic games- PACMAN and STAR-WARS. It is an online (can be played on the same network) multiplayer game (supports upto 10 players). It crosses the eating each other functionality of pacman with the shooting each other functionality of star-wars.

<p align="center">
  <img src="first-window.png" width="600"/><br>
  Game main menu
</p>


<p align="center">
  <img src="gameplay.png" width="600"/><br>
  Gameplay
</p>

____

# Installing dependencies:
### Ubuntu:
1) SDL2  
    use ```sudo apt install libsdl2-dev libsdl2-2.0-0 -y```

2) SDL mixer (For audio) (Not included in SDL2)  
    use ```sudo apt install libsdl2-mixer-2.0-0```

3) SDL image (For displaying images) (Not included in SDL2)  
    use ```sudo apt install libsdl2-image-dev```

(* one might have to install SDL_ttf separately too.)

### Windows:  
Why are you still using it?  

### Other OSs:
Kindly google ```install sdl [OS]``` and ```install sdl [image/mixer/ttf] [OS]```   

# How to run:  
1) Compile  
    use ```make```  

2) Run  
    use ```./game [player_name]```  
    player_name is an optional argument. Game window is named using it.

# References:
1) For almost all doubts:  
https://lazyfoo.net/tutorials/SDL/index.php

2) For networking:
    1) https://github.com/maciejspychala/sdl-game
    2) https://www.youtube.com/watch?v=IydkqseK6oQ
    3) https://www.tutorialspoint.com/difference-between-tcp-and-udp
    4) http://www.steves-internet-guide.com/tcp-vs-udp/

3) For maze creation:  
    1) https://en.wikipedia.org/wiki/User:Dllu/Maze
    2) Introduction to Algorithms, CLRS


____ 

Course Project | Design Practices | Prof. Rijurekha Sen

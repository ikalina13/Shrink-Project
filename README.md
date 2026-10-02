_____ _   _ ______ _  __ _  __
  / ____| \ | |  ____| |/ /| |/ /
 | (___ |  \| | |__  | ' / | ' / 
  \___ \| . ` |  __| |  <  |  <  
  ____) | |\  | |____| . \ | . \ 
 |_____/|_| \_|______|_|\_\|_|\_\

SNEKK is a small Snake game with a twist. Your goal is to eat the apple before the 5-second timer runs out. If you don't manage to eat it in time, the grid gets smaller, making the game harder as you continue playing.

● How I Made It

At first, I tried making SNEKK using regular coding like I normally would. The game worked, but when I converted the HTML into a URI, it went over the KB limit.

Because of that, I had to get creative with how I wrote the code.

I made multiple versions of the script, and each version was smaller and better than the previous one. Instead of completely changing how the game worked, I focused on reducing the amount of unnecessary characters in the code.

Some of the main things I did were:

● Removed unnecessary whitespaces
● Removed comments
● Shortened long variable names
● Used single letters for some variables
● Removed unnecessary code
● Combined lines and statements where possible
●Kept the actual game mechanics the same

● Mechanics of my game

● W,A,S,D " on my first script it was arrowkeys but i changed it bc my arrowkeys are small"
● Timer for every 5 seconds
● Apple collision
● Beep Audio
● Restart button
● Snekk player



The hardest part wasn't really making the Snake game itself. It was getting the game small enough to fit the URI KB limit while still keeping everything working.

In the end, SNEKK became a good challenge in both coding and code optimization.






           /^\/^\
         _|__|  O|
\/     /~     \_/ \
 \____|__________/  \
        \_______      \
                `\     \                 \                                        
                  |     |                  \
                 /      /                    \
                /     /                       \\
              /      /                         \ \
             /     /                            \  \
           /     /             _----_            \   \
          /     /           _-~      ~-_         |   |
         (      (        _-~    _--_    ~-_     _/   |
          \      ~-____-~    _-~    ~-_    ~-_-~    /
            ~-_           _-~          ~-_       _-~
               ~--______-~                ~-___-~


# Bartenter

![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FPho3nyxX%2Fbartender&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=Page+Views&edge_flat=false)

A simulation a classic bar interaction between students and a bartender. Students take from a barrel of beer until that store is empty. Once the store is empty, the bartender is awoken to refill the beer barrel. There are certain restrictions. The barrel can hold up to fifty beers; after taking beer, students drink and think for a random amount of time before going back for more beer; the bartender will awake only three times.

This simulation can only be effectively and efficiently executed using a multithreaded approach. Where multiple student threads run the student functions while a single thread plays the bartender role.

---

## The commands to run the simulation are listed below:

1. Open a terminal window
2. “cd” to the project directory
3. Build command: g++ -pthread Project.cpp –o Project
4. Run command: ./Project
5. Pause command: Enter
6. Resume command: Enter
7. Exit command: Ctrl+c 

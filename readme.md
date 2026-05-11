# Reincarnation Tale
This is an OOD project with a custom game engine realised with SDL2 and C++.

Dependencies: GCC,SDL2, SDL2_image, SDL2_ttf and CMake

Cmake and G++ is tested for arch linux (6.14.2) , should work on all distros. 

Didn't bother with windows equivalent cause it's not like anyone will play this anyways
```
git clone https://github.com/ninelcatel/Reincarnation-Tale.git
```

```
cd Reincarnation-Tale
```

```
mkdir build && cd build
```

```
cmake ..
```

```
make
```

```
./Game
```
Or if you don't want to use cmake:

```
g++ main.cpp src/room.cpp src/assets.cpp src/enemy.cpp src/gamemanager.cpp src/entity.cpp src/init.cpp src/player.cpp -o main -lSDL2 -lSDL2_image -lSDL2_ttf && ./main
``` 

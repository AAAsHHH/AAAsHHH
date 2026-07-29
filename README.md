# QMars R2

A 2D pixel-art sandbox game built with **C++** and **raylib**, compiled to WebAssembly with Emscripten.
░▒▒▒▒▒░▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▓▓█████████████████▓▓▒▒▒   ▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▓█▓▓▒▒▒▒░░░░░░░░
░▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▓▓▓▓██████████████▓▒▒▒▒▒▒    ▒▒▒▒▒▓█████▓▓▓▓██▓▓▓▒▒▒░░░░░░░░
▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▓▓▓▓██████▓▓▓▓▒▒▒▒▒▒▒░   ░▒▒▒▓█▓▒▒▒▒▒▒▒▒▓▓▓▓▓▒▒░░░░░░░░░
▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▓▓▓▓▓▓▒▓▒▓▒▒▒▒▒▒▒▒░    ▒▒▓▓▒▒▒▒▒▒▒▒▒▒▒▒▒▒░░░░░░░░░░░░
▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒     ░▓▓▓▒▒▒▒▒▒░░░░░░░░░░░░░░░░░░░░
▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒░      ▒▒▒▒▒▒▒░░░░░░░░░░░░░░░░░░░░░░
▒▒▒▒▒▒▒▒▒▒▓▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▓▓▒ ░     ░▒▒░░░░░░░░░░░░░░░░░░░░░░░░░░
▒▒▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▓▓▓▒▒▒▒▒▓▒▓ ░░     ░▒░▒░░░░░░░░░░░░░░░░░░░░░░░░░
▓▓▓▓███████▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▒▒▒▒▒▒▒░░░░▒▒▒▒▒▒░ ░░      ░░░░░░░░░░░░░░░░░░░░░░░░░░░░
▓▓▓▓▓██▓█████████████▓▓▓▓▓▓▓▓▓▓▓▒▒▒▒░ ░░░▒▒▒ ▒░     ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
▓▓▓▓▓▓▓▓▓▓█▓█████████████████▓▓▓▓▓▒░ ░  ░░░░▒░       ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
███████████▓▓████████████████████▓▓▓░░   ░▒▒        ▒▒▒░░░░░░░░░░░░░░░░░░░░░░░░░░░
█████████████████████████████████▓▓▓▒░ ░░░         ░▒▒▒▒▒░░░░░░░░░░░░░░░░░░░░░░░░░
██████████████████████████████████▓▓▓▒▒░░░        ░▒▒▒▒▒▒▒▒░░░░░░░░░░░░░░░░░░░░░░░
█████████████████████████████████████▒░░░         ▒▒▒▒▒▒▒▒▒▒▒▒░░░▒▒▒░░░░░░░░░░░░░░
███████████████████████████████████▒▒░░░       ░ ░▒▒▒▒▒▒▒▒▒▒░░░░░░░░░▒░░░░░░░░░░░░
███████████████████████████████████▓░░  ░     ░░▒▒▒▒▒▒▒▒▒▒▒▒▒░▒░░░░░░░░░░░░░░░░░░░
███████████████████▓██████████████▓░░░░░     ░▓▒▓▓▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒░░▒░░░░░░░░░░░
██████████████████████████████████▓░░░░      ░█▓▓▓▓▓▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒
███████████████████████████████████░ ░        ░██▓▓▓▓▓▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒
██████████████████▒▒███░▒████████▒▒  ░          ░  ▓▓▓▓▓▓▓▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒
██████████████████░ ▒██░░▒▒▓▓▒░ ░░░                 ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▒▒▓▓▓▓▓▓▓
█████████████████▓▒▒░░░░░░▒▒▒▒▓▓████▒▒░         ░░  ░▓▒█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓░▒▓▓▓▓▓▓▓
▓▓▓▓▓█████████████▓▒      ▒▓█▓▓▓▓████▓░                ░▒▓▓▒▓▓▒▓▓▓▓▓▓▓▓░░░▓▓▓▓▓▓▓▓
▓▓▓▓▒▒▒▓▓███████████░   ░▓▓█▓▓▓▓▓▓▓▓▒      ▒▒██▓░     ░▒ ▒▒▒▒▒▒▒▒▒▒░▒░░ ░░▒▒▒▒▒▒▒▒
▓▓▓█▒░▒▒▒▒▒▒▒▓▓████▓█░   ░░▒▓█████▓▓░░  ░▒▒▒▒█████▒░    ▒░▒▒▒▒▒▒▒░░░░░░ ░░░░░░░░░░
▒▒▒▒▒░░▒▒▒▒▒▒▒▓▓▓▓▓▓▓    ░▓▓█▓▓▓▒▒▒▒▒░  ░░░▒▒▒▒▒▒▒▒░    ░░▒░▒▒░░░░░ ░ ░ ░░░░░░░░ ░
░░░░▒░░░▒▒░░▒▒▒░░▒▒▓▓░░▒  ▒▓▓▓▒▒▒▒▒░░▒░░░░░░░░░░░░░░    ░░░ ░░░  ░░░  ░░  ░ ░    ░
░░░░░░░░░░░░░░░░░░░▒▒▒▒▓▒ ░▒░▒░░░░░░░▒▒░░░░░░░░░░░░░░░░ ░░░        ░░░░░░░░░░     
░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ ░░░░░░░░░░░░░░░░ ░░░░░░░░░░░░░░░░░░ ░░ ░░ ░░░   ░  ░
░░░ ░ ░░░░░░░░░░░ ░░░░░ ░ ░░░░░░░░░░░░░░░░░░░░░░░░░░░ ░░░ ░░░ ░░░░░░░   ░░ ░░░    
░  ░░░         ░░░░░ ░   ░░░░  ░  ░░ ░░░▒░░░░░░░░░░░    ░ ░  ░   ░   ░░ ░░░   ░░░ 
             ░░  ░░ ░      ░░   ░░    ░░░░░░░  ░░░░  ░░░░░     ░░░ ░░  ░ ░░░░  ░░ 
              ░░░  ▒           ░░ ░  ░░     ░░  ▒     ░░   ░░░░ ░░ ░░░░░░░░░ ░░░░ 
           ░    ░░      ░░          ░   ░    ░         ░   ░  ░░ ░░  ░░ ░ ░░    ▒ 
          ░   ░      ░░       ░   ░░░   ░   ░             ░  ░░  ░▒  ▒░  ░  ░     
  ░▒     ▒░      ▒ ░░   ░░  ░    ░         ░     ░      ░                 ░░    ▒░
░░     ▒        ░▒       ░ ░              ░░   ░░      ░░   ░   ░░             ░  
▒                     ░▓░      ░▒                     ░░        ░   ░▓  ▒   ░ ░   
   ░                ▒                  ░                        ░             ░  ░
░    ░░░             ░        ░     ░  ░             ▒░                    ░  ░ ░ 
         ░▓▒▒░                                    ░          ░ ░       ░          
                                                            ░     ░               
                 ░            ░▒░▒░       ░     ░                             ░░  
    ░▓█▒      ░       ▒░ ░░ ░           ▓▓░░ ░░           ░          ░            

## Play now

- [Play now, in browser (GitHub Pages)](https://aaashhh.github.io/AAAsHHH/)

## About

QMars R2 is a small multiplayer-style sandbox game inspired by games like Core Keeper, Terraria, and Stardew Valley.  
It demonstrates:

- Real-time rendering with raylib
- Custom 2D engine and tile/map system
- Asset streaming and resource management
- Web export via Emscripten (WASM)

## Features

- Pixel-art 2D rendering
- Tile-based world with camera and culling
- Simple inventory / item system
- Save/load system (browser storage via IndexedDB)
- Web, desktop, and potential mobile builds from the same codebase

## Tech stack

- **Language:** C++
- **Engine/Library:** raylib
- **Web build:** Emscripten (WebAssembly)
- **Tools:** MSYS2 / MinGW, Notepad++, custom build scripts

## How to run locally

### Desktop (Windows)

1. Install [raylib](https://github.com/raysan5/raylib) and a C++ toolchain (e.g. w64devkit or MSYS2 + MinGW).
2. Clone this repo:

   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
   cd YOUR_REPO
   ```

3. Build the desktop version:

   ```bash
   g++ -o game.exe main.cpp -IC:\raylib\raylib\src -LC:\raylib\raylib\src -lraylib -lopengl32 -lgdi32 -lwinmm
   ```

4. Run `game.exe`.

### Web (WASM)

You need [Emscripten](https://emscripten.org/).

1. Install emsdk and activate a toolchain.
2. Build raylib for web (once):

   ```bash
   cd C:\raylib\raylib\src
   set EMSDK_PATH=C:\raylib\emsdk
   mingw32-make PLATFORM=PLATFORM_WEB clean
   mingw32-make PLATFORM=PLATFORM_WEB
   ```

3. Build the game:

   ```bash
   emcc -o index.html main.cpp ^
     -I. -IC:\raylib\raylib\src -IC:\raylib\raylib\src\external ^
     -LC:\raylib\raylib\src C:\raylib\raylib\src\libraylib.a ^
     -sUSE_GLFW=3 -sASYNCIFY -sEXPORTED_RUNTIME_METHODS=ccall ^
     --shell-file C:\raylib\raylib\src\shell.html ^
     --preload-file "assets@assets"
   ```

4. Serve locally:

   ```bash
   python -m http.server 8080
   ```

   Then open `http://localhost:8080/`.

## Controls

- **Move:** WASD / Arrow keys  
- **Interact:** E / Mouse  
- **Inventory:** 1–9 keys  
- **Pause:** P / Esc

(Adjust to your actual controls.)

## Roadmap

- Better mobile input support
- Multiplayer over LAN
- More biomes, items, and enemies
- Editor tools for level design

## Contributing

This is primarily a personal project, but suggestions, bug reports, and small PRs are welcome.

               `J ::.:.:.``;;;;;;;;;;;<;;;<<<<<<<<<<<<v<v<vvvvvvvx L
                L  :. :.:.:.:.``;;;;;;;;;;;;;;<;<<<<<<<<<<v<<v<vv<( T
                `> .    . .:.:.:.:.`:;``;;;;;;;;<;;;<;<<<<<<<<<<<v< >
                 b ;           . : .:.:.:.`;;;;;;;;;;;<;;<;<<<<<<<<, I
                 `,`               . : :.:.:.:.`.`;;;;;;;;;;;;<;<;<<. 5
                  b ;                    . : .:.:.:.`;;;;;;;;;;;<;<;<: E
                  `,<                         . . .:.:.:.``;;;;;;;;;;. I
                   b :                             . . :.:.:.:.:.:.;;;. 5
                   `>;                                  . .:..:.:.:.`.:  |
                    b :                                      . . :.:.:.x T
                    `,;                                          . . .::  E
                     b :                                               _  !4
                     `r :                                   __.__,--,;'))))).
                      b :                         ___...--'; `))))))))' '' `>!9eOc
                      `r :              __,--:-;;;)))))))))))'' '' ' ' _. -'-'.`!9Eg.
                       L : . __.--_--:,)))))))))))'' ' '  _. ._.-'-'-'-'\-'\---\/\ ``Qu.
                       `,: !x;:)))))))) ')'' ' _ _._-.'\'\_\_-'\''-\'_'\-'\'\ -_\'-\-. 95n.
                        D` ))))'''  _ .___.-_:/-/\/-_\ /-_, /-,\ \-/_\/\,-\_/-\/-/--' ..v<]9o.
                      __b :<> -_\._/\,- ,_ -\ _/\-\ _-\ -_/-\,\/,-/\_/-_\'\--' .vvvvvvv}v}}x}]NEo.
                .ooPO%LOCu  `< `/\_ -:\/_/-/,\/,/-,/_,-/\ :_\:_-:__-'' ...vvvvvvvvvvvvxx}vx}}}}==No
              .oPO'       `y. `< ~-\ _\/\_,- \ , - ,___..--' .......>>vvvvvvvvx<xvvxx}=x===}~^^   I
        om3jR&57'          `Ey, `\ `!,\ \-/_/\_---''.......vv>>vvvvvvvvvv)v<xvx=}=<~~^~`       :_yd

MIT License – see [LICENSE](LICENSE).

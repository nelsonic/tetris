# Tetris (in `elm`!)

![Tetris header image](https://user-images.githubusercontent.com/194400/30550408-49acb6a2-9c8f-11e7-98db-a4a9bdb9e926.png)


## Why?

Building games is the _most_ "_fun_" you can have
while learning how to program in a new language or platform!


## What?

Our _quest_ to follow the Elm Tetris Tutorial by "_Captain Coder_": https://youtu.be/GMSXYnMH1gg
[![Tetris in Elm Tutorial](https://user-images.githubusercontent.com/194400/30550531-9c488d1e-9c8f-11e7-8076-f5d78c63be11.png)](https://youtu.be/GMSXYnMH1gg)

### Tetris?

Tetris is familiar to _most_ people 
that have played computer/video games...

![Tetris Game Play GIF](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c4/Tetris_basic_game.gif/220px-Tetris_basic_game.gif)

If you have _never_ played it, try now:
https://tetris.com/play-tetris <br />
And, read the history: https://en.wikipedia.org/wiki/Tetris


## _How_?


### 0. Setup

Start by installing elm: https://guide.elm-lang.org/install.html
Ensure that you have a text editor installed, 
in our case we are using Atom: https://atom.io

We are also using `elm-format` to make the code look "_`elm`-ish_".
In _my_ case I had to:

```sh
npm install elm-format -g
```
***AND***
```sh
apm install elm-format
```
If you get "_stuck_" installing the packages,
google for the error message you see and if you
are _still_ stuck after 10mins of googling,
open an issue on GitHub: https://github.com/nelsonic/tetris/issues

### 1. Run `elm-reactor`

In the `/tetris` directory run the `elm-rector` command.
You should see:

![terminal elm reactor](https://user-images.githubusercontent.com/194400/30550173-97567920-9c8e-11e7-84ba-3269f099057a.png)

This runs a local web server on your computer that you can 
access by visiting in the browser: http://localhost:8000

![elm reactor in chrome web browser](https://user-images.githubusercontent.com/194400/30550453-61a08464-9c8f-11e7-9cdb-cd91a5f095ee.png)

### 2. Type the initial code from the the Video

After trying to run the _initial_ code shown in the tuturial:

```elm
module Block where

import Graphics.Element

main = Graphics.Element = show 42
```

`elm-format` re-formats it to:

```elm
module Block exposing (..)

import Graphics.Element


main =
    show 42
```

### 3. Install 

In your terminal, type:

```sh
elm-package install evancz/elm-graphics
```

You should see something like this:
![elm-package install evancz/elm-graphics](https://user-images.githubusercontent.com/194400/30551769-8b2d8936-9c93-11e7-9cf9-dd43b2947ff3.png)

> Again, thanks to StackOverflow: 
https://stackoverflow.com/questions/41408360/what-happened-to-graphics-package-in-elm-0-18

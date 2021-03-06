# 18xx-maker/games

[![build](https://travis-ci.org/18xx-maker/games.svg?branch=master)](https://travis-ci.org/18xx-maker/games)
![version](https://img.shields.io/npm/v/@18xx-maker/games)
![downloads](https://img.shields.io/npm/dt/@18xx-maker/games)
![license](https://img.shields.io/npm/l/@18xx-maker/games)

This repository contains the game and tile files that 18xx-maker uses. It's
purpose is to allow others to get access to these files easily without needed to
use the entire 18xx-maker repository.

## Tiles

We're going to try to keep tiles in this repo consistant with a standard.

- If there is a straight on the tile, have it go from side 1-4 by default.
- If there are two straights on the tile have them go from side 1-4 and 2-5.
- When there are multiple track all originating from one side, prefer that to be
  side 1 (This allows tiles like 26/27, and 28/29 to be symetrical).
- Prefer lower number tile sides for all track. This means a sharp alone with be
  1-2, a gentle 1-3 and a straight 1-4.
- Prefer to leave highest number sides open when possible (This often will agree
  with the last rule). For example: a 5 sided tile should leave side 6 open. A
  three sided tile should leave sides 4-6 open.
- When a tile is in a chicken foot configuration (like 19 or 619) prefer to use
  sides 1,3,4,5 (This should correspond with the keeping straights on sides
  1-4).
- Track coming from the lower side should be "over" and the other track should
  be "under" when applicable.

# Atari Lynx Games ComLynx Configuration

I could not get any technical information about Atari Lynx games, while working on a ComLynx implementation. So I started collecting information as I came across it.

Some of this was confirmed in [this old document](https://atarilynxdeveloper.wordpress.com/documentation/redeye/). The rest was read out from `SERDAT` and `SERCTL` themselves.

**DISCLAIMER**: this is by no means complete and there are no guarantees about accuracy. Having said that, you may use this information in any way you please. Though it would be nice of you to mention [github.com/superKoder/lynx_game_info/](https://github.com/superKoder/lynx_game_info/main/README.md) as a source whenever you do. 

Contributions are welcome!

## All Games (to be completed...)


### Baseball Heroes 

* ID: `50 20`
* P1 handshake: `05 00 00 03 50 20 87`
* P2 handshake: `05 00 01 03 50 20 86` 


### Basketbrawl

* ID: `20 00`
* P1 handshake: `05 00 00 01 20 00 D9`
* P2 handshake: `05 00 01 03 20 00 D6` 


### Bill & Ted's Excellent Adventure

* ID: `00 00` (unset?)
* P1 handshake: `05 00 00 01 00 00 F9`
* P2 handshake: `05 00 01 03 00 00 F6` 


### California Games

_California Games_ appears to be a little of an odd one, when it comes to ComLynx communication.

* ID: `03 00`
* P1 handshake: `03 00 80 FE C8 92 DB 02`
* P2 handshake: `03 00 01 FC 7C 13 0F 01` 


### Checkered Flag

* ID: `C8 00`
* P1 handshake: `05 00 00 01 C8 00 31`
* P2 handshake: `05 00 01 03 C8 00 2E` 


### Double Dragon

This ComLynx handshake is exactly the same as _Pit-Fighter_'s.

* ID: `FF FF` (unset?)
* P1 handshake: `05 00 00 01 FF FF FB`
* P2 handshake: `05 00 01 03 FF FF F8` 


### Gauntlet III

* ID: `01 00`
* P1 handshake: `05 00 00 01 01 00 F8`
* P2 handshake: `05 00 01 03 01 00 F5`


### Malibu Bikini Beach Ball

* ID: n/a
* P1 handshake: `FF`
* P2 handshake: `FE` 


### NFL Football

* ID: `B0 B0`
* P1 handshake: `05 00 00 03 B0 B0 97`
* P2 handshake: `05 00 01 02 B0 B0 97` (or `05 00 01 03 B0 B0 96`) 


### Pit-Fighter

This ComLynx handshake is exactly the same as _Double Dragon_'s.

* ID: `FF FF` (unset?)
* P1 handshake: `05 00 00 01 FF FF FB`
* P2 handshake: `05 00 01 03 FF FF F8` 


### Rampage

* ID: `55 13`
* P1 handshake: `05 00 00 03 55 13 8F`
* P2 handshake: `05 00 01 03 55 13 8E`


### Robo-Squash
* ID: `06 00`
* P1 handshake: `05 00 00 01 06 00 F3`
* P2 handshake: `05 00 01 03 06 00 F0`


### Shanghai

* ID: `53 00`
* P1 handshake: `05 00 00 01 53 00 A6`
* P2 handshake: `05 00 01 02 53 00 A4`


### (Todd's Adventures in) Slime World

* ID: `05 00`
* P1 handshake: `05 00 00 01 05 00 F4`
* P2 handshake: `05 00 01 03 05 00 F1` 


### Warbirds

* ID: `07 00`
* P1 handshake: `05 00 00 01 07 00 F2` (or `05 00 00 01 07 00 F0`)
* P2 handshake: `05 00 01 03 07 00 EF` 


### World Class Soccer 

* ID: `28 00`
* P1 handshake: `05 00 00 03 28 00 CF`
* P2 handshake: `05 00 01 03 28 00 CE` 


### Xenophobe

* ID: `04 00`
* P1 handshake: `05 00 00 01 04 00 F5` (or `05 00 00 03 04 00 F3`)
* P2 handshake: `05 00 01 03 04 00 F2` 


### Xybots 

* ID: `FF 00`
* P1 handshake: `05 00 00 01 FF 00 FA`
* P2 handshake: `05 00 01 03 FF 00 F7` 


### Zarlor Mercinary

* ID: `02 00`
* P1 handshake: `05 00 00 01 02 00 F7`
* P2 handshake: `05 00 01 03 02 00 F4`

(To be continued... I hope...)

# Atari Lynx Games ComLynx Configuration

I could not get any technical information about Atari Lynx games, while working on [my own ComLynx implementation](https://github.com/superKoder/comlynx). So I started collecting information as I came across it.

Some of this was confirmed in [this old document](https://atarilynxdeveloper.wordpress.com/documentation/redeye/). The rest was read out from `SERDAT` and `SERCTL` themselves.

**DISCLAIMER**: this is by no means complete and there are no guarantees about accuracy. Having said that, you may use this information in any way you please. Though it would be nice of you to mention [github.com/superKoder/lynx_game_info/](https://github.com/superKoder/lynx_game_info/blob/main/README.md) as a source whenever you do. 

Contributions are welcome!

## All Games (to be completed...)


### Baseball Heroes 

* ID: 8272 (`50 20`)
* P1 handshake: `05 00 00 03 50 20 87`
* P2 handshake: `05 00 01 03 50 20 86` 
* Parity: enabled (odd)


### Basketbrawl

* ID: 32 (`20 00`)
* P1 handshake: `05 00 00 01 20 00 D9`
* P2 handshake: `05 00 01 03 20 00 D6` 
* Parity: enabled (odd)


### Battle Wheels

* ID: 28672 `00 70`
* P1 handshake: `05 00 00 03 00 70 87`
* P2 handshake: `05 00 01 03 00 70 86` 
* Parity: enabled (odd)


### Battlezone

_Malibu Bikini Volleyball_ and _Battlezone_ are oddballs. They doesn't do the usual ritual, but rather handshakes on a single byte!

* ID: n/a
* P1 handshake: `FF`
* P2 handshake: `FE` 
* Parity: enabled (odd)


### Bill & Ted's Excellent Adventure

* ID: explicitly unset (`00 00`)
* P1 handshake: `05 00 00 01 00 00 F9`
* P2 handshake: `05 00 01 03 00 00 F6` 
* Parity: enabled (odd)


### California Games

_California Games_ appears to be a little of an odd ball when it comes to ComLynx communication. Not only is its handshake very confusing, compared with most of the others. It is also the only game I can think of, so far, that uses even parity.

* ID: 3 (according to Epix doc)
* P1 handshake: `03 00 80 FE C8 92 DB 02`
* P2 handshake: `03 00 01 FC 7C 13 0F 01` 
* Parity: enabled (even!)


### Checkered Flag

* ID: 200 (`C8 00`)
* P1 handshake: `05 00 00 01 C8 00 31`
* P2 handshake: `05 00 01 03 C8 00 2E` 
* Parity: enabled (odd)


### Double Dragon

This ComLynx handshake is exactly the same as _Pit-Fighter_'s.

* ID: 65535 (`FF FF`), basically -1 and not unique.
* P1 handshake: `05 00 00 01 FF FF FB`
* P2 handshake: `05 00 01 03 FF FF F8` 
* Parity: enabled (odd)


### Gauntlet - The Third Encounter

* ID: 1 (`01 00`)
* P1 handshake: `05 00 00 01 01 00 F8`
* P2 handshake: `05 00 01 03 01 00 F5`
* Parity: enabled (odd)


### Malibu Bikini Volleyball

_Malibu Bikini Volleyball_ and _Battlezone_ are oddballs. They doesn't do the usual ritual, but rather handshakes on a single byte!

* ID: n/a
* P1 handshake: `FF`
* P2 handshake: `FE` 
* Parity: enabled (odd)


### NFL Football

* ID: 45232 (`B0 B0`)
* P1 handshake: `05 00 00 03 B0 B0 97`
* P2 handshake: `05 00 01 02 B0 B0 97` (or `05 00 01 03 B0 B0 96`) 
* Parity: enabled (odd)


### Pit-Fighter

This ComLynx handshake is exactly the same as _Double Dragon_'s.

* ID: 65535 (`FF FF`), basically -1 and not unique.
* P1 handshake: `05 00 00 01 FF FF FB`
* P2 handshake: `05 00 01 03 FF FF F8` 
* Parity: enabled (odd)


### Raiden (prototype)

* ID: 47806 (`BE BA`), to spell "babe"
* P1 handshake: `05 00 00 03 BE BA 7F`
* P2 handshake: `05 00 01 03 BE BA 7E`
* Parity: enabled (odd)


### Rampage

* ID: 4949 (`55 13`)
* P1 handshake: `05 00 00 03 55 13 8F`
* P2 handshake: `05 00 01 03 55 13 8E`
* Parity: enabled (odd)


### Rampart

* ID: 210 (`D2 00`)
* P1 handshake: `05 00 00 03 D2 00 25`
* P2 handshake: `05 00 01 03 D2 00 24`
* Parity: enabled (odd)


### Robo-Squash
* ID: 6 (`06 00`)
* P1 handshake: `05 00 00 01 06 00 F3`
* P2 handshake: `05 00 01 03 06 00 F0`
* Parity: enabled (odd)


### Shanghai

* ID: 83 (`53 00`)
* P1 handshake: `05 00 00 01 53 00 A6`
* P2 handshake: `05 00 01 02 53 00 A4`
* Parity: enabled (odd)


### (Todd's Adventures in) Slime World

* ID: 5 (`05 00`)
* P1 handshake: `05 00 00 01 05 00 F4`
* P2 handshake: `05 00 01 03 05 00 F1`
* Parity: enabled (odd)


### Warbirds

* ID: 7 (`07 00`)
* P1 handshake: `05 00 00 01 07 00 F2` (or `05 00 00 01 07 00 F0`)
* P2 handshake: `05 00 01 03 07 00 EF` 
* Parity: enabled (odd)


### World Class Soccer 

* ID: 40 (`28 00`)
* P1 handshake: `05 00 00 03 28 00 CF`
* P2 handshake: `05 00 01 03 28 00 CE` 
* Parity: enabled (odd)


### Xenophobe

* ID: `04 00`
* P1 handshake: `05 00 00 01 04 00 F5` (or `05 00 00 03 04 00 F3`)
* P2 handshake: `05 00 01 03 04 00 F2` 
* Parity: enabled (odd)


### Xybots 

* ID: 255 (`FF 00`)
* P1 handshake: `05 00 00 01 FF 00 FA`
* P2 handshake: `05 00 01 03 FF 00 F7` 
* Parity: enabled (odd)


### Zarlor Mercinary

* ID: 2 (`02 00`)
* P1 handshake: `05 00 00 01 02 00 F7`
* P2 handshake: `05 00 01 03 02 00 F4`
* Parity: enabled (odd)


(To be continued... I hope...)

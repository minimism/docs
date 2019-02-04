![WonkyStuff](../wonkystuff_inv.jpg)

# WonkyStuff **One Unit Of Delay** (_Rev.A_) Assembly Instructions

Thanks for buying the WonkyStuff **One Unit Of Delay** board. The board is
designed as a simple audio delay block to be used in conjuntion with an
external mixer (such as the WonkyStuff 5x5 matrix mixer) to build up
various delay-based circuits. The circuit is based on the _PT2399_
delay chip and as such has a certain lo-fi quality… this is by intent!
The circuit is designed to run from 4.5—5v - applying any more is likely
to cause damage to the chips (the other components will be fine unless
you plug it into a very high voltage. _Don't plug it into a very high
voltage._).

_These instructions are a work in progress. If they are unclear, or there
are any mistakes, or you just want to say 'hello', please email us at
info@wonkystuff.net, or message us via facebook or twitter.
Our website is http://wonkystuff.net/._

There is a basic requirement that your soldering skills are up to scratch
(I'm sure they are). If you need a reminder, you could do worse than to
take a look at this soldering tutorial over at adafruit.com:
https://learn.adafruit.com/adafruit-guide-excellent-soldering/

## Parts List

Before starting, make sure that you have all of the parts listed below.
The chips are not big fans of static electricity, so take care when 
handling them (they're quite robust in our experience, but take care
nonetheless).

| Label  | Part | Description |
| ------ | ---- | ----------- |
| P1  | Power connector | apply 4.5-5.5v here |
| U1  | PT2399 | echo/delay processor |
| C1  | 100nF | Capacitor (marked 104) |
| C3  | 100nF | Capacitor (marked 104) |
| C4  | 100nF | Capacitor (marked 104) |
| C6  | 47n | Capacitor (marked 473) |
| C7  | 47n | Capacitor (marked 473) |
| C8  | 470pF | Capacitor (marked 471) |
| C9  | 470pF | Capacitor (marked 471) |
| R1  | 10k | Resistor (brown/black/black/red/brown stripes) |
| R2  | 10k | Resistor (brown/black/black/red/brown stripes) |
| R3  | 10k | Resistor (brown/black/black/red/brown stripes) |
| R4  | 100k | Resistor (brown/black/black/orange/brown stripes) |
| R6  | 10k | Resistor (brown/black/black/red/brown stripes) |
| R7  | 10k | Resistor (brown/black/black/red/brown stripes) |
| R8  | 10k | Resistor (brown/black/black/red/brown stripes) |
| R10 | 10k | Resistor (brown/black/black/red/brown stripes) |
| C10 | 4n7 | Capacitor (marked 472) |
| C14 | 4n7 | Capacitor (marked 472) |
| J1  | 3.5mm jack  | Audio inputput |
| J2  | 3.5mm jack  | Audio Output |
| R5  | 2k2 | Resistor (red/red/black/brown/brown stripes) |
| R9  | 2k2 | Resistor (red/red/black/brown/brown stripes) |
| C12 | 10n | Capacitor (marked 103) |
| VR1 | 47k	Log Potentiometer | Delay time variation |
| VR2 | 47k	Log Potentiometer | Output level control |
| C5  | 47uF | 16V Aluminum electrolytic capacitor |
| C2  | 100uF | 16V Aluminum electrolytic capacitor |
| C11 | 4.7uF | 16V Aluminum electrolytic capacitor |
| C13 | 10uF | 16V Aluminum electrolytic capacitor |
| U2  | MCP6002 | Dual Op-Amp |
| - | 2 IC sockets | |
| - | PCB | a double-sided Printed Circuit Board |

You'll also need a soldering iron, some solder, a pair of wire cutters and a space to work in.

## Assembly


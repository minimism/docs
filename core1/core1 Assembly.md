![WonkyStuff](../wonkystuff_inv.jpg)

# WonkyStuff Core1 Assembly Instructions

Thanks for buying the WonkyStuff **core1** board. The **core1** is designed as a simple audio generation device which can be reprogrammed. There are four controls (the function of which will depend on the programming) and a single, mono, audio output. The **core1** is designed to run from 4.5v - applying any more is likely to cause damage to the chips (the other components will be fine).

_These instructions are a work in progress. If they are unclear, or there are any mistakes, or you just want to say 'hello', please email us at info@wonkystuff.net, or message us via facebook or twitter._

## Parts List

Before starting, make sure that you have all of the parts listed below. The chips are not big fans of static electricity, so take care when handling them (they're quite robust in our experience, but take care nonetheless).

| Label  | Part | Description |
| ------------- | ------------- |
| U1 | ATTiny85-20  | Main processor (pre-programmed as _dr1a_) |
| U2 | MCP6002  | Dual Op-Amp |
| U3 | n/a | Not yet used |
| VR0-3 | 10k Potentiometer x4 | Interaction!|
| R1 | n/a | Not yet used |
| R2 | 15k | Resistor (brown/green/black/red/brown stripes) |
| R3 | 8.2k | Resistor (grey/red/black/brown/brown stripes) |
| C1 | 1nF | Capacitor (marked 102) |
| C2 | 470pF | Capacitor (marked 471) |
| P1 | Power connector | apply 4.5v here |
| J1 | 3.5mm jack | Audio Output |
| B1 | Battery pack | Takes 3 AAA batteries (not included) |
| - | 2 IC sockets | |
| - | PCB | a double-sided Printed Circuit Board |

You'll also need a soldering iron, some solder, a pair of wire cutters and a space to work in.

## Assembly

**Core1** requires components to be placed on both sides of the PCB, the white text/outline will indicate the correct placing of each component.

The general procedure with the assembly is to work in component-height order, so, let's start!

1. Position the PCB so that the _Designed by…_ text is uppermost:
    1. Solder R2 and R3;
    1. Solder C1 and C2;
    1. Solder IC sockets into positions U1 and U2, taking care to match the notch in the socket with the symbol on the PCB.
    1. Solder the power connector so that it protrudes over the edge of the PCB
1. Turn over the PCB:
    1. Solder J1 into place - take care that the pins go into the correct holes (and not into R1);
    2. Solder the four potentiometers into place (the large tabs may need a slight squeeze for them to go into the holes correctly). The tabs are there for mechanical support, don't forget to solder them!
1. Turn the board over again and insert U1 and U2 into their respective sockets (the legs may need a little squeeze to make them line up).

And that's it for assembly.

## Sound!

The ATTiny85 comes pre-programmed with the **dr1.a** firmware (https://github.com/minimism/dr1a); a fairly simple drone synth capable of generating some quite nice sounds.

1. Insert 3 AAA batteries into the battery holder;
1. Connect the audio output to your audio device (e.g. a mixer);
1. Rotate all of the controls fully counter-clockwise;
1. Attach the battery pack to the board.

Now there should be a low-frequency sound coming from the output. Altering VR1 will change the waveform (there are 8 different shapes). VR2 changes the fundamental frequency, and VR3 changes the slave frequency - play about and see what sounds good. VR0 causes the waveform to change randomly - the frequency of change depends on how far clockwise VR0  is turned.

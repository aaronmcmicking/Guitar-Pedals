# Dandy Horse (Echoflanger)

The [Lectric-FX Dandy Horse](https://lectric-fx.com/product/dandy-horse-v-1-0/) 
is a clone of the discontinued Electro-Harmonix Echoflanger (eventually replaced 
by the [Polychorus](https://shop.ehx.com/item/polyxo/)), a multi-effect 
modulation pedal that started production in the late 1970s.

I began researching and compiling parts for this project in November 2022.
I then did the bulk of the soldering and building over winter break between
my semesters in first year university. The first tests showed that it had significant issues, but unfortunately as the next semester was beginning I
had to shelve it and wait until summer to debug it.

To date, I have not completed this project and troubleshooting is still ongoing. 
I am on a semi-hiatus from this build to pursue other projects, but fully intend
to come back and resolve its issues.

## Resources

The most valuable resource throughout this project has been the [Lectric-FX forums](https://www.madbeanpedals.com/forum/index.php?board=67.0) (login may be
required at link), hosted by [madbeanpedals](https://www.madbeanpedals.com/). 
The folks from Lectrix-FX and other users have been incredibly helpful and I 
would have been beyond lost without this resource.

## Troubleshooting

Initially, the supply voltage was half of what it should have been. This ended up 
being the result of a pad that I erroneously jumpered (fortunately, the build 
documentation has been since been updated to resolve ambiguity about this as it 
appeared to be a somewhat common mistake on the forums). 

However, I believe there is still a grounding issue somewhere. In dry mode, the output is dead. In Blend mode, the signal is simply bypassed unaffected. Internal bias potentiometers and voltages at internal test pads behave as expected for the first few of each, and then begin to have no effect on the signal, as measured
using a homemade audio probe. IC voltage readings are also often in disagreeance
with expected values, although it is difficult to tell from these where in the 
circuit the problem originates. This is where the build currently stands as I
am taking a break from it to pursue other projects, although I will come back
and fix it at some point in the (hopefully near) future.

## Photos

![The individual pedal components laid out on a table](/Dandy%20Horse%20(EHX%20Echoflanger)/photos/parts.jpg)

![The board with almost all components soldered onto it](/Dandy%20Horse%20(EHX%20Echoflanger)/photos/board_soldered.jpg)

![The board mounted into it's enclosure, with most components soldered on](/Dandy%20Horse%20(EHX%20Echoflanger)/photos/in_box.jpg)
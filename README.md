# fsy8
The FSY8 Fantasy Microcontroller

![Alt Text](https://github.com/trevortomesh/fsy8/blob/master/img/fsy8Demo.gif)

## What's all this, then?
The FSY8 (pronounced fizzy-8) is a "fantasy microcontroller" inspired by the
"fantasy console" movement.

It started as a thought experiment for my thesis work, but sort of took on a
life of it's own.

## Why "FSY8? Why not FSY9?"
... because it's got 8 pins.


## Does it have specs?
Yes -- well, basic specs at least. A formal spec sheet is being drawn up, but
here's the basics:

![Alt Text](https://github.com/trevortomesh/fsy8/blob/master/img/FSY8.png)

## So -- installation instructions?
As of right now -- you can't. It doesn't really exist yet in an executable form (working on it).

## What's a "fantasy microcontroller?"
This is a thought experiment first and foremost. It is an exercise in systems
theory / platform studies. When I started studying hardware systems platforms, one of
the first questions I asked myself was "what is a system platform?" Unexpectedly, the
answer came from lexaloffle games -- specifically the [PICO-8](https://www.lexaloffle.com/pico-8.php):

```text
The harsh limitations of PICO-8 are carefully chosen to be fun to work with,
encourage small but expressive designs and hopefully to give PICO-8 cartridges
their own particular look and feel. - PICO-8 Official Website
```

For me, this sold the concept that a "platform" is simply a collection of
restrictions applied to a medium - a collection of system specifications that is
agreed upon by creators working within that "platform". Originally these
restrictions were determined by hardware constraints -- however, given the
plethora of readily available computing resources on modern computing platforms,
the standard creator seldom has to work against these constraints. This is my
interpretation of the fantasy console genre -- a set of constraints agreed upon
by those who work within the platform.

Long story short -- I thought, "hey, that's a great idea! What if the platform
was a microcontroller, though?"

... although, I have to acknowledge that ZACHTRONICS (http://www.zachtronics.com/shenzhen-io/)
 really beat me to the punch on this. :-p

## How about an instruction set?
So, first things first -- I am working on building something I can interact with
in python. Then I'll write an assembly interpreter. I think. Let me at least
get the ALU structure and block diagramming figured out.

## Can I help?
Yes please. Send me a pull request or open an issue! You've probably got better
ideas and are smarter than me. 

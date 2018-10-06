# TinyKeeb
This repository will host all the source code, CAD files, and diagrams I will be using to build my second custom keyboard (you can find my [first one here](https://github.com/nafajardo/PhantomTKL)).

## Plan
Similar to my first keyboard, I want to first do some research on what layout I am looking for, draw it up on my computer, and then do some experimentation. Unlike my first build, I would like to make this keyboard ortholinear (non staggered), and start exploring the realm of layered functionality instead of limiting my layout to predefined standards like qwerty. Interesting layouts exist like [dvorak](https://www.dvorak-keyboard.com/) that seem cool to learn, and could possibly be better.

Ideally, I would like to utilize my 3D printer somehow in this build to dust off my PLA reels. Unlike my first keyboard build, I would want to explore some woodworking in this keyboard, and possibly utilize some sort of joint system like [any of these](http://metosexpo.free.fr/extra/wood_ebooks/others/The%20Joint%20Book.pdf).

The plan to implement the keyboard will probably go in this order:
- [ ] Design Keyboard Layout
- [ ] Decide on switches
- [ ] Design PCB, if needed
- [ ] Design Case in CAD
- [ ] Fabricate Keyboard

## Tools Required
Software:
* [Keyboard Layout Editor](http://www.keyboard-layout-editor.com/)
* [Plate Creator](http://builder.swillkb.com/)
* [Solidworks](https://www.solidworks.com/)

Hardware:
* [Cherry MX Clear Switch](https://deskthority.net/wiki/Cherry_MX_Clear)

## Design Keyboard Layout
After some internal discourse, I am currently looking at following a keyboard layout:

![Alt Text](https://github.com/nafajardo/TinyKeeb/blob/master/KeyboardLayout/keyboard-layout.jpg)

This keyboard utilizes another layer, that can only be access by pressing the fn button on the right of the spacebar. This will allow me to have all the buttons on a full keyboard while retaining the size I want in this build. So in simpler terms, any function that is found on the bottom right of the key in the diagram can only be access when holding the Fn button.

I plugged in the raw JSON of this layout into [Plate Creator](http://builder.swillkb.com/), and produced a 2d version of the file that will turn into my plate layer.

![Player Layer Raw]()

This now will be used in my CAD

## Design Case in CAD

My case will revolve around utilizing cherry switches, a metal 1.5 mm switch layer, and some sort of cable interface. For my cad modeling, I will be using drawings based on the layered json files, produced by [Keyboard Layout Editor]{http://www.keyboard-layout-editor.com/#/}. My 3D assemblies also include models from these resources:
* [Keycaps]{https://github.com/dankwookiee/Kieeboard}
* [Cherry Switch]{https://grabcad.com/library/cherry-mx-switches-mx-1}.

One of the more important aspects of this build for me is to produce some sort of keyboard that is both beautiful in design, and easy to take apart. For this reason, I would like to look into some sort of cool wood joining. After perusing [this book](http://metosexpo.free.fr/extra/wood_ebooks/others/The%20Joint%20Book.pdf), I have found an interesting joint I feel would be cool to implement:

![Wood Joint Picture]()

So after a couple of hours of CAD, I came up with this:

![Angle Pic]()
![Side Pic]()
![Bottom Pic]()
![Top Pic]()

## Design PCB
## Fabricate Keyboard

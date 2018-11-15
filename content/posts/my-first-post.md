---
title: "We're back for Piwars 2019"
date: 2018-10-10T21:00:00+01:00
image: https://lh3.googleusercontent.com/7QkiR90G5ltWUAUtVOQ2MveXGgbOQXUMvyW75aOGsxsOCtVmkjm5srlFss8twOWe3fDEkxHehMj6dGLhOa2aK-oBlKmw4aastKc3-Bd-lLTwp79qVZOWgqRu3ctbPh0eB0gtYNIPKa01uswCv7P7dRetwUZNUCga9Q84t6QNGAnWW17Fcs5qijmmcKBTZb-ty4eaaAB9O3HSpjWwqU7_iIpx4h47GuVXZFDaV5f0D0aomM2naQT6a3JJr6jsWswbYxNif6QASv3tY3yYdU37Q5-zfK5NvL-EFNJ8GsiNqTdJ9uVf67RjrWA4bNOYeo6eTQ011QzCJFqbDZQlQSYAiB5Q9k04dt91mldoOgN94MaGX2O50OIAJpI6jysdLUfu-a1sLLxpNMJdXCW4e7Bbe1i8HPhAD4jtuy-i9vhXAEp5u6ANj7kg_vK4mo8gEp-eK67iD3OsHXBZH3FF097tMXtu94MRXP1uN82JLD17w-PEFdg6Q9OCJqx6kUDmM7kiowPwsFpjxXBYBUB7qHjcGTuHlHscAhva_aatOCGozATbhqUwPqVGllLRD7lUrKam0OHyNWj2jXhDJAyc2z-HFxoisG9QhqbHJK9kcEwbfWm3lwcg7djbOLOfaIkJZQ9DxHtiFBTICj5sJuRH3aqLYLWaVv9wHYmpPqVj19w6RgPg4k5CsMLhfQltjb8KaXm9-gpV2oJkccgr2Hr1NNU=w1675-h942-no
---

We are pleased to have been selected again for the upcoming [Piwars](https://www.piwars.org) competition in Mars 2019.
This will be the 3rd time that we participate to Piwars, and hopefully this year we will do better.

<!--more-->

We will keep our little Night Fury robot, from last year's design, as our starting point for this year competition. After all, he served us well last year, as we managed to win the duck shooting challenge... to our greatest surprise :)

Our design is following the "simple is best" philosophy. We re-used the mechanical parts of a RC toy car (i.e. the wheels, gears and motors) and 3D printed a chasis slightly bigger that the original toy to fit comfortably the PI and PCB inside.
The PCB is minimal as the Raspebrry PI is doing almost all the work. The PCB only powers the PI via its GPIO and drives the 2 motors using a motor driver directly connected to the PI's GPIO.
Add a battery and a camera and we have pretty much all the elements of our robots.

Our ambition (or challenge depending how you look at it) is to bring all the complexity into the software of the robot. I like the idea of proving that the PI is capable of doing complex things with minimal surrounding components. Hopefully this year we will be able to do just that!

![Our little Night Fury](https://lh3.googleusercontent.com/7QkiR90G5ltWUAUtVOQ2MveXGgbOQXUMvyW75aOGsxsOCtVmkjm5srlFss8twOWe3fDEkxHehMj6dGLhOa2aK-oBlKmw4aastKc3-Bd-lLTwp79qVZOWgqRu3ctbPh0eB0gtYNIPKa01uswCv7P7dRetwUZNUCga9Q84t6QNGAnWW17Fcs5qijmmcKBTZb-ty4eaaAB9O3HSpjWwqU7_iIpx4h47GuVXZFDaV5f0D0aomM2naQT6a3JJr6jsWswbYxNif6QASv3tY3yYdU37Q5-zfK5NvL-EFNJ8GsiNqTdJ9uVf67RjrWA4bNOYeo6eTQ011QzCJFqbDZQlQSYAiB5Q9k04dt91mldoOgN94MaGX2O50OIAJpI6jysdLUfu-a1sLLxpNMJdXCW4e7Bbe1i8HPhAD4jtuy-i9vhXAEp5u6ANj7kg_vK4mo8gEp-eK67iD3OsHXBZH3FF097tMXtu94MRXP1uN82JLD17w-PEFdg6Q9OCJqx6kUDmM7kiowPwsFpjxXBYBUB7qHjcGTuHlHscAhva_aatOCGozATbhqUwPqVGllLRD7lUrKam0OHyNWj2jXhDJAyc2z-HFxoisG9QhqbHJK9kcEwbfWm3lwcg7djbOLOfaIkJZQ9DxHtiFBTICj5sJuRH3aqLYLWaVv9wHYmpPqVj19w6RgPg4k5CsMLhfQltjb8KaXm9-gpV2oJkccgr2Hr1NNU=w1675-h942-no)
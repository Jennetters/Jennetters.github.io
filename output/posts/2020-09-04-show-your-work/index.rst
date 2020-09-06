.. title: Show Your Work
.. slug: 2020-09-04-show-your-work
.. date: 2020-09-04 10:45:48 UTC-04:00
.. tags: dactyl, ortholinear, split mechanical keyboard, mechanical keyboard, 3d printing,
.. category: 
.. link: jennetters.github.io
.. description: There's a reason why teachers drilled the behaviour of showing your work, into our heads.
.. type: text

With a lack of build guide for this print I used a mixture of my limited knowledge of circuitry, logic, and previous experience to get this guy wired. I always make sure to test connections every step of the way, it's so much easier than fixing problems after the fact.

Yet, lo and behold! After flashing the pro micro successfully, and then connecting the microprocessors to the keyboard, I was a bit surprised that it wasn't working. 

Like. 

At all.

This isn't my first rodeo, so I didn't expect anything to be perfect the first go around but it took some tinkering and digging to figure out that the pro-micro pins were slightly different from the pins used in the dactyl files on qmk.

This isn't a big problem, at all, you just need to make sure the pins listed in the config.h file correspond to your wiring.

.. link:galleries/dactyl_ez2print

Here's some resources that helped me out:

https://golem.hu/pic/pro_micro_pinout.jpg

https://keyboardchecker.com/

https://docs.qmk.fm/#/config_options

If you get stuck, there's a lot of information on the QMK site.
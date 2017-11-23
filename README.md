<!-- -*- mode: markdown; fill-column: 8192 -*- -->

This is my talk proposal for the [FOSDEM 2018 Hardware Enablement Devroom][fosdem:hwen], currently a work in progress.

 [fosdem:hwen]: https://fosdem.org/2018/schedule/track/hardware_enablement/


<!-- title -->
# Owning our tools

<!-- subtitle -->
Or how having open source input devices opens up a whole new world.

<!-- abstract -->
## Abstract

For people who work with computers, be them hackers, gamers or anyone else, an efficient input device is essential. These are the tools we use daily, through which we interact with the computer the most (at least, in many cases). Yet, very few of these devices have open source firmware, and we don't seem to mind that very much. In this talk, I will highlight why that is wrong. I will show you examples of astonishing productivity boosts one can accomplish with a fully programmable, open-source keyboard. I will show you how being able to control our input devices is not only liberating, but a tremendous boost to not only our productivity, but our feeling of comfort as well.

<!-- full description -->
## Full description

Most of us have worked with keyboards here. Most of us think we have a solid idea about how we can use our keyboards efficiently. Most of us think keyboards, in general, are safe. Most of us think keyboards are simple.

Most of us are wrong.

We have been using the same layout (both physical and logical) for decades, with minor variations, hardly ever questioning if we can do better. Even worse, we have been trained to think that keyboards can only work the way they usually do now. How many of you heard about the [Space Cadet Shift][scs]? Or [dual-use][dual-use] keys? Or layers? Or [tap-dance][td]? All of these can provide tremendous benefit. But to use them, we need to program our keyboards.

 [scs]: http://stevelosh.com/blog/2012/10/a-modern-space-cadet/#shift-parentheses
 [dual-use]: https://github.com/keyboardio/Kaleidoscope-DualUse#kaleidoscope-dualuse
 [td]: https://github.com/keyboardio/Kaleidoscope-TapDance#kaleidoscope-tapdance

Keyboards can be dangerous tools in the wrong hands. We have seen [keyloggers][mantistek:gk2] in various keyboards. We have seen Bluetooth devices being [vulnerable][btvuln], keyboards and mice alike. To combat these issues, to be able to fix our most basic input devices, we need to control the firmware.

 [mantistek:gk2]: http://www.tomshardware.com/news/mantistek-gk2-collects-typed-keys,35850.html
 [btvuln]: https://www.wired.com/2016/02/flaws-in-wireless-mice-and-keyboards-let-hackers-type-on-your-pc/

Many people feel keyboards are simple. You press keys, they appear on the screen. Done. What is so hard about that? Oh boy. There is so much more you can do! You can control LEDs, so when your build fails, or your IDE shows an error, your keyboard (or its underglow) turns red. You can program macros, shortcuts, put them on layers! You can teach the keyboard how to input an unicode ☃, and all kinds of 💩!

In recent years, there has been a growing interest in keyboard kits and DIY keyboards. With 3D printers, and parts getting more affordable or accessible, a whole world of makers are building amazing keyboards. Most of them with open source firmware.

Armed with an open source firmware, we can sleep better, knowing that our keyboard won't spy on us. Knowing that if there is a bug somewhere, we can fix it. If we want to do something strange, like control the mouse from the keyboard, we can do that. We can control a touchpad too. Or a joystick. Or a Steno machine. We can do whatever we want to.

And I'm here to tell you stories about all of these things and more.

<!-- Links & resources -->
## Links & resources

### Firmware

* [Kaleidoscope][kaleidoscope]
* [QMK][qmk]
* [KLL][kll]

 [kaleidoscope]: https://github.com/keyboardio/Kaleidoscope
 [qmk]: http://qmk.fm/
 [kll]: https://github.com/kiibohd/controller/

### Keyboards

* [Keyboardio Model01][m01]
* [ErgoDox EZ][ez]
* [OLKB][olkb]

 [m01]: https://shop.keyboard.io/
 [ez]: https://ergodox-ez.com/
 [olkb]: https://olkb.com/

### Resources

* [Multi-purpose keys, and a case for smaller keyboards][blog:mpk]
* [Xah Lee's keyboard articles][xah:keyboards]

 [blog:mpk]: https://asylum.madhouse-project.org/blog/2016/10/15/multi-purpose-keys/
 [xah:keyboards]: http://xahlee.info/kbd/keyboarding.html

<!-- Submission notes -->
## Submission notes

I'm submitting this talk to the hardware enablement devroom for a variety of reasons, ranging from a desire to show how open source firmware, on open source keyboards can boost our productivity, through singing praise of the custom keyboard community, to a wish to highlight the importance of really owning our most precious input devices.

The hardware enablement devroom appears to be the perfect fit for this kind of talk.

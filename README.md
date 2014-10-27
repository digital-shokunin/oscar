oscar
=====

Oscar automatically adds things to your grocery list when you run out. You
just scan the item's barcode on its way into the trash.

Here's a video about it!

<a href="http://youtu.be/i-llLhHVLy0" target="_blank">
<img src="http://img.youtube.com/vi/9_MNOOgFDg4/0.jpg" alt="Oscar Demo" width="240" height="180" border="10" />
</a>


Python3 Branch (Digital-Shokunin)
-----

I have forked this project in order to maintain a version that is Python 3 compatible (ArchLinux ARM users). 

To use this branch:

     git clone -b python3 https://github.com/digital-shokunin/oscar.git

Getting Started: Hardware
-----

I run Oscar on a [Raspberry Pi][raspberry-pi] under [Raspbian][raspbian]. I use
[this barcode scanner][scanner-amazon].

Edit by digital-shokunin: Also supports [Adafruit's compact scanner][scanner-adafruit] which is much more convenient and easier to place somewhere. There is also a [case I designed for it that can be 3D printed][case].

That said, there's no reason Oscar shouldn't work with other hardware.


Getting Started: Software
-----

To install Oscar, run the included `install.py` as root on the target system. It
will walk you through the process of setting up any API accounts you'll need, and
then it'll install the software.

I haven't really tested that install script, so let's cross our fingers together.


Getting Help
-----

I'm [on the Twitters][twitter] if you have a quick question. For bug reports, use
the [issues page][oscar-issues] or submit a pull request.


[raspberry-pi]: http://www.raspberrypi.org/
[raspbian]: http://www.raspbian.org/
[scanner-amazon]: http://www.amazon.com/gp/product/B0085707Z8/ref=oh_details_o03_s00_i03?ie=UTF8&psc=1
[scanner-adafruit]: http://www.adafruit.com/product/1203
[twitter]: https://twitter.com/danslimmon
[oscar-issues]: https://github.com/danslimmon/oscar/issues
[case]: http://www.thingiverse.com/thing:517814

+++
title="Switching from a German to a US Keyboard Layout - Is It Worth It?"
date=2018-09-02
updated=2025-04-24
[taxonomies]
tags=["dev"]

[extra]
credits = [
  {name = "Simon Brüggen", url="https://github.com/m3t0r" },
]
+++

For the first three decades of my life, I've exclusively used a German keyboard layout for programming. In 2018, I finally switched to a US layout.
This post summarizes my thoughts around the topic.
I was looking for a similar article before jumping the gun, but I couldn't find one &mdash; so I wrote it.

{{ figure(src='keychron.jpg', caption='My current keyboard (as of April 2021), the low-profile, tenkeyless Keychron K1 is close to my favorite input device. Yes, I got the RGB version. &mdash; [Amazon referral link](https://amzn.to/3tRatjU).') }}

## Why Switch To the US Layout?

I was reasonably efficient when writing prose, but felt like
a [lemur on a piano](https://www.etsy.com/listing/896826954/funny-piano-art-print-leptodactylous-aye) when programming:
lots of finger-stretching while trying to reach the special keys like `{`, `;`, or `/`.

{{ figure(src="KB_Germany.svg", caption="German Keyboard Layout", credits="[Image by Wikipedia](https://commons.wikimedia.org/w/index.php?curid=1058095)") }}

Here's [Wikipedia's polite
explanation](https://en.wikipedia.org/wiki/German_keyboard_layout) why the
German keyboard **sucks for programming**:

> Like many other non-American keyboards, German keyboards change the right Alt
> key into an <b>Alt Gr key to access a third level</b> of key assignments. This is
> necessary because the umlauts and some other special characters leave no room
> to have all the special symbols of ASCII, needed by programmers among others,
> available on the first or second (shifted) levels without unduly increasing
> the size of the keyboard.

## But Why Switch **Now**?

After many years of using a rubber-dome [Logitech Cordless Desktop
Wave](https://support.logitech.com/en_us/product/cordless-desktop-wave/), I
had to get a mechanical keyboard again.

Those rubber domes just feel too mushy to me now. In addition to that, I enjoy the
clicky sound of a mechanical keyboard and the noticeable tactile bump. (I'm using
[Cherry MX Brown Keys](https://amzn.to/3mm2WHf) with [O-Ring dampeners](https://amzn.to/3miCfTK) to contain the anger of my coworkers.)

Most mechanical keyboards come with an ANSI US layout only, so I figured, I'd
finally make the switch.

{{ figure(src='durgod_taurus.jpg', caption='My first mechanical keyboard &mdash; [Durgod Taurus K320](https://www.amazon.de/gp/product/B07QK16RDQ/ref=as_li_tl?ie=UTF8&tag=matthiasendle-21&camp=1638&creative=6742&linkCode=as2&creativeASIN=B07QK16RDQ&linkId=fb0a782ecbc713f8266b90b941375a5f) (referral link). They also have a fancy [white-pink](https://www.amazon.de/gp/product/B081LZV2QM?ie=UTF8&tag=matthiasendle-21&camp=1638&linkCode=xm2&creativeASIN=B081LZV2QM) ISO version now.') }}

## How Long Did It Take To Get Accustomed To The New Layout?

Working as a Software Engineer, my biggest fear was, that the switch would slow
down my daily work. This turned out not to be true. I was reasonably productive
**from day one**, and nobody even noticed any difference. (That's a good thing,
_right_?)

At first, I didn't like the _bar-shaped US-Return key_. I preferred the European
layout with a _vertical enter key_. I was afraid that I would hit the key by
accident. After a while, I find that the US return key to be even more convenient.
I never hit it by accident, and it's easy to reach with my pinky from the home position.

Within two weeks, I was back to 100% typing speed.

## Did My Programming Speed Improve Noticeably?

Yup. I'd say I can type programs about 30% faster.

Especially when using special characters (`/`, `;`, `{`, and so on) I'm much
faster now; partly because the key locations feel more intuitive, but mainly
because my fingers stay at their dedicated positions.

Somehow the position of special characters feels _just right_. I can finally understand the
reason why Vim is using `/` for search or why the pipe symbol is `|`: both are
easy to reach! [It all makes sense!](/2018/ten-years-of-vim)
(For a fun time, try that on a German keyboard!)

I understand why Mircosoft chose `\` as a directory separator: it's easily
accessible from a US keyboard. On the German layout, it's&hellip; just&hellip; awful
(`Alt Gr`+`ß` on Windows, `Shift` + `Option` + `7` on Mac).

The opening curly brace on a German layout Mac is produced with `Alt`+`8`, which
always made me leave the [home
row](https://en.wikipedia.org/wiki/Touch_typing#Home_row) and break my typing
flow. Now there are dedicated keys for parentheses. Such a relief!

_Update:_ It also helps greatly when looking up hotkeys for IDEs, text editors,
photo editors, etc. because some programs remap shortcuts for the German market,
which means that all the English documentation is totally worthless.
Thanks to the English layout, I can just use the shortcuts mentioned and move on with my life.

## Am I Slower When Writing German Texts Now?

In the beginning, I was.

Somehow my brain associated the German layout with German
texts. First, I used the macOS layout switcher.
This turned out to be cumbersome and take time.

Then I found the "[US with Umlauts via Option Key
Layout](https://hci.rwth-aachen.de/usgermankeyboard)". It works perfectly fine for
me. It allows me to use a single Keyboard layout but insert German umlauts at will
(e.g. ö is `Option`+`o`). There is probably a similar layout for other language combinations.

[Stefan Imhoff](https://www.stefanimhoff.de/) notified me that there's also a
[Karabiner](https://www.stefanimhoff.de/) rule which does the same. Might come
in handy in case you already use this tool.

## Is Switching Between Keyboards Painful?

{{ figure(src="KB_United_States.svg", caption="US keyboard layout" credits="[Wikipedia](https://commons.wikimedia.org/wiki/File:KB_United_States.svg)") }}

My built-in MacBook Pro keyboard layout is still German. I was afraid, that switching between
the internal German and the external English keyboard would confuse me. This
turned out not to be a problem. I rarely look at the print anyway.
(Update: can't remember when I last looked at the print.)

## How Often Do You Switch Back To A German Layout Now?

Never. My Girlfriend has a German keyboard and every time I have to use it, I switch to the US layout. It makes her very happy when I do this and forget to switch back to German when I'm done.

## Summary

If you consider switching, just do it! I don't look back at all
and apart from the initial transition period, I still couldn't find any downsides.

Since posting this article, many of my friends made the switch as well and
had similar experiences:

- [Wolfgang Gassler wrote a post about his layout switch on Linux](https://wolfgang.gassler.org/switch-keyboard-german-to-english-linux-fedora/)
- [Discussion of the article on Twitter](https://twitter.com/ro14nd/status/1304360915840753664)

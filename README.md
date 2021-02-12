# Dvorak ALT Layouts
Two alternatative Dvorak keyboard layouts

One with the IU keys swapped.
The other with the IU and LM keys swapped, see picture below:

![dvorak IULM layout](https://p239.p2.n0.cdn.getcloudapp.com/items/RBu44dWG/e4450f04-e0da-4307-bda6-ef031b741f7f.png?v=c64a6c208d52cac3d90caee7081dc8c0)

## Installation
Mac:
Dowlnoad the .DMG file of the layout you want and open the file inside. Select the keyboard layout in System Preferences -> Keyboard.

PC:
Download the PC version of the file (Sorry there is no IU & LM version for PC) extract and open setup.exe. Then select the keyboard layout in the input sources.

## Motivation and theory
After [analyzing](http://patorjk.com/keyboard-layout-analyzer/) other keyboard layouts like colemak, workman, and norman I came to the conclusion that I could get most of the benefits of these layouts in Dvorak without switching to them by simply swapping the I and U keys.

'I' is much more frequently used in English than 'U' so putting it directly under a finger on the home row makes for less movement of the fingers which should lead to faster typying speed. One should theoretically move their fingers less on this layout than on the traditional Dvorak layout. Dvorak with IU swapped even performed better than some of the other layouts like colemak in certain situations.

The same is also true for the 'L' and 'M' keys. L is used more frequently than M so it makes sense to put it in a position that does not strain the right pinky.

## Personal experience
I have been using the DvorakIU swap keyboard layout since 2009.

It took me about a week and a half of using this new layout until I was up to my old speed on the official Dvorak layout. In the end I found it easier on the hands than the normal Dvorak layout.

I have been using the DvorakIULM swap since 2018 and have been really enjoying it. The time it took to switch was about two weeks to get back to normal typing speed.

## Karabiner
I have also included my karabiner config which you can install by all files in `karabiner` in this repo in `~/.config/karabiner` on your machine.
The config swaps capslock with delete. The complex_modification config files make it so that when the option key is held the right hand home row becomes arrows and the left hand has some common punctiation. Details can be found for each rule when you install the file. The complex modifications are designed to be much like my ergodoxez layer 2 layout, which you can see below.

## ErgoDoxEZ layout
I currently type on an ErgoDoxEZ and really enjoy it. The keyboard layout I use can be found here: https://configure.ergodox-ez.com/layouts/qMW3/latest/0

## Credits
The mac file was created with [Ukelele V3](https://scripts.sil.org/ukelele) and should work on all versions of MacOS. The PC files where created a long time ago and I don't know if they still work, PRs welcome.

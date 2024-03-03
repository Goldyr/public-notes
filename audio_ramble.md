---
title: equalizer config
description: A reminder on how to configure my EQ for headphones
tags:
  - equalizer
  - music
---

# Equalizing headphones

## Ramble

This is like the 4th time I have to do a small research on how to do this, so im gonna keep some of my findings and instructions here. Im not an audio technician just someone who likes music

## Whats an EQ

An EQ is a tool to adjust the gain of various frequency ranges in the complete frequency range of a given output device. By configuring specifics ranges you get to listen more of the audio that somethings gets hidden by noise.

## How

The first step is downloading an application to use the EQ.

I chose the [EqualizerApo](https://sourceforge.net/projects/equalizerapo)
After installation by default you can find your app folder at "C:\Program Files\EqualizerAPO"

Run Configurator.exe an mark the headphones you are going to configure, you are gonna have to reboot your PC at this point.

Now you can open Editor.exe and start configuring your EQ.

I dont particulary like to configure this on my own, so what I did was find [this](https://github.com/jaakkopasanen/AutoEq) database of configurations based on headphone models, found my own and downloaded it.

I use the github search bar to find the GraphicEQ.txt for my specific headphone.

Using the Editor.exe gui you can click green plus sign and add a Graphic Equalizer you can try using a 15 or a 30 band but I tend to just use the variable one.

Paste the EQ.txt by editing the text on config.txt and assuming that you already configured your headphones correctly you can now turn on and off the EQ to test it and see whats to your liking.

I actually found that I like the same EQ that I use on my MX40 for most of my headphones

config.txt :

```
GraphicEQ: 20 -0.2; 21 -0.2; 22 -0.5; 23 -0.9; 24 -1.3; 26 -2.1; 27 -2.5; 29 -3.1; 30 -3.4; 32 -4; 34 -4.5; 36 -5; 38 -5.5; 40 -5.9; 43 -6.4; 45 -6.8; 48 -7.2; 50 -7.4; 53 -7.6; 56 -7.8; 59 -7.9; 63 -8; 66 -8.1; 70 -8.2; 74 -8.4; 78 -8.5; 83 -8.7; 87 -8.7; 92 -8.7; 97 -8.8; 103 -9; 109 -9.1; 115 -9.4; 121 -9.8; 128 -10.1; 136 -10.1; 143 -9.9; 151 -9.8; 160 -9.8; 169 -9.8; 178 -9.6; 188 -9.3; 199 -9; 210 -8.5; 222 -7.9; 235 -7.2; 248 -6.5; 262 -5.9; 277 -5.2; 292 -4.7; 309 -4.2; 326 -3.9; 345 -3.6; 364 -3.7; 385 -4; 406 -4.1; 429 -4.2; 453 -4.2; 479 -4.3; 506 -4.4; 534 -4.5; 565 -4.6; 596 -4.7; 630 -4.7; 665 -4.7; 703 -4.7; 743 -4.8; 784 -4.8; 829 -4.9; 875 -4.9; 924 -4.9; 977 -5; 1032 -5.2; 1090 -5.7; 1151 -6; 1216 -6.3; 1284 -6.5; 1357 -6.6; 1433 -6.6; 1514 -6.6; 1599 -6.5; 1689 -6.5; 1784 -6.2; 1885 -5.8; 1991 -5.5; 2103 -5.2; 2221 -5; 2347 -4.8; 2479 -4.6; 2618 -4.5; 2766 -4.4; 2921 -4.5; 3086 -4.6; 3260 -4.8; 3443 -4.9; 3637 -4.8; 3842 -5; 4058 -5.6; 4287 -6.4; 4528 -6.1; 4783 -4.7; 5052 -4.1; 5337 -4.7; 5637 -4.7; 5955 -4.5; 6290 -4.9; 6644 -5.7; 7018 -6.5; 7414 -6.9; 7831 -7.2; 8272 -7.7; 8738 -8.2; 9230 -8.8; 9749 -9.2; 10298 -9.5; 10878 -9.9; 11490 -10.3; 12137 -10.8; 12821 -11.2; 13543 -11.6; 14305 -12.1; 15110 -12.5; 15961 -13; 16860 -13.5; 17809 -13.9; 18812 -14.4; 19871 -14.9
```

### Apps and links:

https://github.com/jaakkopasanen/AutoEq

https://sourceforge.net/projects/equalizerapo

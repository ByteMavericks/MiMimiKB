# MiMimiKB - Amiga MisterFPGA Minimig Keyboard
A small project for Arduino Leonardo / clones to 
Standing on the shoulders of many!

// modified Jan 2021 from code released by BrainSlugs83 - https://github.com/BrainSlugs83/Amiga500-Keyboard/blob/main/AmigaKeyboard.ino
// https://forum.arduino.cc/index.php?topic=139358.90
// ByteMavericks: added reset code for MiSTerFGPA, and overloaded the HELP key to serve as F12, F11 and also Print screen
// HELP = F12 (OSD)
// Ctrl-HELP = F11
// Shift-HELP = PRINTSCREEN
// Useful MisterFPGA shortcuts:
// - Ctrl-LSHIFT-LALT-RALT= master reset (same as reset key)
// - Ctrl - Amiga- Amiga = CTRL LALT RALT = core reset
// Keyboard interface board with LED driver available - if interested drop me a line

If using a Pro Micro sourced from Amazon (search Pro Micro ATmega32U4 5V 16MHz as an example)and powering from USB then J1 needs bridging if you want 5V on the Pro Micro board, otherwise it goes through the regulator which means you won't be lighting up the Amiga keyboard...  

DO NOT CONNECT THE AMIGA LEDS DIRECTLY TO THE PRO MICRO!

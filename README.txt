This is all the changes that I made in order to make the TFT sheild to work with Arduino.

Foloseste antetul si ce e de setup in fiserul separat ca sa faci libraria sa mearga
Aststea sunt schimbate
#define YP A2  // must be an analog pin, use "An" notation!
#define XM A1  // must be an analog pin, use "An" notation!
#define YM 7   // can be a digital pin
#define XP 6   // can be a digital pin

#define  WHITE   0x0000
#define YELLOW    0x001F
#define GREEN     0xF800
#define RED   0x07E0
#define MAGENTA    0x07FF
#define CYAN 0xF81F
#define BLUE  0xFFE0
#define BLACK   0xFFFF

 tft.begin(0x8357); // SDFP5408

  tft.setRotation(2); // Need for the Mega, please changed for your choice or rotation initial

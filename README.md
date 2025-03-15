# Type-Drift

This project is inspired by the thirst to learn how to build things. Inspiration was derived from the wonderful community that is [r/ErgoMechKeyboards](https://www.reddit.com/r/ErgoMechKeyboards/)

Join me as we dive into the rabbit hole that is the custom keyboard and fish out the knowledge one gets by doing it all. In the project I plan to docuument every step and feature the best I could.

Features to include:
- Hardware:
  - [ ] Split with tenting
  - [ ] Type-C connection (to computer and between)
- Electrical:
  - [ ] Wireless and wired capabilities (type-C)
  - [ ] Rechargable Batteries
  - [ ] Small O-Led screen (layer monitoring and custom graphics)
- Software
  - [ ] Sleep when inactive (power saving)
  - [ ] disconnect battery when in wired mode
  

### How Does it Work?
The esp-32 c3 (my microcontroller of choice) is on each half

The two halves will communicate via ESP-NOW protocal when wireless

The rechargable cell will be 1050mAh (from Nokia); it's charge is checked and also put to sleep when inactive to preserve charge




Grandted mainstream firmwares lack support for the esp32, I will be writing custom firmware for the project (making it as simple and readable as possible)

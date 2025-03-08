# Type-Drift

This project is inspired by the thirst to learn how to build things. Inspiration was derived from the wonderful community that is [r/ErgoMechKeyboards](https://www.reddit.com/r/ErgoMechKeyboards/)

Join me as we dive into the rabbit hole that is the custom keyboard and fish out the knowledge one gets by doing it all. In the project I plan to docuument every step and feature the best I could.

Features to include:
- Hardware:
  - [ ] Split with tenting
- Electrical:
  - [ ] Wireless and wired capabilities (type-C)
  - [ ] Rechargable Batteries
- Software
  - [ ] Interchangable master and slave
  - [ ] Sleep when inactive


### How Does it Work?
The esp-32 c3 (microcontroller of choice) is on each half

The two halves will communicate via ESP-NOW protocal when wireless (though there's plans to add an option to run wired with C-cable)

The rechargable cell will be 1050mAh (from Nokia); it's charge is checked and also put to sleep when inactive to preserve charge

# CODESYS project #

    Projects that demonstrate Codesys programming skills 

- [CODESYS project](#tcpip-project)
  - [Main objectives](#main-objectives)
    - [YT film](#yt-film)
    - [Description](#description)

---

## Main objectives ##

One of University Project written in codesys

### YT film ###

[![Tanks---Codesys](https://i.ytimg.com/vi/NeWcSz-L5u8/maxresdefault.jpg?sqp=-oaymwEmCIAKENAF8quKqQMa8AEB-AH-CYAC0AWKAgwIABABGD8gVihlMA8=&rs=AOn4CLD2S6YpJuYzPJNy5OGNtA9to5A44g)](https://www.youtube.com/watch?v=NeWcSz-L5u8&ab)

### Description ###

- The device consists of a power source with a left and right flow inlet, the flow of which controls the respective pump M1 and M2. 
- Pump M1 runs only when external level sensor B01 is in low state (tank is empty) until B02 is checked. 
- Then pump M2  pumps fluid until sensor B03 is triggered. After filling tank the M3 motor mixing the fluid.
- After mixing M4 motor pumps fluid to second tank. 
- It has 2 level sensor. Activation the first indicator in the tank (B04) is required to start filling boxes. Second - B05 stops the M4 motor (flow to fill source)
- The containers move along the production line driven by the M5 motor. 
- The belt stops when the container is detected by the B06 photoelectric sensor. The pouring is carried out by overriding the actuator coil Y1.
- After the set time, the Y2 coil is overdriven, closing the tank. After the actuator (B07) returns, the M5 motor sets the belt in motion again.

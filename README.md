# README: Circuit Playground Projects

## Overview
This repository contains `.uf2` firmware files designed for the Adafruit Circuit Playground Express. Each file represents a unique project that showcases different functionalities of the board, such as capacitive touch sensing, sound generation, and LED animations.

---

## Files and Descriptions

### 1. **`circuitplayground-CapTouchCounter.uf2`**
   - **Purpose**: Demonstrates capacitive touch sensing with a counter.
   - **Features**:
     - Detects touch on designated pads.
     - Increments or decrements a counter based on touch input.
     - Visual or auditory feedback for each touch interaction.
   - **Use Case**: Great for interactive learning or creating touch-sensitive projects.

### 2. **`circuitplayground-TrumpetToolboxCScale.uf2`**
   - **Purpose**: Simulates a trumpet using the Circuit Playground Express.
   - **Features**:
     - Plays musical notes corresponding to the C scale.
     - Uses touch or button inputs to trigger specific notes.
     - Designed to be an educational tool for learning music or electronics.
   - **Use Case**: Perfect for music enthusiasts and teaching musical concepts interactively.

### 3. **`circuitplayground-blinky.uf2`**
   - **Purpose**: A simple LED animation project.
   - **Features**:
     - Lights up the onboard LEDs in various patterns.
     - Includes customizable blinking speeds and color sequences.
   - **Use Case**: Ideal for beginners learning LED programming or as a fun lighting effect.

---

## Prerequisites
- **Hardware**: Adafruit Circuit Playground Express  
- **Software**: No additional software is required; simply upload the `.uf2` files to the board.

---

## How to Use
1. **Prepare the Board**:
   - Connect the Circuit Playground Express to your computer using a USB cable.
2. **Enter Bootloader Mode**:
   - Press the **Reset** button on the board twice quickly. The LEDs will turn green, and a drive named `CIRCUITPY` or `CPLAYBOOT` will appear.
3. **Upload the Firmware**:
   - Drag and drop the desired `.uf2` file onto the `CPLAYBOOT` drive.
   - The board will reboot automatically, running the uploaded program.

---

## Customization
- Modify the source code if you wish to adapt the functionality of these projects.
- Use Adafruit’s CircuitPython or MakeCode to create or tweak your own `.uf2` files.

---

## Future Enhancements
- **CapTouchCounter**: Add visual feedback using LEDs for each touch input.  
- **TrumpetToolboxCScale**: Expand the range of notes or integrate a song-playing mode.  
- **Blinky**: Include additional LED animations or interactive controls for customization.

These projects provide a hands-on introduction to the capabilities of the Circuit Playground Express, making them excellent for both learning and creative experimentation.

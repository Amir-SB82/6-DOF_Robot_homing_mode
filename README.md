# Homing mode

## Overview

**Homing mode** Controlling parallel robots is a very important issue for laboratory and industrial robots.Homing mode is used to find the zero position of the robot.This code has different methods that you can use to check the document.

---

## Features

- 🚀 **Different methods**: You can implement different methods on the code
- 🌐 **Offset**: You can direct the motors to any position you want with the offset command

---

## Getting Started

To set up the project locally, follow these steps.

### Prerequisites
- **STM32CubeIDE**: Ensure you have [STM32CubeIDE version 1.13.0(recommended)]
- **CANopen stack**: you need this stack for your communication 
i have used this stack in the code, you can also download and including it from [github website](https://github.com/CANopenNode/CANopenNode)

### Run code
1. **open new project**: 
    go to file --> new --> STM32 project
2. **add the stack**: 
    Go to project --> properties --> paths and symbols --> includs --> add --> file systrm
    Then choose CANopenNode and core/CANopenNode_STM32
    Ensure there is CANopenNode in the source location(if this file does not exist in the source location, first apply and close and build the project, then come to the source location again.)
3. **run**
    now, you can use this mode by upload the code to micro   

## License
- you can download
 *CANopenNode* document from this link(https://drive.google.com/file/d/1Lg_B5r14P_CGMcFEsO6PIyp6nOz_elqh/view?usp=drive_link)

## Contact
- **Email**: bestbs.1382@gmail.com
- **Github**: Amir-SB82
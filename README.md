# CODESYS Elevator Controller

A modular PLC elevator controller developed in CODESYS using Structured Text (IEC 61131-3).

The project simulates a 3-floor elevator and demonstrates common PLC programming concepts such as state machines, Function Blocks, HMI visualization and modular software design.

## Features

- State machine (ElevatorState)
- Motor controller
- Door controller
- Request manager
- Emergency stop
- Overload detection
- HMI visualization
- Git version control

## Architecture

The application is divided into separate Function Blocks:

- FB_Elevator – Main state machine
- FB_MotorControl – Controls elevator movement
- FB_DoorControl – Controls the door
- FB_RequestManager – Handles floor requests

## Development Workflow

- Feature development on personal branch
- Merge into 'develop'
- Stable releases merged into 'main'

## Technologies

- CODESYS V3.5
- Structured Text (IEC 61131-3)
- Git
- GitHub

## Project Status

Current release: **v1.0**

Planned future improvements:

- Hall call buttons
- Request queue
- Motor feedback timeout
- Door timeout
- Advanced fault handling

## HMI

![Elevator HMI](Images/V%201.0%20Elevator%20HMI.png)

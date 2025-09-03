# MacHaik-Houston-ET2

This repository contains the control scripts, configuration files, and documentation for a divisble multi-purpose room and multiple video conferencing rooms deployed at the client's Houston ET2 Location.

---

## System Overview

**Room Type**: Multi-Purpose 2-Way Divisible Rooom (East & West)
 **Purpose**: Video conferencing and BYOD presentation  
**Control Processor**: Q-SYS Core 510i
**User Interface**: 4x TSC-101-G3 (2x per Side)
**Display**: 2x 98" Samsung : 2x 110" Primeview (2x per Side)
**Sources**: 4x HDMI Inputs (2x per Side)
**Audio**: 8 x James Speakers : 2x Shure MXA-920 : 2x Shure MXW2 : 2x Shure MX1  
**Camera**: 3x Aver PTZ310 : 2x Aver TR315 (3x in East & 2x in West)
**Network**: Client VLAN (Link to MacHaik Kirkwood Q-Sys Core)
**Platform**: QSC

---

# AV System Programming Scope: Description

These rooms are designed for BYOD presentation and video conferencing utilizing the Q-Sys platform for audio, video and control. 
The rooms will feature 110" displays, multiple PTZ cameras, ceiling beamforming microphones, wireless microphones and ceiling speakers to ensure comprehensive audio and video coverage. 
Wall-mounted control panels at the front and side of the multi-purpose rooms offer AV system controls at multiple locations for flexibility in different room configurations.

## QSys System Control – Control Requirements

- Custom programming for Multi-Purpose 2-Way Divisible Rooom QSys AV system control
  - BYOD/BYOM rooms
  - Auto source detection upon laptop HDMI and USB connections
        -  Front Wall Plates / Rear Wall Plates
  -  Camera Selection:
        -  Presenter(s) and Audience(s)
        -  All 5 cameras selectable in combined
        -  Camera Presets and Auto-Framing for Audience and Presenter
  - Video Conference Meeting controls will be done through video conference application on the user’s laptop
  - Display Controls (4 Displays)
        -  Displays On/Off
        -  Automatic power control from displays HDMI auto sensing
  - AV system schedule (TBD)
        -  Auto-Shut Down
- Audio DSP programming and Dante configuration

## TSC-101 User Interface – Control Requirements

- Custom programming for Apple IPAD AV/Room QSys controls
  -  Room combine controls (Individual and combined), Display control, Source selection, mic control, volume control, camera control (Auto-Framing), AV system schedule

---

## Repository Structure

```
/docs/           → user training etc.. 
/qsys/           → Q-SYS design file, JSON configs
/media/          → Touch panel screenshots, diagrams etc ... 
```

---

## Troubleshooting Tips

- Use Q-SYS Core logs 
- Check This and That

---

## License & Ownership

All scripts and designs are the property of ieSmartSystems.  
Do not redistribute or share outside of client or internal teams.

---

## Maintainers

- Primary: hnash@iesmartsystems.com    
- Backup: jdemille@iesmartsystems.com



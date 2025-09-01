📁 ECG Front-End Circuit Design – Altium-Based PCB Project

## Overview
This project implements a fully custom ECG signal acquisition front-end on a multi-stage analog PCB, designed using Altium Designer. The system includes instrumentation amplification, active bandpass filtering, level shifting, and programmable gain control.

## Demo

![ECG_PCB](ECG_PCB.png)


## Key Features

Created flipped custom footprint for STX-3000 audio jack based on bottom-view datasheet

Designed and routed LT1920 instrumentation amplifier and MCP4132 digital rheostat circuit

Shared op-amp (TL072) used for both bandpass filtering and level shifting with precise ±3.3V rail control

PCB layout optimized for analog signal flow and connectivity to the Nucleo-F303K8

## Technologies

Altium Designer, Analog Circuit Design, PCB Layout, ECG Signal Acquisition

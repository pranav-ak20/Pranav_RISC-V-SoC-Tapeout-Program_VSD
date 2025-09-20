# 🚀 Week 0: VLSI System Design (VSD) Program Foundation & Tool Setup
This repository contains documentation for setting up the necessary tools for the VSD RISC-V Tapeout Program. The guide covers the installation of Yosys, Icarus Verilog (iverilog), and GTKWave.
## Table of Contents
1. Introduction

2. Prerequisites

3. Installation Steps

   . Icarus Verilog (iverilog)

   . GTKWave

   . Yosys

4. Conclusion
## Introduction
This guide provides a step-by-step process for installing the open-source EDA tools required for hardware design and verification. These tools form a basic toolchain for synthesis, simulation, and waveform viewing.
   ### Icarus Verilog (iverilog): A Verilog simulation and synthesis tool.
   ### GTKWave: A fully featured GTK+ based wave viewer.
   ### Yosys: A framework for Verilog RTL synthesis.

## Prerequisites
This guide assumes you are using a Debian-based Linux distribution (like Ubuntu). Before starting, ensure your system is up-to-date.
``` sudo apt update
   sudo apt upgrade -y ```
## Installation Steps
Follow the sections below to install each tool.

### 1. Icarus Verilog (iverilog)
Icarus Verilog is a Verilog compiler that generates a simulation.
### Installation Command:
``` sudo apt install iverilog ```


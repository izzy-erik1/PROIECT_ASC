# PROIECT_ASC

# 8086 Assembly Project – Byte Processing

## Overview
This project is written in 8086 Assembly (TASM/TLINK) and processes a sequence
of 8–16 bytes entered by the user in hexadecimal format.

## Features
- Reads user input using DOS interrupt 21h (AH=0Ah)
- Converts ASCII hex values into binary bytes
- Sorts the byte array in descending order
- Rotates each byte based on its lowest two bits
- Uses only 8086-compatible instructions

## Input Format
Example: 3F 7A 12 5C 20 0A FF 01


- Each byte is written as two hex digits
- Bytes are separated by spaces
- Press ENTER to finish input

## Requirements
- TASM
- TLINK
- DOSBox

## Build & Run
tasm project.asm
tlink project.obj
project.exe

#Team G-1
-Erkalo, Israel T.


# Automatically Start Firefox Application Through Windows Batch Script

## Introduction
- In the Script Two Batch Script File
- One for Start Firefox Application
- Second for Stop Firefox Application

### Features
- Start & Stop Application Work on Multiple Application
- It Also Helps in to Kill Application
- Improves time efficiency
- Required Less Knowledge to Run & Execute

## Installation
- Just, Clone this repository - 
````bash 
https://github.com/SLoharkar/Auto-Start-Firefox-Application.git
````
- Download Specific File of Firefox Start or Firefox Stop

- Copy Firefox Start Code
````bash
@echo off
start /min firefox.exe
````
- Copy Firefox Stop Code
````bash
@echo off
taskkill /IM firefox.exe /F
````

## Dependencies
- `Windows OS`

> Supported Platform : **`Windows 7,8,10 & 11`**, **`Microsoft Server 2016 & 2019`**

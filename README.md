![demo](https://github.com/h2337/core86/blob/eca2be73c33b42aee1d3085ee080016fbd4f5f9d/screenshot.png?raw=true)

(The screenshot is not representative of the actual current state of the project. The MDA window does not exist yet but other panels displayed mostly work. Some MDA work has been done but it's not finished yet.)

## Overview

core86 is a *WORK-IN-PROGRESS* 8086 IBM PC emulator that aims to run MS/DOS as the initial goal.

## Run

Run emulator by executing `cargo run -- ./path/to/boot/floppy.img`

Run the GUI by executing `cd gui && python3 -m venv ./venv && source ./venv/bin/activate && pip3 install -r requirements.txt && python3 main.py`

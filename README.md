# Wasp-OS Pomodoro App

A customizable Pomodoro timer application for [wasp-os](https://github.com/wasp-os/wasp-os) running on [PineTime](https://pine64.org/devices/pinetime/) smartwatches.

## Features

- Multiple timer presets with comma-separated durations
- Configurable vibration patterns
- Persistent settings between sessions
- Swipe gestures for quick preset switching
- Adjustable vibration count (1-15)
- Random vibration patterns for better attention grabbing
- Auto-stop after 99 cycles to prevent battery drain
- Screen-off support for background operation

## Usage

### Basic Controls
- **Swipe Left/Right**: Switch between timer presets
- **Swipe Up/Down**: Adjust number of vibrations
- **Touch Numbers**: Input custom timer duration
- **"Then" Button**: Add multiple timers (separated by commas)
- **"Go" Button**: Start the timer sequence
- **"Del" Button**: Remove last input
- **"+1" Button**: Add 1 minute to current timer (while running)
- **"STOP" Button**: Stop current timer sequence

### Timer Format
Enter times in minutes, separated by commas for sequential timers.
Example: "25,5" creates a 25-minute work period followed by a 5-minute break.

### Default Presets
- 1 minute, 10 minutes
- 10 minutes, 1 minute
- 20 minutes, 5 minutes

## Installation

1. Ensure you have wasp-os installed on your PineTime
2. Copy `Pomodoro.py` to your wasp-os apps directory
3. Reboot your watch or reload the app launcher

## Requirements

- PineTime smartwatch
- wasp-os installed
- MicroPython support

## License

LGPL-3.0-or-later

## Credits

Originally forked from timer.py by github user thiswillbeyourgithub

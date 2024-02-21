# Rust Audio Tuner Plugin

A simple guitar/bass tuner VST plugin written in Rust. 

![Tuner GUI](images/tuner_gui.png)

## Overview  

This plugin analyzes an incoming audio signal to detect played notes and determine if they are in tune. It displays the detected note name and cent deviation for tuning purposes.

The core pitch detection and note mapping logic is implemented in Rust for performance and portability across plugin formats. The GUI frontend utilizes the Iced library.  

## Features

- Detects pitch of incoming monophonic audio
- Displays nearest note name (e.g. D, F♯) 
- Calculates cent offset from perfect tuning
- Highly responsive FFT analysis
- Compatible with VST2 and VST3 hosts  

## License  

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for more details.
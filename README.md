# Laser Audio Visualizer Project

This project I built is a hands-on audio detection system that uses a laser pointer, a photodiode, and an op-amp to pick up sound vibrations from a surface. When sound hits something like stretched plastic wrap or a balloon, it causes tiny movements in the surface. The laser reflects off it and onto a photodiode, which converts those movements into an electrical signal you can hear or analyze.

## What This Project Does
It turns sound vibrations into an electrical signal using light — no microphones required. It's a cool way to visualize how vibrations carry audio and how you can detect them with basic analog components.

## How It Works
- A laser is pointed at a stretched surface (like a balloon over a cup).
- The surface vibrates when sound hits it.
- The reflected laser beam moves slightly with each vibration.
- A photodiode picks up the laser movement.
- A transimpedance amplifier (using an LM833N op-amp) turns that light change into a voltage signal.
- The signal is sent out through a 3.5mm audio jack — you can plug in headphones or an oscilloscope to hear or see it.

## Components Used
- LM833N op-amp
- Photodiode
- 0.1 µF and 10 µF capacitors
- 10kΩ and 100kΩ resistors
- Breadboard + jumper wires
- 3.5mm audio jack
- Laser pointer (red or green)
- Balloon or plastic wrap
- Power source (e.g., 9V battery)
- A cup to wrap the balloon rubber on top

## Things You Can Improve or Explore
- Use an Arduino to digitize and visualize the output
- Add a better preamp stage or filtering
- Try bouncing the laser off different materials
- Explore different photodiodes for better response

## Coming Soon
- Circuit diagram
- Breadboard photos
- Demo video

## Built By
Leo Issa Ghoulian - Bachelor of Science in Computer Engineering

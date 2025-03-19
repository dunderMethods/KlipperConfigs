DunderMethods Klipper Config Files 
3.19.2025 - DunderMethods
-----------------------------------

These are a personal backup of the Klipper config files for all of my 3D printers.
I'm sharing them because it took quite a while for me to properly configure these machines.
I hope someone finds these helpful!

Machines: (Mods)
- Creality Ender3 (4.2.7 Silent Main Board, MicroSwiss Direct Drive)
- Creality CR10-V2 (E3D V6 Hot End, BL Touch)
- Creality Ender6
- OpenBeam Kossel Pro (Azteeg X5 Mini V3)
- OpenBeam Mini Kossel Pro (Azteeg X5 Mini V3)

Note: Each of these configs are tailored to my unique machines. Each machine has its own directory with a readme.md file. I've tried to call out any modifications installed on my machines, as your machine may need to be configured differently if you are using an unmodified machine. Ender6-2 should be a stock Ender6 configuration, everything else has a custom hot end or other mods which may have different X,Y,Z extruder offsets or a different thermistor from the original stock configuration. 

Note: If you see "mcu 'rpi': Unable to connect" you may need to remove the following sections from the printer.cfg file (if you are not using input shaper.)
- [mpu9250]
- [mcu rpi]
- [resonance_tester]
- [input_shaper]

I am providing these config files as a reference for others to get up and running with Klipper. These configs are pulled directly from my working machines. Use these files at your own risk!
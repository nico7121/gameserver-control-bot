# gameserver-control-bot
A lightweight, energy efficient, embedded Solution to control generic Gameservers via Raspberry Pi GPIO and SSH

-- Disclaimer: --
  I am not an experienced developer, and this is not a project meant to be copied and run "as is", since I am mainly doing it to try things out and taylor Hardware to my own needs, and it might never reach an acceptable development state. However, if you find anything useful, or want to use it for your own needs, I think that is great, and you can do whatever you want with it :)

  ## Concept
  Using an affordable PC to run personal gameservers, f.e. Minecraft, comes with a simple problem: How to boot it up? How to Shut it down? What if I cannot use Wake-On-Lan? How do we switch the program it runs? How to save running costs?
  It is simple: you use a different device to manage it

  Requirements:
  Raspberry Pi and Motherboard GPIO, and a simple perfboard Circuit with, optionally, Buttons, Status-LEDs, and an Opto-Isolator or transistor to allow the device to detect Motherboard Power state and toggle the Power-On Pin.
  Wifi or, optimally, LAN Network connection to access the devices and allow them to access each other via SSH
  WiP: establish an SSH connection via the USB ports, wich might allow WakeOnUSB, SSH via USB, and lower level access to the machine if needed.

  

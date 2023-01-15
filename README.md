Pico_IRCam
==========
A tiny Infra-Red camera based around the Raspberry Pi Pico and the MLX90640

### Installation instructions for the Raspberry Pi Pico:

1. Install CircuitPython on the Pico

    https://circuitpython.org/board/raspberry_pi_pico/
    
    Note: This project used vesion 7.3.3
    

2. Run git clone to clone this folder somewhere...

   git clone https://github.com/astro-designs/Pico-IRCam.git

3. Copy the contents of the *pico_files* folder to the Rasppberry Pi Pico

    Note: I used Thonny 3.3.10 for Windows to manage the files on the Pico and edit / develop the code.
    
    https://thonny.org
    


### About this project

This project re-uses code published by others with some minor tweaks

* David Glaude:

    Using David's mlx90640_240x240.py and notes on his github page as a starting point
    https://github.com/dglaude/circuitpython_phat_on_pico.git

* Adafruit

    Adafruit CircuitPython libraries for the Raspberry Pi Pico, including:
        adafruit_display_text
        adafruit_mlx90640.py
        adafruit_st7789.py
        simpleio.py

* Mark Cantrill

    Adapted David Glaude's code to work with the for the Waveshare 1.3" 240x240 display for Raspberry Pi Pico
    Adapted David Glaude's code to save the bitmap image to the pico when the joystick button is pressed

    Future work:
    
    * Extract mininim, maximum and average temperature data from the data
    * Use the joystick to change view from the bitmap to display min/max/average
    * Add other display options
# Breadboard Boost Regulator

This is a small boost regulator circuit designed for use on a breadboard. It can be fully manufacturered at JLCPCB using the gerbers.zip BOM.csv and mount.csv files. The design here produces 12.5V from 3V to 9V input. It can switch around one amp, so the output current depends on the input voltage (e.g. at 9V input, it can produce 600mA current, but at 3V input, only around 70mA due to inefficiencies). The board has 2 outputs, both the same, as the minimum board size for PCBA from JLCPCB is 20mm x 20mm, plus I just wanted two outputs :) The schematic shows the formular to change the output voltage from the default. I used 2 resistors on one side of the divider to allow more flexibility when choosing parts. I have used "basic parts" from the JLC library where possible, to reduce cost. The cost for 20 boards is currently around £26 + shipping! Obviously the cost per board reduces as the quantity increases.

![Render](./images/board2.png?raw=true)

![Render](./images/schematic.png?raw=true)

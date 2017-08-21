# About
This is the DSP/control board.  

Hardware desig files are here, [firmware](firmware/) is
in subfolder.

# Technical
- Audio source
  - Analog stereo input with 3.5 mm jack + good ADC
  - USB audio
    - With STM32 USB interface?
  - Bluetooth audio
    - [Bluegiga WT32i](https://www.silabs.com/products/wireless/bluetooth/bluetooth-classic-modules/wt32i-bluetooth-audio-module)

- STM32H7 as DSP
  - Should handle the digital inputs
  - Acts as audio crossover for high and middle/low tone (BiQuad IIRs)
  - Could do some equalizing etc...
  - For analog volume control IC
  - Some runtime config of DSP
  - Remote control IR/radio?
  - Switch on delay to charge caps
  - Temperature control

- DAC for feeding the class D amps
  - WM8804/WM8524 ???
  - Volume control
    - [TI PGA2311](http://www.ti.com/lit/ds/symlink/pga2311.pdf)


[https://www.hobbyhifiladen.de/aktivmodule-dsp/sure-electronics/?p=4](https://www.hobbyhifiladen.de/aktivmodule-dsp/sure-electronics/?p=4)

# Tools
The board should be designed with KiCAD.

# Notes


# blink-1-Recording-Light

Use a [blink(1) USB notification light](https://blink1.thingm.com) with the built in "Recording Light" control surface bundle in [Logic Pro](https://www.apple.com/logic-pro/). 

### Instructions

1. Enable the "IAC" Midi port in macOS.
2. Start "USB Recording Light" and click its icon in the menu bar. Choose "IAC1" as MIDI input and output ports.
3. Start Logic Pro and add the "Recording Light" control surface. Choose the IAC output and input in the configuration window
4. Record something and try not to get distracted by the red glowing light  

#### How do I enable the IAC midi port in macOS?

- Open "Audio Midi Setup" (just do a spotlight search for it, and it will show up).
- The IAC virtual midi device is disabled (greyed out) by default. To enable it, just double click it in the MIDI view and select the "Enable" checkbox.

#### How do I add the "Recording Light" control surface in Logic Pro?

- In the "Logic Pro" menu, choose "Control Surfaces" and "Setup…"
- Press the "New" combo button and select "Install…"
- From the list, choose "Recording Light" (at the top of the list) and click "Add".

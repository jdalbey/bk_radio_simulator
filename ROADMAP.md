## ROADMAP

- ~~Press the [SCN] button to start channel scanning. The flashing SCN led will appear on the display. Scan operation occurs only while the radio is not transmitting.~~
- When the unstopped channel selector is rotated past the highest (16th)
  channel, the radio will emit a beep and remain on the highest
  channel. When rotated past the lowest (1st) channel, the radio
  will emit a beep and remain on the lowest channel.
- Next feature is implement priority channel. The radio can designate one       
    channel to have priority, that is, any traffic on that channel has priority   
    and will override any other channel that might be scanning. Make the default  
    priority channel "SQF CH4". To change the priority channel the user takes     
    these steps: Toggle SCN and PRI function buttons off. Turn channel knob to    
    desired priority channel. Click PRI on the handset keypad. The PR led         
    illuminates in the display. Toggle SCN and PRI buttons on. 
- Press the [PRI] button to start or stop priority scanning. The PR led and the flashing SCN led appear on the display. 
- When Priority Scan is on, the PR led illuminates, and the display flashes SCN led. If a message is received on a priority channel, the Priority indicator illuminates. 
- CHANGE THE SCAN LIST
  1. Turn Scan and Priority Scan buttons off. (The pips and leds go off.)
  2. Select a channel to be added or removed from the scan list by turning the Channel Selector knob. If the channel is already on the scan list, SCN appears in the display.
  3. **Press and hold the [SCN] button for more than 1 second** to
    toggle the channel on or off the scan list.
- For scenario configuration, the script will need to specifiy which channel an audio clip is being received on, so the radio knows whether it should light up the priority indicator. 




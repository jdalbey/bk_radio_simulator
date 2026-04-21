## ROADMAP

- ~~Press the [SCN] button to start channel scanning. The flashing SCN led will appear on the display. Scan operation occurs only while the radio is not transmitting.~~
- When the unstopped channel selector is rotated past the highest (16th)
  channel, the radio will emit a beep and remain on the highest
  channel. When rotated past the lowest (1st) channel, the radio
  will emit a beep and remain on the lowest channel.
- Next feature is implement priority scan. Priority Scan enables the radio to receive on any channel while monitoring for a message on the designated priority channel. Priority Scan operates only while the radio is not transmitting and can be used in combination with scan operation. Press the [PRI] button to start or stop priority scanning. When Priority Scan is on, the PR led illuminates, and the display flashes SCN. If a message is received on a priority channel, the Priority indicator illuminates, and the radio receiver locks onto that channel for the duration of the transmission.  "Locks on" means the audio is played for the priority channel despite if the channel selector knob selects a different channel. 
- Make the default priority channel "SQF CH4" and treat the audio mp3 playback as being received on the priority channel. To change the priority channel the user takes  these steps: Toggle SCN and PRI function buttons off. Turn channel knob to desired priority channel. Click PRI on the handset keypad OR Press and hold the [PRI] button for more than 1 second. A short beep sounds and PR led appears in the display, indicating that the displayed channel is now the priority channel. Toggle SCN and PRI buttons on. 
- CHANGE THE SCAN LIST
  1. Turn Scan and Priority Scan buttons off. (The pips and leds go off.)
  2. Select a channel to be added or removed from the scan list by turning the Channel Selector knob. If the channel is already on the scan list, SCN appears in the display.
  3. **Press and hold the [SCN] button for more than 1 second** to
    toggle the channel on or off the scan list.
- For scenario configuration, the script will need to specifiy which channel an audio clip is being received on, so the radio knows whether it should light up the priority indicator. 




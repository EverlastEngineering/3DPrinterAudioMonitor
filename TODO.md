Here's an informal To Do list for this monitoring system.

Housekeeping items:
1. Prompt for initial IP address, show pic of where to get it?
1. Store IP for machine in local storage / cookie
1. Get it working through a firewall with port forwarding turned on (WSS)
1. Look if there are better ways of getting the audio to play automatically
1. Audio test button
1. Select from a range of audio
1. Get this to work on mobile browsers
1. Graph temp over time with chart.js
1. Handle different firmware's outputs, would require other testers

Functionality:
1. Show connecting / failure, reconnect button
1. Show time since last information, option to alert if no information over x amount of time
1. Show bed temperature and target
1. Handle end of print better, sometimes causes false positives and scares the shit out of you
1. Selectable tolerance temp (spinner, real time, store in local storage)

Future ideas, not likely to implement:
1. AWS Lambda with email / sms capability on node
1. A second IP with webcam support to show video of print

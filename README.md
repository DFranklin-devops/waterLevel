# waterLevel
Use raspberry pi to detect water spill / leakage from household appliances

Requirements:
- Multiple sensors (or rope type sensors) that can be triggered
- Does not need to run on battery, can be AC powered
- Upon event detection, actions are:
  - Close solid-state-activated main valve to house
  - Sound piezo buzzer, illuminate alarm light
  - Send SMS/email (maybe VOIP call with recorded message)
- Must have configuration ability (web, mobile app, or small LCD screen) for event detection parameters
Research: https://www.raspberrypi.org/forums/viewtopic.php?t=229903

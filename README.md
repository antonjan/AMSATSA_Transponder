# AMSATSA_Transponder (1U cube)
This repository is to hold the AMSATSA Cubesat source code.

This repository will holed the AMSATSA SDR Cubesat transponder details.

1) Transponder will be a SDR receiver and SDR transmitter.
2) Uplink frequency will be 70cm.
3) Downlink frequency is tsill to be desided 2M or 1.2Ghz
4) Transponder will need to be able to run from 1.2W 5v or 3.3V (preverd 3.3 volt)
5) Transponder will need to have a command controle recever to mange the transponder and battery usage and antenna deplyment. (70cm frquency)
6) Transponder will need to send telemetry with onboard configeration data and power and transponder status details.
6.1) Antenna deploiment detail.
6.2) Battery chanrge status.
6.3) Solar panel status
6.4) Beacon ID call sign.
6.5) Modulation BPSK 1k2 not continuous interval 10 Seconds ( Leeding tone 1S to alowe for RX pll to lock before sending data)
6.6) RX alc levels.
6.7) TX power levels
6.8) Temprature of Battery, Transponder and OBC.
7) Estimated deplyment altitude 650Km (LEO)

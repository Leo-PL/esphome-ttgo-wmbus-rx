# TTGO WMBus receiver

An ESPHome configuration for TTGO T-Lora32 V2.1-1.6 and T-Beam v0.7 for receiving WMBus meters as sensors.

Based on [WMBUS-Reader](https://github.com/MariuszWoszczynski/WMBUS-reader)

Sensors configuration matches my home, remember to adjust your types and fill out secrets.yaml before using.
Display support is WIP, but the hardware itself works.
Display is optional on T-Beam, but a common model is included as an example.
This should be easily adaptable to other T-Beam or T-Lora variants just by changing the hardware definition.

---
title: Renson
description: Instructions on how to integrate Renson Endura Delta sensors into Home Assistant.
ha_category:
  - Sensor
ha_release: 2023.7
ha_iot_class: Local Poll
ha_config_flow: true
ha_codeowners:
  - '@jimmyd-be'
ha_domain: renson
ha_platforms:
  - sensor
---

The Renson integration pulls in data from the Renson Endura delta device. Most of the sensors that can be monitored from inside the Android/iOS application can be monitored with this integration.


{% include integrations/config_flow.md %}
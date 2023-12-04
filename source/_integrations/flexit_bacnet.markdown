---
title: Flexit BACnet
description: Instructions on how to integrate Flexit air handling unit into Home Assistant.
ha_category:
  - Climate
ha_release: 2024.1
ha_iot_class: Local Polling
ha_domain: flexit_bacnet
ha_platforms:
  - climate
ha_integration_type: integration
---

Integrates [Flexit](https://www.flexit.no/en/) Nordic series air handling unit into Home Assistant.

## Prerequisites

To configure the integration, you need to obtain the IP address and Device ID for the unit.

1. Open the Flexit Go app on your mobile.
2. On the main screen, select the **Find product** button.
3. Select your device and select **Connect**.
4. Enter the installer code (default: 1000) and select **Login**.
5. Go to **More** > **Installer** > **Communication**  > **BACnet settings**.
6. Note down the **IP address** and **Device ID**.

{% include integrations/config_flow.md %}

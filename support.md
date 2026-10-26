---
title: SSMLink Support
---

# SSMLink Support

SSMLink reads live data and trouble codes from 1990–1996 Subaru engine computers (ECUs)
through the yellow Select Monitor connector, using a small ESP32 Bluetooth adapter. It's made
for Subaru-powered conversions such as EJ22 swaps in VW Vanagons, and works on stock 1990s
Legacys, Imprezas and SVXs too.

## Contact

Questions, bug reports and adapter build help: **[nickma@gmail.com](mailto:nickma@gmail.com)**.
You can also send feedback from the About screen in the app (Parameters › About SSMLink).

## Try it without a car

Open the app and tap **Try the demo ECU** on the Live tab. A simulated 1993–94 EJ22 runs a
one-minute drive loop, so every screen works without the adapter.

## Common questions

**The app says "No adapter connected".** Plug the adapter into the yellow diagnostic connector,
switch the ignition on (engine running or not), and tap Connect. The adapter needs 12 V from
the connector.

**Connected, but no reply from the ECU.** Check the ignition is on and the plug is fully
seated. The green test-mode and black read-memory connectors should be apart.

**Values look wrong.** Read the ROM ID on the Live tab so SSMLink picks the matching address
map. If your ROM has no exact map, compare RPM and coolant against your gauges.

**Values update slowly.** A 1990s ECU answers about five values per second. Select fewer
parameters on the Parameters tab for faster updates.

**mph or km/h, °F or °C?** Tap the gear on the Live tab and choose US or Metric units.

**Where are my recordings?** On iPhone in the Files app (On My iPhone › SSMLink); on Android in
Downloads › SSMLink. Both can be shared from the Live tab.

## Privacy

SSMLink collects no personal data. See the [privacy policy](./).

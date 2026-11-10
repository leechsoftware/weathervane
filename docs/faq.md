---
title: Questions and answers
---

# Questions and answers

## About the app

**Where do I download it?**
Only from the App Store: [apps.apple.com/app/id6812456607](https://apps.apple.com/app/id6812456607).
It is listed there as Dashboard for ECOWITT Weather. This repository has no download.

**Is it really free?**
Yes. There are no ads, no subscription and no account with us.

**Is the source code available?**
No. The app is closed source. This repository is for documentation and for reporting
problems.

**Is this an official Ecowitt app?**
No. Weathervane is independently developed and is not affiliated with or endorsed by Ecowitt.

**Can I try it without a weather station?**
Yes. Choose **Just show me a sample dashboard** on the first screen. See
[Getting started](getting-started.md).

**Is there a Mac version?**
Yes, from the same App Store listing. Its documentation is at
[leechsoftware/weathervane-mac](https://github.com/leechsoftware/weathervane-mac).

**Is there an Android or Windows version?**
No.

## Connecting

**The app cannot find my gateway on Wi-Fi.**
- The phone must be on the same network as the gateway, not on mobile data or a guest network.
- Allow the app to find devices on your local network when iOS asks, or turn it on in
  Settings > Privacy & Security > Local Network.
- Turn off any VPN or firewall app and try again.
- The original GW1000 and some consoles cannot be read over Wi-Fi. Use Ecowitt Cloud for them.

**Readings stop when I leave home.**
A station connected over Wi-Fi can only be read on that network. Switch it to Ecowitt Cloud
in the Data Source screen to read it from anywhere.

**Cloud readings are a few minutes old.**
Ecowitt limits how often an account may ask for readings, and stations upload on their own
schedule. A few minutes is normal for the cloud. Over Wi-Fi, readings arrive about once a
minute.

**I see a "rate limited" message.**
Ecowitt has asked the app to slow down, usually because several apps or devices are using
the same account. The app waits and carries on by itself.

**A sensor is missing.**
Check that it appears in Ecowitt's own app first. If it does, use **Contact us** in the
About screen so we can see what your device reports.

## Readings

**The forecast high is different from another app's.**
Weathervane adjusts the forecast's highs and lows to how your own station has read over the
last month. Tap a day to see the forecast's own figures beside the adjusted ones, or turn the
adjustment off in Settings.

**The colours on the wind compass changed from yesterday.**
The heat map's colours are relative to each day's own wind, so the same colour can mean a
different speed on a different day. The figures beside the compass give the speeds.

**Rain totals differ from Ecowitt's app.**
Check which rain gauge is set as the main one if your station has two, and whether your
weather day starts at midnight or 9 am.

## Alerts

**Alerts arrive late on my iPhone.**
With the app closed, iOS decides when it may check your station. See [Alerts](alerts.md).

## Still stuck?

[Open an issue](https://github.com/leechsoftware/weathervane/issues/new/choose) or use
**Contact us** in the app. Please never post your Ecowitt keys or password.

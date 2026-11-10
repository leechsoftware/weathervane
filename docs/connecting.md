---
title: Connecting your station
---

# Connecting your station

Weathervane reads a station in one of two ways. Both show the same dashboard.

| | Ecowitt Cloud | Your own Wi-Fi |
|---|---|---|
| Works away from home | Yes | No |
| Needs an Ecowitt account | Yes | No |
| Reaches every station on your account | Yes | Only devices on the same network |
| Apple Watch can read the station by itself | Yes | No, it relies on the iPhone |
| Longest history | Up to three years | What the app has collected, plus the gateway's memory card where it has one |

If you are not sure, choose **Ecowitt Cloud**.

## Ecowitt Cloud

Your station already uploads to ecowitt.net if you set it up with Ecowitt's own app. To read
it, Weathervane needs two keys from your Ecowitt account: an application key and an API key.

You can get them in two ways:

1. **Sign in from the app.** Weathervane opens Ecowitt's own sign-in page and sets the keys
   up for you.
2. **Paste them yourself.** Create the keys on ecowitt.net under your account's private
   centre, then paste them into the app.

The keys are stored in your device's Keychain. Your Ecowitt password is not kept.

Ecowitt limits how often an account may ask for readings. Weathervane paces itself to stay
inside that limit, so cloud readings arrive every few minutes, not every few seconds.

## Your own Wi-Fi

Choose **Find devices on this Wi-Fi network** and the app looks for gateways and consoles on
the network your phone or Mac is on. You can also type a device's address.

- On iPhone and iPad, iOS asks for permission to find devices on your local network. The app
  cannot find a gateway without it.
- Readings come straight from the gateway, about once a minute.
- If your router gives the gateway a new address, the app recognises it and keeps its history.
- A VPN or firewall app can stop the phone seeing the gateway.

Some devices cannot be read this way and need Ecowitt Cloud. The app tells you when you add
one. They include the original GW1000 and consoles such as the HP2560 and HP2564. See
[Supported hardware](supported-hardware.md).

## Using both

A station can be switched between the two in the app's Data Source screen. Its history,
records and alert settings stay with it.

## A gateway with no weather station

A gateway that only has add-on sensors, such as soil or temperature sensors, gets its own
dashboard built around those sensors. Forecast, radar and moon cards are off for it to begin
with and can be turned on in Settings.

## Next

- [Supported hardware](supported-hardware.md)
- [Questions and answers](faq.md)

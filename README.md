# Dusk

A free macOS app that makes your Mac's brightness keys work on your monitors. Press F1 or F2 and Dusk
sets the brightness on the monitor itself, over its cable, the way the buttons on the monitor do.
Nothing is drawn over the screen, so colors and contrast stay as they are.

This repository only holds the downloads. Get the latest version from
[Releases](https://github.com/DAdjadj/dusk-releases/releases/latest).

## Install

1. Download `Dusk.zip` from the latest release and unzip it.
2. Move **Dusk** to your Applications folder and open it.
3. macOS asks to let Dusk use Accessibility. Click **Open System Settings** and turn Dusk on. That's how
   it sees the brightness keys; it acts on no other key.

Requires macOS 26 or later on a Mac with Apple silicon, and a monitor that takes brightness over its
cable (DDC/CI). Most do; a few need DDC/CI turned on in the monitor's own menu. Monitors behind
DisplayLink docks, AirPlay and Sidecar can't be dimmed this way, and Apple's own displays already work
with the keys. Dusk updates itself: it checks once a day, or choose Check Now in Dusk's Settings.

## Keys

- **F1 / F2**: every monitor at once, or only the one with the pointer (Settings).
- **⌃ with F1 / F2**: the other of the two.
- **⌥⇧ with F1 / F2**: smaller steps.
- The menu bar icon has a slider for each monitor.

## Privacy

No accounts, no analytics, no servers. The only network request is the update check, which asks
GitHub for the latest version number and contains nothing about you.

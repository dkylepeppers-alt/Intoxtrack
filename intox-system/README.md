# Intoxication & Arousal System

A SillyTavern extension that tracks intoxication and arousal levels through regex pattern matching on chat messages.

## Features

- Automatic drink detection from narrative text
- Progressive intoxication tiers (Sober → Tipsy → Buzzed → Drunk → Wasted)
- Arousal tracking based on exposure, touch, and embarrassment triggers
- Speech slurring generator
- Food consumption slows intoxication
- Time-based sobering
- Manual controls via settings panel

## Installation

1. In SillyTavern, go to Extensions
2. Click "Install Extension"
3. Paste: `https://github.com/YOUR_USERNAME/intox-system`
4. Reload

## Console Commands

Access via browser console:
javascript
IntoxSystem.addDrinks(2) // Add drinks
IntoxSystem.setArousal(5) // Set arousal
IntoxSystem.slur("Hello") // Test slurring
IntoxSystem.getInjection() // View prompt injection
IntoxSystem.reset() // Reset all values


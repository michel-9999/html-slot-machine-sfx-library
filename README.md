# Slot Machine SFX Library

Original procedurally-generated WAV sound effects designed for use in a game project.

Format:
- Mono WAV
- 48 kHz
- 16-bit PCM

Folders:
- reels: repeatable ticks, spin-up, spin-down, reel stop
- buttons: press, confirm, cancel, spin, toggle
- ui: hover, tab, open/close, error, notification
- coins: credit/coin pings and count-up sounds
- losses: no-win and loss cues
- wins_small / wins_medium / wins_big: increasing reward intensity
- jackpot: large jackpot fanfares
- bonus: bonus trigger/end cues
- symbols: scatter and wild hits
- impacts: generic machine impacts
- transitions: whooshes
- alerts: countdown and attention cues
- loops: short mechanical reel ambience loops

Godot tip:
For repetitive sounds like reel ticks and coin pings, randomly choose among several variations and apply very small pitch variation (for example 0.97–1.03) to reduce listener fatigue.

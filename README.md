# DRM
Minimal 3×3 drum pad and ABC sequencer. Vanilla HTML, CSS and JavaScript, no build step or dependencies.

## Live
https://markxxv.github.io/drm/

## Controls
Tap pads or use keys **1–9**. **Space** plays/pauses the ABC sequence. The editor autosaves to localStorage. Reset restores the default Lamp-inspired rhythm study; it is an approximation, not a transcription.

ABC pad mapping:
```
E  A  d       Hat / Soft Hat / Sharp Hat
D  G  c       Snare / Low Snare / High Snare
C  F  B       Kick / Low Kick / Tight Kick
```
Chords use `[CE]` (kick+hat), `[DE]` (snare+hat), `z` is rest. Tempo from `Q:1/4=71`. Supports basic ABC note lengths and chords. Variations pitch/shape the three supplied source sounds.

## Deployment
Static site at repo root with relative `./samples/` URLs. Workflow publishes to GitHub Pages on pushes to main. In repository Settings → Pages select **GitHub Actions** as the source once if Pages is not yet enabled.

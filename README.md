# enFUCKYOU v2 — Frame-bordered + structured cover

Overlapping frames (default 4 s, 50 % overlap) so each frame borders into the next.
- Analyzes instantaneous frequency peaks with bordering context.
- Builds a continuous structured fake δf(t) (slow random-phase sinusoids + smoothed noise, realistic mHz scale).
- Integrates the fake curve to phase and synthesizes low-level cover tones at 50/60 Hz + harmonics.
- Overlap-adds the result with Hann windows for smooth edges.

## Install
```bash
makepkg -si
```

## Usage
```bash
enFUCKYOU recording.mp4
```
Produces `recording_enFUCKYOU.mp4`.

The overlap/bordering gives cleaner frequency estimates at frame edges and continuous phase in the cover.

---

**This was made with use of AI and not tested in real world conditions. Please test this software if you intend to use it. This software was made to counter potential stalkers, but is not in any way guaranteed to protect you. If you feel you are in danger call local law enforcement. IF you're being tracked by law enforcement, that's not my problem, and don't involve me in your crimes. This is in no way a law enforcement evasion tool. Do not use this software to hide your crimes, as that is not it's intended use, and likely an additional crime, but i don't know. 
The creator of this software is in no way responsible for your legal safety or liability, as this was intended to be a tech demo.**

# Articulation in 3D

An interactive 3D model of the vocal tract for learning how English speech sounds are made.

**Open it:** https://khlee5728-creator.github.io/vocal3d/

- **Explore**: pick a consonant or vowel and watch the lips, tongue, velum and vocal cords. Rotate the head, cut it open, switch on labels or X-ray.
- **Practice**: "Which sound is this?" The model makes a sound without naming it; choose from four. Three game types (Classic, Time attack, Survival) and five levels (Place, Manner, Voicing, Vowels, Mixed).

No sign-in. Progress (rank, badges, looks) is stored only in the visitor's own browser.

## Link options

Add these to the address to open a particular screen:

| Option | Values | Example |
|---|---|---|
| `mode` | `practice` | `?mode=practice` |
| `level` | `place` `manner` `voicing` `vowels` `mixed` | `?mode=practice&level=voicing` |
| `game` | `classic` `time` `survival` | `?mode=practice&game=time` |
| `s` | a sound symbol, to open Explore on that sound | `?s=k` |

## Notes

- The model is schematic: shapes are idealized to show place, manner, voicing and lip rounding.
- Badge, host-character and result art is AI-generated.
- Built as a single HTML file with [three.js](https://threejs.org/) loaded from a CDN.

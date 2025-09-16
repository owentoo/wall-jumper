# Wall Jumper (Phaser 3 on Vercel)

A tiny, static Phaser demo wired for your sprite sheet ranges:

- Slide loop: frames **1–12** (indices 0–11), 24×34 (w×h)
- Jump: frames **13–16** (indices 12–15)
- Land/collision: frame **17** (index 16)

## Run locally
```bash
npx vercel dev
# or
python3 -m http.server 8080
```

## Deploy
```bash
vercel
# Framework: Other
# Output: .
```

Make sure `index.html` and `ninja_sheet.png` are in the project root.

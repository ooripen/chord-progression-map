# Chord Progression Map

Interactive major-key chord progression map with diatonic and secondary dominant movement.

## Features
- Key selection across all 12 major keys
- Interactive chord map with inbound/outbound highlighting
- Chord info panel (function, notes, movement)
- Secondary dominant paths
- Keyboard accessibility for chord nodes

## Run Locally
From this folder:

```bash
python3 -m http.server 8080
```

Then open: `http://localhost:8080`

## Deploy
This is a static site and deploys directly to Vercel.

```bash
vercel --prod
```

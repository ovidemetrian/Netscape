# The Möbius Bar — NoEscape Navigator

**Lumină, nu vrăjeală.** *(Light, not trickery.)*

A single-file tribute to Netscape Navigator 1.0, running a museum of modern dark
patterns inside a 1994 browser chrome. No build step, no dependencies, no tracker,
no server. One HTML file, 60 KB, and a modem that still screams.

**Live:** https://ovidemetrian.github.io/Netscape/
---

## The modem answers first

The site opens on a Windows 95 **Dial-Up Networking** panel. Press any key, tap
anywhere, or click **Connect** and a full 56k handshake plays — dial tone, DTMF
digits for 410-MOBIUS, the 2100 Hz answer tone, the warble, the carrier screech.

Every sound is synthesized live in the Web Audio API. There are no audio files in
this repository.

Browsers block unprompted audio, so the panel asks once, honestly. **Work Offline**
and **Skip the screeching** are real buttons that really work — which is the entire
argument of the site (Law X).

## What's inside

| Section | What it is |
|---|---|
| The Future Past | Tonight's pour — the Suno application |
| The Ten Laws of A.I. | The house rules, on the wall |
| GGI & Synthiosis | The steering wheel for AGI |
| The Neogrammar Index | New words for new failures |
| The Institutional Ledger | NIST, CDAO, and other three-letter friends |
| Guestbook | Pám Pám or it didn't happen |
| NoEscape Navigator | The dark-pattern museum: the cookie bar that overrules you, the exit that won't, the confirmshaming link |

Plus an honest visitor counter that counts your reloads and says so, a sparkle
cursor trail, and several things worth clicking twice.

## Deploying to GitHub Pages

```bash
git init
git add .
git commit -m "The Möbius Bar — NoEscape Navigator"
git branch -M main
git remote add origin https://github.com/USERNAME/mobius-bar.git
git push -u origin main
```

Then: **Settings → Pages → Source: Deploy from a branch → main / (root) → Save.**

Live in about a minute at `https://USERNAME.github.io/mobius-bar/`. Replace the
placeholder URL at the top of this file once it resolves.

`.nojekyll` is included so GitHub serves the files as-is.

## Files

```
index.html    the entire site
README.md     this file
LICENSE       copyright terms
.nojekyll     tells GitHub Pages to skip Jekyll processing
```

## Accessibility & honesty notes

- Respects `prefers-reduced-motion` — animations shorten, the splash clears early.
- No cookies are set. No analytics. No network requests. The page works offline
  after first load.
- The visitor counter starts at 41 and counts only what happened in your session.
  It is a joke that refuses to lie (Law IX).

---

Built by **Ovidiu "Ovi" Demetrian** — Media Content Delivery LLC, Phoenix, AZ.

- https://www.mediacontentdelivery.com
- https://www.smarthomesbyovi.com
- https://10lawsofai.com
- https://youtube.com/@mobiusbar

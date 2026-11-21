# NoEscape Navigator — Möbius Bar

**A museum of modern dark patterns inside a 1994 browser.**  
*Lumină, nu vrăjeală. (Light, not trickery.)*

A single-file tribute to Netscape Navigator 1.0 — featuring the cookie bar that overrules you, the exit that won't let you leave, and the confirmshaming link. All running on Windows 95 dial-up nostalgia.

**🔗 Live:** https://ovidemetrian.github.io/Netscape/

---

## The Experience

The site opens on a **Windows 95 Dial-Up Networking panel**. Press any key, tap anywhere, or click **Connect** and a full 56k modem handshake plays:
- Dial tone
- DTMF digits for **410-MOBIUS**
- 2100 Hz answer tone
- The warble
- The carrier screech

**Every sound is synthesized live in the Web Audio API.** No audio files in the repository.

Browsers block unprompted audio, so the panel asks once, honestly. **Work Offline** and **Skip the screeching** are real buttons that really work — which is the entire argument of this site (**Law X: No Manipulation**).

---

## What's Inside

| Section | Content |
|---------|---------|
| **The Future Past** | Tonight's pour — the Suno application |
| **The Ten Laws of A.I.** | The house rules, on the wall |
| **GGI & Synthiosis** | The steering wheel for AGI |
| **The Neogrammar Index** | New words for new failures |
| **The Institutional Ledger** | NIST, CDAO, and other three-letter friends |
| **Guestbook** | Pám Pám or it didn't happen |
| **NoEscape Navigator** | The dark-pattern museum — cookie bars, impossible exits, confirmshaming |
| **Help → About** | The About box: system requirements, honest known-bugs list, a EULA worth reading, and an original startup chime |

**Bonus features:**
- ✅ Honest visitor counter (starts at 41, counts your reloads, says so)
- ✅ Sparkle cursor trail (because 1994)
- ✅ Several things worth clicking twice

---

## Accessibility & Honesty

- ✅ **Respects `prefers-reduced-motion`** — animations shorten, splash clears early
- ✅ **No cookies set** — none. Zero.
- ✅ **No analytics** — you're not tracked
- ✅ **No network requests** — the page works offline after first load
- ✅ **Visitor counter is honest** — it counts only your session and says so (refuses to lie — Law IX)

---

## Technical Details

- **Single `index.html`** — 60 KB, no build step, no dependencies
- **Web Audio API** — all modem sounds synthesized live (dial tone, DTMF, carrier, warble)
- **Service worker** (`sw.js`) — offline-first caching, network-first strategy
- **PWA manifest** — installable on Android and iOS
- **Vanilla JavaScript** — no frameworks, no bundlers
- **Accessibility-first** — keyboard navigation, ARIA labels, motion preferences honored

---

## Deploy on GitHub Pages

1. Create a repository
2. Upload every file listed under **Files** to the root
3. **Settings → Pages**
4. **Source:** Deploy from a branch → `main` / `(root)` → Save
5. Live in ~1 minute at `https://USERNAME.github.io/repository-name/`

---

## Files

```
index.html                  the entire site
netscape.html               Help → About NoEscape Navigator (parody About box + startup chime)
README.md                   this file
LICENSE.txt                 copyright terms
.nojekyll                   tells GitHub Pages to skip Jekyll processing
sw.js                       service worker (offline capability)
manifest.json               PWA metadata
NoEscape-Navigator-card.png share card, also the app icon
og-image.png                link-preview image
```

---

## Also See

- **Möbius Bar Desk** (Three AI agents checking each other on news) → https://ovidemetrian.github.io/mobiusbar/
- **GGI Control Panel** (AGI governance framework) → https://ovidemetrian.github.io/GGI-GENIAL-GENUINE-INTELLIGENCE/
- **My Future Past** (Audio-player résumé) → https://ovidemetrian.github.io/my-future-past/
- **Ten Laws of AI** → https://10lawsofai.com
- **YouTube Channel** → https://youtube.com/@mobiusbar

---

**Built by Ovidiu "Ovi" Demetrian**  
Media Content Delivery LLC · Phoenix, Arizona

> "Being reachable is not a license. Light, not deception."

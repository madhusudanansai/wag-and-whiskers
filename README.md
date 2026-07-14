# Jamun & Misri's Wag & Whiskers

A tiny pixel game for Aditi. One file, no build, no server, no dependencies.

## Play locally
Double-click `index.html`. That's it. Works on desktop and mobile (touch supported).

## Deploy free on Vercel
Option A (no terminal): go to vercel.com/new, drag the folder containing `index.html`, done.

Option B (terminal):
```
npm i -g vercel
vercel --prod
```
Static single file = free tier forever, no cold starts. (fly.io works too but is overkill — it runs servers; this needs none.)

## Files
- `index.html` — current version (v2: walking characters, plants, Claudith)
- `game-v1-baseline.html` — original baseline version

## What's new in v2
- Higher-res pixel art (640x360), one shared room: their plant-filled living room becomes the salon
- Animated story scenes with walking characters and speech bubbles (no dialogue boxes): Aditi waters her plants and leaves, salon building montage, customers walk in through the door
- **Claudith**, Aditi's helper, shows up unannounced once per day mid-groom — alarm sounds, you must click the half-soaped customer to hide them behind the giant monstera. Hidden: Claudith wonders why the plant is breathing. Caught: the customer wears a flower pot as a disguise ("since when do plants WAG?"). Either way, she needs chai.
- Morning routine on days 2–3: water Aditi's droopy plants so she suspects nothing (Misri walks over and waters each one)
- Interactive panic ending: Aditi's car pulls up, click the tub/table/sign to poof the salon away before she walks in — then Claudith delivers the final line: "the dogs have been VERY normal this week."

## What's new in v4
- Renamed to **Wag & Whiskers** ("dogs, cats, dragons welcome")
- First customer is now **MALAI the cat** (pointy ears, whiskers, curvy tail, bell collar) who chats about HOUSE OF DRAGONS — Aditi's show. Jamun: "Aditi NEVER misses it!! Sofa. Blanket. Yelling at the TV."
- Sam's golf bag is now big and proud front-left with a "SAM'S CLUBS — do not touch" plaque; the salon montage YEETs it into the palm ("sorry, sam!") where it stays for the rest of the game

## What's new in v3
- Sharper rendering (960x540) with finer fur, blinking eyes, wagging tails, belly shading
- Living room: sunbeam with dust motes, a bird that visits the window sill, butterflies around the plants, steam off the tub, sky shifts to sunset as the days pass
- Aditi flavor: GAME OF DRAGONS poster + "home by 6 SHARP, it's dragons night"; Sam's golf bag gets shoved behind the palm during the salon montage ("sorry, sam") and never put back
- **Upgrade shop** between days: golden shampoo, turbo dryer, velvet scissors, fancy rug, disco ball, treat refill — decor items visibly appear in the room and boost tips
- **Suspicion meter**: sloppy Claudith hides raise it; at 50+ you get the "busted" ending where Claudith presents her evidence (wet floors, wagging plants, self-moving golf clubs) — but the dogs deploy Plan B: look adorable

## The game
- **Story**: Aditi keeps lending money to billionaires and never asks for it back, so when she leaves for work, Jamun and Misri secretly run a grooming salon to fix the family finances. Phineas & Ferb rules apply: the salon vanishes the moment she gets home.
- **3 days, 8 customers** (all named after Indian sweets: Ladoo, Barfi, Jalebi, Kaju, Gulab, Pista, Rasgulla) — plus a Day 3 VIP: Mr. Billionaire's pug, who pays a 10x "billionaire surcharge." Debt recovery: salon edition.
- **3 minigames per customer**: scrub the mud (drag), blow-dry (timing bar), styling snips (shrinking-ring clicks). Better play = bigger tips.
- ~5–10 minutes to finish.

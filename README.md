# BradBlox

A Roblox-style avatar editor that runs in the browser (Three.js). Pick an avatar style, skin colour, hair, face, shirt, pants and accessories, then preview the avatar with Idle, Walk, Run, Jump, Climb and Hold animations.

## Files

Everything sits in the top level of the repo, with no folders:

- `index.html`: the whole app
- `Body1_ClawHands.glb` … `Body7_Woman.glb`: the seven avatar styles
- `Animations.glb`: the shared animations (one set fits every body)
- `PonytailHair.glb`, `SpikyHair.glb`, `CurlStrandHair.glb`, `LongStraightHair.glb`, `ShortBobHair.glb`, `BowlCutHair.glb`, `CornrowsHair.glb`, `EmoSwoopHair.glb`, `LongBangsHair.glb`, `DuragHair.glb`, `SweptLayersHair.glb`, `FluffyMessHair.glb`: hair (modelled grey so the app can tint them any colour)
- `PropellerBeanie.glb`, `TopHat.glb`, `Headband.glb`, `YellowBallDude.glb`, `CrewVisor.glb`, `Backpack.glb`, `IsraelFlag.glb`, `FlagBuddy.glb`: accessories

If a model hasn't been uploaded yet, the site still loads and just hides the items that use it.

## Run it

Turn on GitHub Pages (Settings → Pages → Deploy from a branch → `main` / root) and open the Pages link.
Opening `index.html` by double-clicking won't load the models, because browsers block local `.glb` files.

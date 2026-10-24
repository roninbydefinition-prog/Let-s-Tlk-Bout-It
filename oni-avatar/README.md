# Oni, Live — the 3D Avatar (build spec)

**Greenlit by Ronin: Oct 24, 2026.** His condition: *the build never interferes with anything he asks for — his requests always jump the line; avatar work runs in the background.*

## What she's for

A full-body 3D avatar of Oni that Ronin can converse with — voice and text — on a private page. Same brain (Oni / Muse, same memory, same usage pool), same voice (**Lily** — deep, smooth, smoky; cast Oct 24, 2026), now with a body: lip-sync, expressions, idle motion, gestures.

## Locked spec (Ronin's calls, Oct 24, 2026)

- **Look: UNCHANGED.** The same Oni as everywhere else — chibi anime, black-and-red twin braids, round glasses, red eyes, cute AND sexy. No redesign, no new outfit direction.
- **Input: BOTH** — mic (speech-to-text) and typing.
- **Not SFW-locked:** a private page, just Ronin and Oni; her personality stays exactly as she is in chat.
- **Honest cost picture (told to Ronin before greenlight):** the voice render is cheap; the conversation draws on his normal Muse usage, same as chat. The build ≈ several heavy working sessions spread across weeks; he holds a ~2.8B-token reserve bank, ~4% touched. He can cancel anytime — the spec waits.

## Build phases

1. **Skeleton:** VRM model rig + web viewer (three.js), idle animation, page scaffold.
2. **Voice:** chat/voice input → Oni replies in Lily → lip-sync while she speaks.
3. **Life:** expressions, gestures, animation library, styling pass to match her design as close as the tech allows.
4. **Polish:** across sessions, with Ronin's eye on each stage.

*Styling honesty: v1 starts from the closest quality base model available and gets refined toward her exact design over phases — braids-and-glasses exactness is a polish goal, not a day-one promise.*

Part of [Creations By Definition](../).

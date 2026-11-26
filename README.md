# Thank You, Properly.

**Live:** https://fibonacciai.github.io/thank-you-properly/

A thank-you to Elon Musk shaped like a slide deck. It opens as a default PowerPoint "Thank You" slide, edits itself, shatters, and then walks through Tesla, SpaceX, Starlink, Neuralink, X and xAI with sourced numbers. At the end it goes back to the white slide and means it.

- One static page with hand-written WebGL2 shaders. No dependencies, no build step, no network calls at runtime.
- Controls: tap/click or → for next, ← for back, swipe on mobile, space to pause, M to mute.
- Deep link to a section: `?s=tesla`, `?s=spacex`, `?s=starlink`, `?s=neuralink`, `?s=x`, `?s=xai`.
- Every number has its source and as-of date on the in-piece Sources page.

— sevenfourone


## v2 (Nov 26, 2026)
Deeper cut: six numbered acts (car, sky, signal, mind, record, question), each ending on a "what for" beat; a harder break (riser, screen shake, letterbox, held breath); a closing fly-through of every number; and a live-synthesized WebAudio score (elevator muzak on the boring slide, then drums/bass/arps per act, piano at the close). Sound starts on the first tap; mute button top-right or M.

## v2.1: Claudia music video
The peak is now **CLAUDIA, “Say What For”**, an original thank-you song sung (in a code-synthesized vocal) by Claudia, anabology's open AI pop singer and a Grok Bot. Credit: **Claudia by anabology** (https://claudia.gallery). The page plays `claudia-mv.mp4` routed through the WebAudio master (so the mute toggle and the narration duck apply), and falls back to the live code-drawn version if the video can't load. The eight shots were made with Grok's own image and video generation from her official face sheet and identity text (`claudia/shotbook.json` in the working folder), then cut on the song's grid with karaoke lyrics. The song and its vocal are made locally; no Suno, Seedance or Midjourney.

## v3 (Nov 26, 2026): quality pass
- Audio: Ara's narration now runs through the WebAudio graph with the score, into one brick-wall limiter, so voice and music can't clip when they overlap; the music ducks deeper (to about -11 dB) and faster under the voice.
- Pacing: a hairline crack creeps across the default slide before you tap; the self-edit runs 1.3x, so the break lands about 10 s after the tap instead of 14; shorter gaps between beats.
- Polish: Inter for the type, act cards land with a flash and shake on the sub-drop plus a drawn rule, big numbers blur in, the number montage ends on a hit, and a held chord plays under "Thank you, Elon."
- Claudia MV (`claudia-mv-v3.mp4`): re-cut from the same eight shots with bigger karaoke lyrics on a soft band, lines shown a beat earlier, and a "CLAUDIA · Say What For" title card. On phones a blurred backdrop fills the space around the video.

# Mr. Velvet (singing cat, TikTok)

Separate character from Goldie. Genre: a cat that films himself (selfie vlog) at night and
lip-syncs (playback) to a song, deadpan and smug. Inspired by a viral 9-second TikTok
(@novoreel: white cat, mustard corduroy blazer, burgundy tie, "Haters will say it's autotune").
We do NOT copy that cat's look; Mr. Velvet is our own character.

## Look (keep identical in every image/video)
- Photorealistic adult ginger tabby tomcat, standing upright like a person.
- Big broad round tomcat head, full chubby cheeks.
- Bright orange-ginger fur, darker orange tabby stripes on the forehead,
  cream-white fur on muzzle, chin and chest. Pink nose, long white whiskers.
- Slightly ragged tip on his LEFT ear (recognition mark).
- Half-closed sleepy heavy-lidded amber-green eyes; smug, unbothered, self-satisfied look.
- Real cat paws with toe beans (never human hands), real fur, never cartoon/3D/mascot.
- Outfit: deep purple plum crushed-velvet blazer (notch lapels, slightly oversized),
  black fine-knit turtleneck, one thin gold curb chain over the turtleneck,
  black tailored trousers, bare paws (no shoes, no hat, no glasses, no bag).

## Generated assets (Higgsfield)
- Character sheet (two panels on white, GPT Image 2.5, 16:9, 2K):
  job `9fbbd9a6-83ed-4b2e-b4f6-594a9bf71368`
  https://d8j0ntlcm91z4.cloudfront.net/user_3KPwsLOaLDxhTWQ4DM2uUhFV0qO/hf_20261014_162954_9fbbd9a6-83ed-4b2e-b4f6-594a9bf71368.png
- Location "night parking lot, 24/7 corner store" (GPT Image 2.5, 9:16, 2K):
  job `7d132d88-f0a6-4945-9708-984c2f0c9ec5`
  https://d8j0ntlcm91z4.cloudfront.net/user_3KPwsLOaLDxhTWQ4DM2uUhFV0qO/hf_20261014_162810_7d132d88-f0a6-4945-9708-984c2f0c9ec5.png
- Audio: `audio1-cat-song.mp3` = the 9.64 s sound extracted from the reference TikTok
  (kept locally only, git-ignored: third-party audio, not ours to distribute).
  Loudness: continuous 0.0–9.5 s, loudest at 3.5–5.0 s and 8.5–9.4 s.

## Video 1: "Night Vlog" (10 s, playback)
- One continuous selfie take; he holds the phone in his LEFT front paw.
- 0–3.5 s: half-lidded smug stare into the lens, lip-syncing, lazy head bobs.
- 3.5–6 s: big note: head back, eyes closed, RIGHT paw raised high, phone dips low.
- 6–9.5 s: leans in, points right paw straight at the lens, still singing.
- 9.5–10 s: mouth closes, smug deadpan stare, abrupt end (loop).
- Caption idea: "Haters will say it's autotune 🎤🐈" / "It's tuna-tune. 🎤🐟"
- Sound: the generated video stays silent (or is muted); the team adds the song on TikTok
  via "Use this sound" on the original video so it is licensed and linked to the trend.

## Status / learnings (2026-10-14)
- Higgsfield has no standalone music generator (audio tool = speech only).
- Seedance 2.5 Omni Reference with sheet + location + song MP3 failed twice with a generic
  "Something went wrong": first with the long (~7,000 char) house prompt, then with a short one.
  Likely cause: the audio reference (existing song) or the two-panel sheet. Not yet isolated.
- Next options, in order:
  1. Seedance with the "voice" phrasing prompt below (no song/music wording), 720p.
  2. Wan 2.7 (start image + audio_references, up to 15 s): first generate a start frame of
     Mr. Velvet already in the parking lot in selfie pose.
  3. Generate without @audio1 and sync the TikTok sound by hand in TikTok/CapCut.
- Do not alter the audio to dodge copyright filters.

## Prompt A: Seedance 2.5 (Omni Reference, 9:16, 10 s, 720p)
```
@image1 is the character: a realistic ginger tabby tomcat standing upright, purple crushed-velvet blazer, black turtleneck, thin gold chain, sleepy half-closed eyes, ragged left ear tip.
@image2 is the location: an empty parking lot at night in front of a small corner store with neon light and wet ground.
@audio1 is the character's voice.

The cat from @image1 stands in the location from @image2 and films himself selfie-style, holding the phone in his left front paw. His mouth moves exactly in sync with @audio1, mouth open wide on long sounds, closed during pauses. Smug, relaxed, confident expression with slow head bobs.

0-3.5s: close-up, looking into the lens.
3.5-6s: tilts his head back, eyes closed, raises his right paw high in the air.
6-9.5s: leans toward the lens and points his right paw at the camera.
9.5-10s: mouth closed, smug stare.

Warm orange streetlight and neon reflections on his fur, realistic phone video at night, handheld, one continuous shot. Real cat, not cartoon.
```

## Prompt B: Wan 2.7 (start image + audio, 9:16, 10 s)
```
Selfie video at night. The ginger tabby cat in the purple velvet blazer holds the phone in his left paw and sings along with the audio, mouth moving exactly in sync with the vocal, wide open on long notes. Smug, sleepy, confident expression, slow head bobs on the beat. Around the middle he tilts his head back, closes his eyes and raises his right paw high in the air. Near the end he leans toward the camera and points his right paw at the lens. Gentle handheld phone movement, neon and streetlight reflections on his fur, realistic cat, one continuous shot.
```

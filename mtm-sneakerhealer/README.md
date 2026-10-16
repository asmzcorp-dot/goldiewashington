# MTMsneakerhealer: "Sneaker ER" (9 s, 9:16)

Video ad for a sneaker-cleaning business (separate client project, not Goldie).

## Files
- `logo-voor-seedance.png`: logo crop, used as @image2 in Seedance.
- `eindbeeld-logo-overlay.png`: transparent 1080x1920 end-card overlay (gold logo + "wij genezen wat jij draagt"), for the last 1.5 s in editing.
- `ondertitels.srt`: Dutch subtitles.
- Location: Higgsfield GPT Image 2.5 "Sneaker Clinic" (dark studio, black/gold table, heart monitor right, brushes left).

## Script (Dutch voice-over)
| Time | Shot | VO |
|---|---|---|
| 0–1.5 s | Mud-caked white sneaker on the table, weak heartbeat | "Patiënt... ademt nauwelijks." |
| 1.5–3.5 s | Gloved hands spray and brush, foam covers the mud | "Sneakerhealer. We beginnen." |
| 3.5–6.5 s | One towel wipe reveals clean white leather, beeps speed up | |
| 6.5–9 s | Spotless shoe, slow orbit, steady heartbeat, logo | "Niet dood... gewoon vies." |

## Model settings
Seedance 2.5, mode `omni_reference`, 9 s, 9:16, 1080p, bitrate `high`, audio on (draft first).
@image1 = location, @image2 = logo, @audio1 = Dutch voice-over.

## Voice prompt
```
Dutch male voice-over artist, native Netherlands accent, 35–45. Deep, rich, cinematic baritone with real emotion and drama, like a movie trailer narrator crossed with a confident ER surgeon. Highly expressive and dynamic: tense and hushed at the start, building urgency in the middle, then a relieved, cocky, playful punchline with an audible smile. Clear contrast between lines, natural breaths, dramatic pauses, close-miked studio quality. Premium TV commercial energy, never flat or monotone.
```
```
[hushed, tense, almost whispering] Patiënt... ademt nauwelijks.
[short breath] [focused, urgent, determined] Sneakerhealer. [beat] We beginnen.
[relieved, cocky, with a smirk] Niet dood... [playful, warm, confident] gewoon vies.
```
ElevenLabs: stability 25–35%, style 50–70%, similarity 75%, speed 0.9.

## Seedance 2.5 prompt
```
@image1 is the location: a dark luxury sneaker restoration studio, matte black treatment table with brushed-gold edge, a small black heart-rate monitor on a slim stand at the back right corner of the table, brass-handled brushes and a black spray bottle on a black towel at the front left, a small plant and a dark cabinet in the soft background, glowing gold shelves with white sneakers on the back wall. Keep this exact set, lighting and color palette (deep black and warm gold, green glow from the monitor screen).

@audio1 is the Dutch voice-over. Use it exactly as provided, perfectly synced to the action below. Do not generate any other voice or speech.

@image2 is the MTMsneakerhealer logo: a gold serif "MTM" monogram above the gold serif wordmark "MTMsneakerhealer" on black. Reproduce this logo exactly as provided: same letterforms, same spelling, same proportions, same warm gold color. Do not redesign, distort or misspell it.

Style: high-end TV commercial, shot on ARRI Alexa with a macro lens, 9:16 vertical, single continuous take, no cuts. Real-world physics, realistic foam and water, natural motion, crisp detail, shallow depth of field, subtle film grain, warm gold key light from upper left, gentle haze. Looks like a premium Nike commercial, not CGI. No morphing, no warping, no faces, no other text or logos except the @image2 logo at the end. Only two hands in black nitrile gloves appear.

0–1.5s: Low macro shot at table height. A white low-top leather sneaker sits in the center of the table, heavily caked in dried brown mud and dirt, laces grey and stained. The monitor at the back right shows a weak, slow green heartbeat line. Slow, faint beeps. Voice-over (@audio1): "Patiënt... ademt nauwelijks."

1.5–3.5s: Camera slowly pushes in. Two hands in black nitrile gloves enter the frame; one sprays a fine mist of cleaner over the shoe, the other picks up a brass-handled brush and scrubs the side in quick, confident circles. Rich white foam builds up and covers the mud. Voice-over (@audio1): "Sneakerhealer. We beginnen."

3.5–6.5s: The hand takes a black microfiber towel and makes one smooth, slow wipe along the whole side of the shoe from toe to heel. Where the towel passes, the foam and dirt are lifted away, revealing bright, perfectly clean white leather underneath. Tiny water droplets catch the gold light. The heartbeat beeps speed up and grow stronger.

6.5–9s: The hands pull away. The now spotless white sneaker sits gleaming on the black table; the camera does a slow quarter orbit around it in the warm gold light. The monitor shows a strong, steady green heartbeat with confident regular beeps. Voice-over (@audio1): "Niet dood... gewoon vies." In the final 1.5 seconds, the logo from @image2 softly fades in, centered in the dark upper third of the frame above the shoe, glowing warm gold with a subtle light sweep across it, perfectly sharp and legible. The logo is the only text in the video.

Audio: @audio1 voice-over on top. Underneath: deep cinematic low hum, a low bass hit at the very start, crisp foley of spray mist, bristles scrubbing, foam crackling, a towel-wipe whoosh, and heart-monitor beeps that start slow and faint, speed up during the wipe, and end strong and steady. No music with lyrics.
```

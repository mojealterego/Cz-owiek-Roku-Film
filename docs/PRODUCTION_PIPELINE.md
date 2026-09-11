# AI FILM PRODUCTION PIPELINE

## Master flow

`136-page screenplay → acts → sequences → scenes → shots → prompts → references/continuity → generation → editing → sound → master`

## Shot-level prompt pack

For every scene, create:

1. Scene ID.
2. Screenplay time/chronology.
3. Narrative purpose.
4. Shot number.
5. Target duration.
6. Shot class.
7. Camera / lens / movement.
8. Exact source-derived blocking/action.
9. Lighting.
10. Sound / VO cue.
11. Continuity lock.
12. Copy-ready Picsart prompt.
13. Negative prompt.
14. Extend prompt where useful.
15. Recommended generation model.

## Shot classes

Each scene should be considered through:
- establishing;
- master;
- character;
- insert;
- POV;
- reaction;
- detail;
- transition.

Not every scene must use every class; the list is the default coverage framework.

## Duration guidance

Typical AI shot targets:
- 4–8 s: standard dramatic coverage;
- 10–15 s: simple continuous motion or longer blocking;
- up to 30 s: continuous-take opportunities when supported and useful.

## Picsart model/workflow notes

Research previously established:
- WAN 3.0: continuous takes up to 30 seconds; 5/10/15/30 s; Extend; up to 1080p.
- WAN 2.7: 5/10/15 s; up to 4K.
- MiniMax H3 / H3 Max: 5–15 s.
- Flux 3: 5/10/15/20 s or auto.
- Sora 2 in Picsart API: 4/8/12/16/20 s.
- Picsart Storyline: narrative videos up to 10 minutes.
- Picsart Flow Motion Graphics: videos up to 10 minutes.
- Picsart Video Editor: multi-track timeline, trimming, text, music, captions and export.
- Picsart Kai: source up to one hour, producing 20–30 short clips.

These are workflow notes and should be re-verified before production if model/API limits have changed.

## Continuity system

Every generated shot must be checked for:
- character identity;
- age;
- hairstyle;
- glasses;
- wardrobe;
- tattoos;
- tattoo chronology;
- props;
- location;
- time of day;
- weather;
- lighting direction;
- camera axis;
- emotional state;
- preceding/following shot continuity.

## Hard rejection criteria

Reject a generation if it introduces:
- wrong tattoo chronology;
- face drift;
- wrong age;
- wrong body proportions;
- wardrobe continuity error;
- impossible lighting;
- random text/logo/watermark;
- invented props that alter the scene;
- invented dialogue;
- stylization that contradicts the established visual language.

## Source integrity

Never invent dialogue. Use screenplay dialogue/VO where available. Book material may be adapted into VO or cinematic imagery only as an explicit adaptation decision.

# AxoLottaFun — Visual Refresh Asset Prompts

**Project:** AxoLottaFun
**Studio:** Playology Entertainment
**Phase:** 1 — Axolotls, Helpers, Flora
**Total assets:** 81 PNG-32 files
**Style target:** Semi-realistic 3D-render-to-sprite (volumetric, high-end mobile game)

---

## How to use this document

Each asset has its own prompt paragraph. **Always prepend the Universal Preamble** to the per-asset paragraph when submitting to the image generator. The preamble enforces lighting direction, palette, and the underwater-tank context that makes all 81 assets feel like they belong in the same scene.

Frames within a loop should be generated as a **batch with maximum visual consistency** — same camera angle, same lighting, same subject geometry. Only the noted variables (gill position, eye state, breath phase, tentacle position, etc.) change between frames.

---

## Universal Preamble (prepend to every per-asset prompt)

> Semi-realistic 3D-render-to-sprite style. Volumetric form with soft subsurface scattering on translucent biological tissue. Single key light from upper-left at 11 o'clock, soft cool rim light from above (simulating godrays through water from a deep teal aquarium environment, ambient color `#143D50`). Painted-on soft ambient occlusion. No outlines. No pure black, no pure white — warm white highlight `#FFF9EC`, deepest shadow a dark tinted hue of the subject. Fully transparent PNG-32 background. sRGB color space. The art should feel like a high-end mobile game underwater scene — *Sky: Children of the Light* underwater meets *Endling*. Subject anchored as specified per asset. No motion blur, no baked shadows on background, no environmental elements (water, bubbles, plants) included in the asset itself — only the subject.

---

## Universal palette reference

Use these as the base colors so all 81 assets harmonize with the existing tank gradient and UI:

| Role | Hex | Use |
|---|---|---|
| Axolotl base pink | `#F9B8D8` | Primary skin tone |
| Axolotl shadow pink | `#C97AA0` | Subsurface scatter shadow |
| Axolotl deep magenta | `#8A4A6E` | Darkest skin recesses |
| Pearl / iridescent | `#B48FD4` | Legend stage shimmer |
| Bubble yellow | `#FFF082` | Eye catchlight, glow accents |
| Warm highlight | `#FFF9EC` | Specular pop |
| Tank ambient | `#143D50` | Background context only — don't paint into asset |
| Substrate mid | `#6A5A32` | Reference for ground-touching helpers |
| Coral pink accent | `#FF8C8C` | Coral / anemone flora |
| Kelp green deep | `#2A5A4A` | Foreground kelp |
| Kelp green mid | `#3D7560` | Mid kelp |

---

# Section 1: Axolotls (36 files)

**Frame size:** 440 × 400 px each, individual PNG files.
**Anchor:** subject centered horizontally; bottom of silhouette at Y=395; 10–20 px transparent margin on sides and top.
**Pose:** 3/4 front view, facing forward + very slightly to viewer's right. Static body position — **only gills, eyes, and subtle breath change between frames.**
**Loop:** 6 frames at 8 fps = 0.75 s cycle, seamlessly loopable.

---

## 1.1 Egg Stage (`axo_egg_01.png` – `axo_egg_06.png`)

The egg has no gills or limbs. The "breathing" loop is a faint internal glow pulse and slight silhouette shift of the curled hatchling visible inside the translucent egg.

### `axo_egg_01.png`
> A small translucent pink-pearl axolotl egg, perfectly oval, roughly 200px tall centered in a 440×400 canvas with ~100px transparent margin all sides. Egg membrane is soft gelatinous pink (`#F9B8D8` core fading to `#FCDCE8` at the rim) with subtle refractive shine on the upper-left. Inside, the faint silhouette of a curled tiny hatchling is barely visible in deeper pink (`#C97AA0`). A gentle inner glow emanates from the center at lowest intensity (frame 1 of pulse). Subsurface scattering makes the whole egg luminous, as if lit from within. No outline, painted form only.

### `axo_egg_02.png`
> Identical egg to frame 01 — same geometry, position, lighting. Inner glow at 20% intensity (slightly brighter than frame 01). The curled hatchling silhouette inside is fractionally more visible. Same anchor and margins.

### `axo_egg_03.png`
> Identical egg to frame 01 — same geometry, position, lighting. Inner glow at peak intensity (60% — warm `#FFF082` tinted core glow visible through the membrane). Hatchling silhouette most defined at this frame. Same anchor and margins.

### `axo_egg_04.png`
> Identical egg to frame 01. Inner glow at 50%, beginning to fade. Hatchling silhouette slightly shifted — the curled form has subtly repositioned (like a sleeping breath). Same anchor and margins.

### `axo_egg_05.png`
> Identical egg to frame 01. Inner glow at 25%. Hatchling silhouette barely visible. Same anchor and margins.

### `axo_egg_06.png`
> Identical egg to frame 01. Inner glow at 10%, lowest dim before returning to frame 01's baseline. Same anchor and margins.

---

## 1.2 Hatchling Stage (`axo_hatchling_01.png` – `axo_hatchling_06.png`)

A tiny baby axolotl. Oversized head proportional to body (head ~50% of body length), stubby gill fronds (3 per side but short and rounded), very large round dark eyes, no limbs visible yet (or vestigial nubs). Pure cuteness. Skin `#F9B8D8` with soft pink subsurface scatter.

### `axo_hatchling_01.png`
> A tiny baby axolotl, 3/4 front view facing forward and very slightly to the viewer's right. Oversized round head, very large dark glossy eyes (~30% of face width each) with single warm `#FFF9EC` catchlight upper-left in each. Tiny stubby gill fronds (3 short rounded protrusions per side) at the sides of the head, currently in relaxed neutral position. Soft translucent pink skin (`#F9B8D8` body, `#C97AA0` in shadowed underside), faint subsurface scatter glow in the gills. Tiny body, no visible limbs yet. Mouth in a small content curve. Anchored bottom-center of 440×400 canvas, ~15px transparent margin. Frame 01 of 6-frame idle loop: eyes fully open, gills at rest, body in neutral breath position.

### `axo_hatchling_02.png`
> Identical hatchling to frame 01 — same pose, camera angle, lighting, position. Differences only: gills beginning to flutter outward (each frond rotated ~5° away from head), body subtly inflated for inhale phase (paint the form ~1% larger in Y, do not transform), eyes still fully open. Same anchor and margins.

### `axo_hatchling_03.png`
> Identical hatchling to frame 01. Differences only: gills at peak flare (each frond rotated ~10° outward from head, fronds slightly puffed with subsurface light), body at peak inhale, eyes still fully open. Same anchor and margins.

### `axo_hatchling_04.png`
> Identical hatchling to frame 01. Differences only: gills returning toward neutral (~5° outward, settling), body beginning exhale, eyes half-closed (upper eyelid covering ~50% of eye, mid-blink). Same anchor and margins.

### `axo_hatchling_05.png`
> Identical hatchling to frame 01. Differences only: gills at rest, body at full exhale (1% smaller in Y than frame 01), eyes fully closed in a content blink — paint as soft curved closed eyelids matching face curvature. Same anchor and margins.

### `axo_hatchling_06.png`
> Identical hatchling to frame 01. Differences only: gills at neutral, body returning to neutral breath, eyes opening (upper eyelid covering ~30% of eye). Same anchor and margins.

---

## 1.3 Juvenile Stage (`axo_juvenile_01.png` – `axo_juvenile_06.png`)

Adolescent axolotl — limbs have formed (four small soft limbs visible), gill fronds longer and bushier than hatchling but not yet at adult fullness, body slimmer and longer than hatchling. Personality emerging.

### `axo_juvenile_01.png`
> A juvenile axolotl, 3/4 front view facing forward and very slightly to the viewer's right. Body proportions: head still relatively large (~40% of body length) but body has elongated. Four small soft pink limbs visible — front two slightly forward, back two visible at sides of body. Gill fronds at middle development (3 fronds per side, each longer and feather-like compared to hatchling, but not as full as adult). Translucent pink skin (`#F9B8D8` base, `#C97AA0` in shadow recesses, subsurface scatter in gills). Large dark glossy eyes with warm `#FFF9EC` catchlights. Small content smile. Short flat tail just beginning to show fin shape. Anchored bottom-center of 440×400 canvas, ~15px transparent margin. Frame 01 of 6-frame idle loop: eyes open, gills relaxed, neutral breath position.

### `axo_juvenile_02.png`
> Identical juvenile to frame 01. Differences only: gills fluttering outward (~5° rotation per frond), body at inhale (~1% larger in Y), eyes open. Same anchor and margins.

### `axo_juvenile_03.png`
> Identical juvenile to frame 01. Differences only: gills at peak flare (~10° outward, fronds slightly translucent with subsurface light), body at peak inhale, eyes open. Same anchor and margins.

### `axo_juvenile_04.png`
> Identical juvenile to frame 01. Differences only: gills relaxing (~5° outward), body beginning exhale, eyes half-closed (mid-blink). Same anchor and margins.

### `axo_juvenile_05.png`
> Identical juvenile to frame 01. Differences only: gills at rest, body at full exhale, eyes fully closed in soft content blink. Same anchor and margins.

### `axo_juvenile_06.png`
> Identical juvenile to frame 01. Differences only: gills at neutral, body returning to neutral, eyes opening (~30% closed). Same anchor and margins.

---

## 1.4 Adult Stage (`axo_adult_01.png` – `axo_adult_06.png`)

The canonical axolotl — the hero image of the entire game. Full feathery gill fronds (3 per side, large and luxuriantly branched), four small soft limbs, finned tail. This is the most important asset of the 81.

### `axo_adult_01.png`
> An adult axolotl, 3/4 front view facing forward and very slightly to the viewer's right. The canonical, most iconic form of the species: rounded head with broad smile, four small soft limbs (front pair slightly forward, back pair visible at sides), flat finned tail trailing behind, and three large feathery gill fronds per side of head — each frond luxuriantly branched, translucent and glowing softly from subsurface scatter (`#F9B8D8` base, `#C97AA0` shadow, faint `#FFF082` glow at frond tips). Soft pink translucent skin overall, slightly deeper pink in shadowed recesses. Large round dark glossy eyes with prominent single warm `#FFF9EC` catchlight upper-left in each. Content, neutral-happy expression. Anchored bottom-center of 440×400 canvas, ~15px transparent margin. Frame 01 of 6-frame idle loop: eyes open, gills relaxed, body in neutral breath position. Render with high detail — this is the hero asset.

### `axo_adult_02.png`
> Identical adult to frame 01 — same pose, angle, lighting, body geometry. Differences only: each gill frond beginning to flutter outward (~5° rotation away from head), individual frond branches subtly fanning. Body at inhale (~1% larger in Y, painted not transformed). Eyes fully open. Same anchor and margins. Match frame 01 lighting and color exactly.

### `axo_adult_03.png`
> Identical adult to frame 01. Differences only: gills at peak flare — each frond rotated ~10° outward, individual branches at maximum fan, subsurface glow visibly stronger through the fronds. Body at peak inhale. Eyes fully open. Same anchor and margins. Match frame 01 lighting exactly.

### `axo_adult_04.png`
> Identical adult to frame 01. Differences only: gills relaxing back inward (~5° outward, branches settling), body beginning exhale, eyes half-closed (upper eyelid covering ~50% of eye, in the act of blinking). Same anchor and margins.

### `axo_adult_05.png`
> Identical adult to frame 01. Differences only: gills at full rest, body at full exhale (~1% smaller in Y than frame 01), eyes fully closed in a soft content blink — paint as smooth curved closed eyelids matching head curvature, with subtle lash hint. Same anchor and margins. This is the peak-cuteness frame.

### `axo_adult_06.png`
> Identical adult to frame 01. Differences only: gills at neutral position, body returning toward neutral breath, eyes opening (upper eyelid covering ~30% of eye). Same anchor and margins.

---

## 1.5 Elder Stage (`axo_elder_01.png` – `axo_elder_06.png`)

Wise, mature axolotl. Adult proportions but deeper saturation, slightly longer and more elegant gill fronds, and a faint shimmer on the skin (subtle iridescence, not yet bioluminescent). Slightly more dignified expression.

### `axo_elder_01.png`
> An elder axolotl, 3/4 front view facing forward and very slightly to the viewer's right. Adult body proportions but with mature refinement: gill fronds slightly longer and more elegantly branched than adult, skin a fractionally deeper saturated pink (`#F9B8D8` shifted ~5% deeper toward `#F4A0C8`), with a subtle iridescent shimmer on the upper body surfaces (faint `#B48FD4` pearl highlights catching the upper-left light). Eyes slightly more lidded, conveying calm wisdom — but still warm, with prominent catchlights. Four small soft limbs, flat finned tail. Gentle dignified expression. Anchored bottom-center of 440×400 canvas, ~15px transparent margin. Frame 01 of 6-frame idle loop: eyes in calm half-aware state, gills relaxed, neutral breath.

### `axo_elder_02.png`
> Identical elder to frame 01. Differences only: gills fluttering outward (~5°), subsurface glow in fronds slightly stronger. Body at inhale. Eyes in same calm half-aware position. Same anchor and margins.

### `axo_elder_03.png`
> Identical elder to frame 01. Differences only: gills at peak flare (~10° outward), iridescent skin shimmer slightly more pronounced at this breath peak. Body at peak inhale. Same anchor and margins.

### `axo_elder_04.png`
> Identical elder to frame 01. Differences only: gills relaxing (~5° outward), body exhaling, eyes fully closed in a meditative blink (deeper, slower-feeling than adult). Same anchor and margins.

### `axo_elder_05.png`
> Identical elder to frame 01. Differences only: gills at rest, body at full exhale, eyes still closed (this elder holds the blink one extra frame — meditative). Same anchor and margins.

### `axo_elder_06.png`
> Identical elder to frame 01. Differences only: gills at neutral, body returning to neutral, eyes opening (~30% closed). Same anchor and margins.

---

## 1.6 Legend Stage (`axo_legend_01.png` – `axo_legend_06.png`)

Mythic form. Bioluminescent — gentle inner glow throughout the body, intensifying on breath peaks. Iridescent skin shifting toward pearl `#B48FD4`. The fronds glow visibly. Still readable as the same character — magical but not gaudy.

### `axo_legend_01.png`
> A legend-tier axolotl, 3/4 front view facing forward and very slightly to the viewer's right. Same body geometry as adult/elder but transcendent: bioluminescent inner glow throughout the body at low intensity (frame 01 baseline), skin shifting between pink (`#F9B8D8`) and iridescent pearl (`#B48FD4`) with a soft chromatic shift across the body — pearl tones catching the upper light, pink remaining in the shadow side. Gill fronds glow visibly with warm `#FFF082` light at their tips, subsurface scatter strong throughout each frond. Eyes deep and luminous, with not just a catchlight but a subtle inner glow in the iris itself. Four small soft limbs, flat finned tail with faint trailing shimmer at the tail edges. Serene, almost knowing expression. Anchored bottom-center of 440×400 canvas, ~15px transparent margin. Magical but restrained — not gaudy, not bright. Frame 01 of 6-frame idle loop: gills relaxed, eyes open, glow at lowest intensity (~30% of peak).

### `axo_legend_02.png`
> Identical legend to frame 01. Differences only: gills flutter outward (~5°), bioluminescent glow intensifying to ~50% — pearl iridescence on skin slightly more saturated, frond glow brighter. Body at inhale. Eyes open. Same anchor and margins.

### `axo_legend_03.png`
> Identical legend to frame 01. Differences only: gills at peak flare (~10° outward), bioluminescent glow at peak (~80% intensity) — skin shimmer most pronounced, frond tips brightest with warm `#FFF082` glow, faint chromatic halo visible at body edges. Body at peak inhale. This is the visually peak frame. Same anchor and margins.

### `axo_legend_04.png`
> Identical legend to frame 01. Differences only: gills relaxing (~5° outward), glow fading to ~60%, body exhaling, eyes half-closed in slow mystical blink. Same anchor and margins.

### `axo_legend_05.png`
> Identical legend to frame 01. Differences only: gills at rest, glow at ~40%, body at full exhale, eyes fully closed — closed lids retain faint inner glow at the seam, suggesting the radiance continues inside. Same anchor and margins.

### `axo_legend_06.png`
> Identical legend to frame 01. Differences only: gills at neutral, glow returning to ~30% baseline, eyes opening (~30% closed). Same anchor and margins.

---

# Section 2: Helper Creatures (40 files)

**Frame size:** varies per helper (see individual sections).
**Anchor:** within each frame, the creature's contact-point-with-substrate (or body center for full swimmers) at horizontal center; bottom of creature at ~90% of frame height.
**Facing:** **always drawn facing right** — the engine horizontally flips the sprite for leftward travel.
**Loop:** 6 or 8 frames at 8 fps, seamlessly loopable.

---

## 2.1 Snorkel the Snail (`helper_snorkel_01.png` – `helper_snorkel_06.png`)

**Frame size:** 80 × 80 px. **6 frames.** Slow crawler along the substrate.

Personality: slow, methodical, gentle. Wears a tiny diving mask. Spiral shell is the visual hero element.

### `helper_snorkel_01.png`
> A small aquatic snail facing right, 80×80 canvas. Spiral coiled shell ~50px diameter centered on the body, painted in warm cream-and-brown swirl pattern (`#F5E6C8` to `#8B5E3C`) with soft volumetric shading and a glossy upper-left highlight. Soft pink body (`#F9B8D8`) extends forward and slightly down from the shell base. Two short eye stalks rising from the head, each tipped with a small dark eye. A tiny round glass diving mask covers the front of the face (~15px wide, transparent glass with a thin gold rim, faint reflective glint upper-left). Bottom of body at Y=72 (90% of canvas height) so the foot meets the substrate. Frame 01 of 6-frame walk cycle: foot in neutral muscular contraction, shell upright, eye stalks vertical.

### `helper_snorkel_02.png`
> Identical snail to frame 01. Differences only: foot in first phase of muscular wave (left half of foot subtly contracted, right half extended forward by ~2px), shell tilted ~2° forward as body lurches, eye stalks swaying ~3° rightward from inertia. Same anchor, lighting, geometry otherwise.

### `helper_snorkel_03.png`
> Identical snail to frame 01. Differences only: foot at peak wave (full contraction moved through to mid-foot), shell tilted ~4° forward, eye stalks at peak rightward sway (~5°). Same anchor and lighting.

### `helper_snorkel_04.png`
> Identical snail to frame 01. Differences only: foot in trailing wave phase (right half contracting, left half extending), shell returning to ~2° forward tilt, eye stalks swaying back toward vertical. Same anchor and lighting.

### `helper_snorkel_05.png`
> Identical snail to frame 01. Differences only: foot near end of wave (mostly relaxed, slight leftward residual), shell nearly upright, eye stalks past vertical at ~3° leftward sway. Same anchor and lighting.

### `helper_snorkel_06.png`
> Identical snail to frame 01. Differences only: foot fully relaxed about to begin next wave, shell upright, eye stalks returning to vertical. Same anchor and lighting. (Loops back to frame 01.)

---

## 2.2 Shrimply the Shrimp (`helper_shrimply_01.png` – `helper_shrimply_06.png`)

**Frame size:** 96 × 64 px. **6 frames.** Hyperactive mid-water swimmer.

Personality: zippy, expressive, friendly. Translucent body with visible segmentation. Long antennae. Best friends with Snorkel.

### `helper_shrimply_01.png`
> A small aquatic shrimp facing right, 96×64 canvas. Body ~80px long horizontally, oriented with head at right side and tail fan at left. Body is segmented (5–6 visible abdominal segments) with translucent warm coral coloring (`#FF9E7A` base, deeper `#D06848` in shadows, faint subsurface scatter through the translucent shell). Curved hunched posture typical of shrimp. Large compound eye on the right side (head end) — dark with subtle iridescence. Two long thin antennae trailing back and slightly upward from the head, ~40px each. Tail fan at left end (3 overlapping fins, soft pink-orange translucent). Five pairs of small swimmerets (legs) along the underside of the abdomen. Bottom of body at Y=58 (90% of canvas height). Frame 01 of 6-frame swim cycle: body in neutral arc, swimmerets in mid-stroke (3 forward, 2 back), antennae streaming straight back.

### `helper_shrimply_02.png`
> Identical shrimp to frame 01. Differences only: body slightly more arched (curl ~3° tighter), swimmerets in next stroke phase (forward-back pattern shifted), antennae fluttering ~5° upward from inertia. Same anchor, lighting, geometry.

### `helper_shrimply_03.png`
> Identical shrimp to frame 01. Differences only: body at peak arch (curl ~6° tighter than frame 01), swimmerets at peak forward sweep (4 forward, 1 back), tail fan slightly compressed for thrust, antennae at peak ~10° upward sweep. Same anchor and lighting.

### `helper_shrimply_04.png`
> Identical shrimp to frame 01. Differences only: body uncurling back toward neutral (~3° tighter than frame 01), swimmerets reversing stroke, tail fan opening, antennae returning toward neutral. Same anchor and lighting.

### `helper_shrimply_05.png`
> Identical shrimp to frame 01. Differences only: body at neutral, swimmerets in opposite stroke phase from frame 01 (2 forward, 3 back), tail fan fully open, antennae trailing slightly downward (~5°). Same anchor and lighting.

### `helper_shrimply_06.png`
> Identical shrimp to frame 01. Differences only: body returning to neutral start position, swimmerets approaching frame 01 phase, antennae returning to straight back. Same anchor and lighting. (Loops back to frame 01.)

---

## 2.3 Clawdia the Crab (`helper_clawdia_01.png` – `helper_clawdia_08.png`)

**Frame size:** 100 × 80 px. **8 frames.** Sideways scuttle along substrate.

Personality: businesslike, no-nonsense. Carries a tiny brown leather briefcase in one claw.

### `helper_clawdia_01.png`
> A small aquatic crab facing right, 100×80 canvas. Body is a wide low oval carapace ~60px wide × ~30px tall, deep red-orange (`#C8523A` base, `#8A2E20` in shadows, glossy upper-left specular highlight). Two large claws extending forward — the right claw (viewer's right, the crab's left from its perspective) holds a tiny brown leather briefcase (~14×10px, with a small gold clasp). The left claw is empty and slightly raised in pincer pose. Four pairs of walking legs visible — segmented, jointed, deep red-orange matching body. Two small dark eyes on short stalks on top of carapace. Bottom of body (where legs meet substrate) at Y=72 (90% of canvas height). Frame 01 of 8-frame walk cycle: legs in pose 1 of sideways scuttle (front-right legs forward, back-left legs forward, opposing pairs back), body level, briefcase steady, eye stalks vertical.

### `helper_clawdia_02.png`
> Identical crab to frame 01. Differences only: legs transitioning to pose 2 (the legs that were forward are now mid-step planted, the legs that were back are lifting). Body bobs up ~1px from the step. Briefcase swings forward ~2px. Eye stalks lean ~2° forward from motion. Same anchor and lighting.

### `helper_clawdia_03.png`
> Identical crab to frame 01. Differences only: legs in pose 3 (lifted legs now forward, planted legs now in mid-stride). Body level. Briefcase at peak forward swing (~3px ahead). Eye stalks vertical. Same anchor and lighting.

### `helper_clawdia_04.png`
> Identical crab to frame 01. Differences only: legs in pose 4 (forward legs planting, rear legs lifting). Body bobs down ~1px. Briefcase swinging back. Eye stalks lean ~2° backward. Same anchor and lighting.

### `helper_clawdia_05.png`
> Identical crab to frame 01. Differences only: legs in pose 5 (mirror of pose 1 — opposite legs forward). Body level. Briefcase steady at neutral. Eye stalks vertical. Same anchor and lighting.

### `helper_clawdia_06.png`
> Identical crab to frame 01. Differences only: legs in pose 6 (mirror of pose 2). Body bobs up ~1px. Briefcase swings back ~2px. Eye stalks lean ~2° backward. Same anchor and lighting.

### `helper_clawdia_07.png`
> Identical crab to frame 01. Differences only: legs in pose 7 (mirror of pose 3). Body level. Briefcase at peak backward swing (~3px behind). Eye stalks vertical. Same anchor and lighting.

### `helper_clawdia_08.png`
> Identical crab to frame 01. Differences only: legs in pose 8 (mirror of pose 4, transitioning back to pose 1). Body bobs down ~1px. Briefcase swinging forward toward neutral. Eye stalks lean ~2° forward. Same anchor and lighting. (Loops back to frame 01.)

---

## 2.4 Puffington the Pufferfish (`helper_puffington_01.png` – `helper_puffington_06.png`)

**Frame size:** 96 × 96 px. **6 frames.** Mid-water swimmer in **non-inflated** state (sweet, gentle).

Personality: anxious, sweet, easily startled. This base animation is calm — the inflate is a separate special anim for v2.

### `helper_puffington_01.png`
> A small pufferfish facing right, 96×96 canvas, in calm non-inflated state. Body is a soft oval ~70px wide × ~55px tall, warm sandy yellow on top fading to cream-white belly (`#F5D86E` dorsal, `#FFF5D8` ventral). Tiny dark dots/spots scattered across the dorsal surface. Small rounded fins: pectoral fin near the head (right side), small dorsal fin on top, ventral fin underneath, and a soft fan-shaped tail fin at the left. Large round dark eye with prominent warm `#FFF9EC` catchlight upper-left. Small puckered mouth in a content shape. Soft volumetric shading. Body center at horizontal middle, bottom of body at Y=86 (90% of canvas height — fish floats slightly above this point). Frame 01 of 6-frame swim cycle: all fins in neutral position, eye open, body in neutral breath.

### `helper_puffington_02.png`
> Identical pufferfish to frame 01. Differences only: pectoral fin rotated ~5° forward (mid-flutter), tail fin curved gently ~5° to the right, body subtly inflated (~1% larger in Y) for breath. Eye open. Same anchor, lighting.

### `helper_puffington_03.png`
> Identical pufferfish to frame 01. Differences only: pectoral fin at peak forward flutter (~10°), tail fin at peak rightward curve (~10°), body at peak inhale. Eye open. Same anchor and lighting.

### `helper_puffington_04.png`
> Identical pufferfish to frame 01. Differences only: pectoral fin returning to neutral (~5° forward), tail fin uncurving (~5°), body beginning exhale, eye half-closed (slow blink). Same anchor and lighting.

### `helper_puffington_05.png`
> Identical pufferfish to frame 01. Differences only: pectoral fin at neutral, tail fin at neutral, body at full exhale, eye fully closed in soft content blink. Same anchor and lighting.

### `helper_puffington_06.png`
> Identical pufferfish to frame 01. Differences only: pectoral fin neutral, tail fin slightly leftward (~5°), body returning to neutral, eye opening (~30% closed). Same anchor and lighting. (Loops back to frame 01.)

---

## 2.5 Inky the Squid (`helper_inky_01.png` – `helper_inky_08.png`)

**Frame size:** 112 × 96 px. **8 frames.** Mid-water swimmer with tentacle undulation.

Personality: artistic, contemplative. Paints murals on tank glass. Translucent mantle with subtle iridescent shimmer.

### `helper_inky_01.png`
> A small squid facing right, 112×96 canvas. Body has two parts: a torpedo-shaped mantle (~50px long × ~30px tall) at the right (the squid's head end), translucent purple-magenta (`#A06AC4` base, `#6A3A8E` shadow, faint iridescent shimmer with subtle subsurface scatter) with two small triangular fins on the sides of the mantle (one visible at top). Two large round dark eyes near the front of the mantle, with prominent warm `#FFF9EC` catchlights. Below the mantle: 8 tentacles flowing back to the left, each ~40–50px long, tapering, the front pair (2 longer feeding tentacles) more prominent than the other 6, all flowing in graceful curves. Tentacles painted in same purple gradient as mantle but slightly more translucent at the tips. Bottom of body at Y=86 (90% of canvas height — body floats above this). Frame 01 of 8-frame swim cycle: tentacles in neutral flowing position, fins on mantle in neutral, eyes open.

### `helper_inky_02.png`
> Identical squid to frame 01. Differences only: mantle fins curving inward (~5°), tentacles in undulation phase 2 — each tentacle has shifted ~3px in its waveform, the long pair now slightly more curved upward. Mantle subtly compressed (~1% smaller in Y) at start of jet pulse. Same anchor and lighting.

### `helper_inky_03.png`
> Identical squid to frame 01. Differences only: mantle fins at peak inward curl (~10°), tentacles in phase 3 — all tentacles drawn together slightly (~3°), mantle at peak compression (~2% smaller in Y). Same anchor and lighting.

### `helper_inky_04.png`
> Identical squid to frame 01. Differences only: mantle fins beginning to flare outward (~5° outward), tentacles flaring slightly (~3° outward fan), mantle expanding back toward neutral. Same anchor and lighting.

### `helper_inky_05.png`
> Identical squid to frame 01. Differences only: mantle fins at neutral, tentacles at full flare (~5° outward fan from each tentacle), mantle at neutral, eyes still open. Same anchor and lighting.

### `helper_inky_06.png`
> Identical squid to frame 01. Differences only: mantle fins curving outward (~5°), tentacles returning toward neutral, mantle subtly inflated for inhale, eyes half-closed (slow mystical blink). Same anchor and lighting.

### `helper_inky_07.png`
> Identical squid to frame 01. Differences only: mantle fins at peak outward (~10°), tentacles at neutral, mantle at peak inhale (~1% larger in Y), eyes fully closed in soft blink. Same anchor and lighting.

### `helper_inky_08.png`
> Identical squid to frame 01. Differences only: mantle fins returning to neutral, tentacles slightly past neutral toward the next pulse, mantle settling, eyes opening (~30% closed). Same anchor and lighting. (Loops back to frame 01.)

---

## 2.6 Oracle the Octopus (`helper_oracle_01.png` – `helper_oracle_08.png`)

**Frame size:** 128 × 128 px. **8 frames.** Slow ethereal floater. The most visually impressive helper.

Personality: ancient, all-knowing, rarely visible. Largest helper. Slight translucency throughout to convey otherworldliness.

### `helper_oracle_01.png`
> A small octopus facing right, 128×128 canvas. Bulbous round head (mantle) ~50px diameter at the upper-right of the body, painted in deep iridescent purple-blue (`#5A3A8E` base, `#3A1E6A` shadow, with subtle iridescent shimmer toward `#B48FD4` pearl in the highlights). Two large luminous eyes on the head — dark with deep inner glow, prominent warm `#FFF9EC` catchlights and a subtle inner `#FFF082` warm light suggesting ancient wisdom. Eight long sinuous tentacles flowing from beneath the head, each ~60–80px long with visible suckers along the underside, fanning out and trailing back to the left in graceful curves. Tentacles painted with same iridescent gradient as head but more translucent at the tips (you can see faint subsurface light through them). Subtle overall body translucency (~10% — the whole creature feels half-real). Body centered horizontally, bottom of trailing tentacles at Y=115 (90% of canvas height). Frame 01 of 8-frame slow float cycle: tentacles in neutral flowing position, head level, eyes open and serene.

### `helper_oracle_02.png`
> Identical octopus to frame 01. Differences only: head rising ~2px (subtle vertical float), tentacles beginning slow undulation — each tentacle in phase 2 of its waveform with subtle curves shifting, slightly looser fan. Eyes serene. Same anchor and lighting.

### `helper_oracle_03.png`
> Identical octopus to frame 01. Differences only: head at peak vertical rise (~4px above neutral), tentacles in phase 3 — central tentacles flowing inward, outer tentacles flowing outward in slow opposing wave. Eyes serene. Same anchor and lighting.

### `helper_oracle_04.png`
> Identical octopus to frame 01. Differences only: head descending back toward neutral (~2px above), tentacles in phase 4 — wave continuing, individual tentacles at varied positions for organic motion. Eyes half-closed (slow contemplative blink). Same anchor and lighting.

### `helper_oracle_05.png`
> Identical octopus to frame 01. Differences only: head at neutral level, tentacles in phase 5 — central tentacles flowing outward, outer tentacles flowing inward (opposite of phase 3), eyes fully closed in slow blink, faint inner glow visible at the closed lid seam. Same anchor and lighting.

### `helper_oracle_06.png`
> Identical octopus to frame 01. Differences only: head descending below neutral (~2px lower), tentacles in phase 6, eyes still closed. Same anchor and lighting.

### `helper_oracle_07.png`
> Identical octopus to frame 01. Differences only: head at lowest point (~4px below neutral), tentacles in phase 7, eyes opening (~30% closed). Same anchor and lighting.

### `helper_oracle_08.png`
> Identical octopus to frame 01. Differences only: head rising back toward neutral (~2px below), tentacles in phase 8 settling, eyes fully open and serene. Same anchor and lighting. (Loops back to frame 01.)

---

# Section 3: Background Flora (5 files)

**Canvas size:** 1920 × 1080 px each.
**Background:** transparent. Flora bottom-anchored, full canvas width, transparent above the seabed line (~bottom 60% of canvas contains art, top 40% transparent).
**Do not paint:** substrate, water, bubbles, or any other tank elements. Flora only.

---

### `flora_far_silhouette.png`
> A distant horizon line of underwater silhouette plants and kelp at the back of a deep teal aquarium, 1920×1080 canvas. Bottom-anchored, full canvas width. Dark muted silhouettes only (low contrast, painted in `#0A2030` to `#0E2A3A` range) with very soft edges suggesting distance and water-haze. Multiple kelp stalk silhouettes of varying heights (40–200px from bottom), scattered across the entire width with natural spacing — denser in some areas, sparser in others, no perfect symmetry. A few rounded silhouette shapes suggest distant coral mounds or rocks (~80–120px tall) along the bottom edge. Top 60% of canvas fully transparent. No detail, no defined edges — pure atmospheric backdrop layer meant to imply depth.

### `flora_mid_kelp.png`
> A middle layer of underwater kelp stalks at moderate distance, 1920×1080 canvas. Bottom-anchored, full canvas width. Painted with moderate detail in teal-green tones (`#2A5A4A` base, `#1A3A30` shadows, faint `#4A8A70` highlights), more saturated than the far silhouette layer but still subdued. 6–9 kelp stalks distributed across the width, varying heights (200–500px), some leaning slightly in implied current. Each stalk has 4–8 visible long leaves/blades flowing from a central stem. Soft volumetric shading suggesting water diffusion. Defined enough to read as kelp but not sharply detailed — this is a parallax mid layer. Top 50% of canvas transparent.

### `flora_foreground_left.png`
> A single lush detailed foreground kelp stalk emerging from the bottom-left of a 1920×1080 canvas. Stalk and leaves occupy roughly the left 25% of canvas width, rising ~700px tall from the bottom edge (~65% of canvas height). Highly detailed: visible texture on the central stem, individual blade-like leaves with visible vein patterns, painted in saturated kelp greens (`#3D7560` base, `#1A3A2A` shadows, `#7AB890` highlights catching the upper-left light). 10–14 long leaves flowing upward and to the right (implied gentle current). Bottom-anchored, with the base/holdfast visible at the bottom edge. Subsurface light filtering through the translucent leaf edges. Top 35% of canvas and right 75% fully transparent. This is a hero parallax foreground asset.

### `flora_foreground_right.png`
> A single lush detailed foreground kelp stalk emerging from the bottom-right of a 1920×1080 canvas — visual mirror of `flora_foreground_left.png` but with natural variation, not a literal flip. Stalk and leaves occupy roughly the right 25% of canvas width, rising ~700px tall (~65% of canvas height). Highly detailed stem, individual leaves with vein patterns, painted in the same saturated kelp greens (`#3D7560` / `#1A3A2A` / `#7AB890`). 10–14 long leaves flowing upward and to the left (implied gentle current). Bottom-anchored, base/holdfast visible. Subsurface light filtering through leaf edges. Top 35% and left 75% fully transparent. Hero parallax foreground asset.

### `flora_coral_clumps.png`
> A collection of small coral and anemone clusters distributed along the bottom of a 1920×1080 canvas, bottom-anchored. 3–5 distinct clumps scattered across the canvas width with natural spacing (not evenly distributed — visual rhythm matters). Each clump occupies roughly 150–250px wide × 100–180px tall. Mix of forms: at least one branching coral (warm coral pink `#FF8C8C` with `#C85858` shadows), at least one bulbous anemone (deep warm red `#C84848` with delicate tentacle fronds in soft pink), at least one small mossy/encrusting coral patch in warm green-cream tones. Each clump has clear volumetric form, subsurface scatter on translucent tentacle elements, and warm color pop against what will be a cool teal background. Top 80% of canvas transparent. These are accent pops of warm color in a cool environment.

---

# Notes for the Image Generator Operator

**Batching:** Generate the 6 (or 8) frames of each loop as a single batch with seed locked, varying only the noted differences. This is the single most important factor for visual consistency within a loop.

**Iteration:** Frame 01 of each subject is the canonical reference. Approve frame 01 first, then generate the rest of the loop matching its exact pose, lighting, and color.

**Hero priority:** If quality must be sacrificed somewhere due to time/budget, prioritize:
1. `axo_adult_*.png` (most-seen game state)
2. `axo_legend_*.png` (endgame wow moment)
3. `helper_oracle_*.png` (rarest visible helper, most magical)
4. `flora_foreground_left.png` / `flora_foreground_right.png` (always on screen)

Lower-priority filler can be the in-between stages (juvenile, elder) and the lower-tier helpers (snorkel, shrimply).

**Background discipline:** Repeat for every prompt — *fully transparent PNG-32 background, no environmental elements baked in, no shadows on background, no water, no bubbles, no plants in helper or axolotl assets.* This is the most common failure mode for generators and the most expensive to fix downstream.

**Delivery:** Drop the populated `/assets/` folder into the project root next to `AxoLottaFun_Game.html`. The integration patch will preload everything on game start with a fallback to existing SVG/canvas rendering if any asset is missing — so partial deliveries are safe to test.

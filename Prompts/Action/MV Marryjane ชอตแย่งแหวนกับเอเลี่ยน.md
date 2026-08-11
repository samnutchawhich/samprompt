---
title: MV Marryjane ชอตแย่งแหวนกับเอเลี่ยน
scene: "Scene 04D — The Tumble / Chasing the Ring Down"
project: Mary Jane MV
category: Action
tags:
  - prompt/video
  - category/action
  - subgenre/comedy-action
  - subgenre/anime-3d
  - project/mary-jane-mv
  - technique/reference-to-video
  - technique/character-lock
tool: Seedance 2.5
duration: 15s
aspect: "16:9"
references: 8
status: draft
rating: 
created: 2026-08-09
---

# MV Marryjane — ชอตแย่งแหวนกับเอเลี่ยน

> [!abstract] สรุป
> ต่อจากซีนขอแต่งงาน — แซมนอนชูแหวนอยู่ที่เท้าแมรี่เจน แล้วจู่ๆ เอเลี่ยนกระโดดถล่ม **กลิ้งลงหลังคาลาดด้วยกัน** แหวนหลุดกระเด็นนำหน้าไป ทั้งคู่คว้าแหวนกลางกลิ้ง แซมตั้งหลักได้ **เตะ 1 ที** แล้ววิ่งไล่แหวนต่อ

## Reference images

| Slot | ใช้เฉพาะ |
|---|---|
| `<<<image_1>>>` | **SAM — หน้า** ผมน้ำตาลตั้ง แว่นทองเหลืองบนหน้าผาก ตาน้ำตาล คางคม รอยเปื้อนที่แก้ม |
| `<<<image_2>>>` | **SAM — ลุคปัจจุบัน (แขนขาด)** เสื้อเทาแขนสั้น **แขนขวาขาดหมด** แขนซ้ายปกติ กางเกงคาร์โก้เขียวมะกอก บู๊ทน้ำตาล ถุงมือเปิดนิ้ว เป้ + ถุงผ้าใส่อัญมณี **หูฟังคล้องคอ** |
| `<<<image_3>>>` | **คอร์กี้ของแซม** ส้มอมน้ำตาล-ขาว สายรัดชมพู (ตัวประกอบ) |
| `<<<image_4>>>` | **Mary Jane — หน้า** ผมบ๊อบสีน้ำตาลแดง แผลเป็นเล็กที่แก้ม ตาน้ำตาล |
| `<<<image_5>>>` | **Mary Jane — ชุด** เชิ้ตลายสก็อตเขียวเปิด ทับเสื้อดำขาด กางเกงยีนส์ขาสั้น ดาบคาตานะ รองเท้าผ้าใบสีเบอร์กันดี |
| `<<<image_6>>>` | **โลเคชั่น** ดาดฟ้าตอนเช้าฟ้าครึ้ม เมืองจมน้ำด้านล่าง มีส่วนหลังคา**ลาดเอียง**ลงไปชั้นถัดไป |
| `<<<image_7>>>` | **Reptilian** สัตว์ประหลาดเขียวมะกอกยืนสองขา ตากลมส้ม (ตัวที่พุ่งชนแซม) |
| `<<<image_8>>>` | **แหวน** ทองอุ่น เพชรกลม หนามเตย 4 ขา — เรนเดอร์เป็น**แหวนจริงวงเดียว** ห้ามออกมาเป็นแผ่น prop sheet |

## Key constraints (จุดที่พังบ่อย)

- [ ] **หูฟัง** — คล้องคอเท่านั้น ขนาดพอดี **ห้ามครอบหู ห้ามใหญ่ ห้าม in-ear ห้ามมีสองอัน**
- [ ] **แขนขวาขาด** ซ้ายปกติ — ทุกช็อต
- [ ] **แหวนวงเดียว** ตรงกับ image_8 ห้ามเป็นแผ่น prop sheet ห้ามมีหลายวง
- [ ] **มือซ้าย** — ตอนเปิดฉากแซมถือแหวนด้วย**มือซ้าย** (ต่อจากซีนขอแต่งงาน)
- [ ] **แมรี่เจนต้องอยู่ในแบ็คกราวด์ตอนกลิ้ง** — เห็นหน้าตกใจชัดเจน ข้อนี้พังบ่อยสุด
- [ ] **เตะครั้งเดียว** — ห้ามเตะซ้ำ
- [ ] **โทนการ์ตูน** — ไม่มีเลือด ไม่มีบาดเจ็บ เอเลี่ยนแค่กระเด็นแบบตลก
- [ ] **คอร์กี้ตัวเดียว** สายรัดชมพู ห้ามหาย ห้ามซ้ำ

## Full prompt

```yaml
title: "Mary Jane MV — Scene 04D: The Tumble / Chasing the Ring Down"
reference_handling: "
  <<<image_1>>> = SAM face lock — brown spiky hair, brass goggles on forehead, brown eyes, sharp jaw, smudge on cheek. Lock this face exactly in every shot.
  <<<image_2>>> = SAM current look (TORN-SLEEVE VERSION) — short-sleeved grey shirt with the RIGHT sleeve fully torn off (right shoulder/upper arm bare, ragged armhole), LEFT sleeve intact; olive cargo shorts, brown boots, fingerless gloves, rucksack with the cloth JEWEL SACK on its strap. HEADPHONES per the sheet: a modest-sized clear retro pair with orange foam pads worn AROUND HIS NECK (hanging at the collarbones, NOT on his ears). Brass goggles on forehead. Match <<<image_2>>> exactly.
  <<<image_3>>> = Sam's Corgi — orange-tan and white, pink harness. Present, secondary.
  <<<image_4>>> = Mary Jane face lock — auburn short bob hair, small scar on cheek, brown eyes. Lock this face exactly.
  <<<image_5>>> = Mary Jane costume — green plaid shirt open over torn black top, denim shorts, katana, burgundy mary-jane sneakers. Her survivor look.
  <<<image_6>>> = environment — morning overcast rooftop cluster, pale grey-white sky, flooded city below; a sloped/ramped rooftop section dropping toward the next level.
  <<<image_7>>> = Reptilian — lean upright olive-green scaled creature, big orange round eyes; the harmless cartoon creature that tackles Sam. Render as needed.
  <<<image_8>>> = RING sheet — the gold diamond ring (warm gold band, round brilliant diamond, four-prong). The single real ring that gets knocked loose and bounces away down the slope; render as ONE real ring, NOT the prop-sheet panels/labels.
  HEADPHONE RULE: modest clear/orange-padded headphones AROUND SAM'S NECK only — never on/over the ears, never a large pair on the head, never in-ear/earbud, never duplicated.
  RIGHT SLEEVE RULE: Sam's right sleeve is torn off (right arm bare, ragged armhole), left sleeve intact — every shot (per <<<image_2>>>).
  TONE: stylized cartoon adventure action — playful comedic tumble, NO blood, NO injury, NO gore. Nobody hurt; the creature bounces comically.
  CONTINUITY: this picks up the instant after Sam, face-down at Mary Jane's feet, has proposed and is holding the ring up in his LEFT hand.
  Faces locked: Sam <<<image_1>>>, Mary Jane <<<image_4>>>."
style: "K-pop Demon Hunter anime — Solo Leveling visual quality, high-gloss stylized 3D animation. Stylized cartoon action, playful, no blood or injury. Morning overcast post-apocalyptic rooftop from <<<image_6>>>. Pale cool grey-white sky, desaturated muted tones."
visual_feel: "Sweet calm beat snaps into a sudden comedic tumble — Sam and a creature rolling down a sloped rooftop together, both lunging for the ring mid-roll, ending in a quick recovery and a chase. Dynamic, kinetic, playful. One rolling shot keeps Mary Jane's shocked face in the background. Light film grain."
duration: "15 seconds"

character_modeling:
  sam:
    base: "Face locked to <<<image_1>>>; look matches <<<image_2>>> exactly (right sleeve torn off / left intact; jewel sack; headphones around neck; goggles on forehead)."
    features: "Male late teens, sharp jaw, brown eyes, brown spiky hair. Right arm bare (ragged armhole), left sleeve intact. Olive cargo shorts, brown boots, fingerless gloves, rucksack with jewel sack. Modest clear/orange-padded headphones around the neck. Brass goggles on forehead."
    personality: "Earnest, scrappy, single-minded about the ring the second it gets away — recovers from chaos instantly and goes after it."
    movement_in_this_scene: "Lying propped at Mary Jane's feet, he holds the diamond ring up in his LEFT hand toward her, hopeful. Suddenly a creature leaps in and tackles him — the two ROLL together down the sloped rooftop, the ring knocked loose and bouncing away ahead of them. Mid-roll, Sam and the creature both lunge/grab for the tumbling ring. Sam gets his feet under him, recovers his footing out of the roll, and KICKS the creature away — then sprints off down the slope after the bouncing ring."
    emotional_state: "Hopeful proposal → comic shock as he's tackled → scrappy determination mid-roll → triumphant recovery kick → locked-on chase."
  sam_corgi:
    base: "Matching <<<image_3>>> — pink harness. Secondary."
    features: "Orange-tan and white Corgi, pink harness."
    movement_in_this_scene: "Beside Sam at the proposal; yelps as Sam is tackled and tumbles; bolts down the slope after Sam and the ring."
  mary_jane:
    base: "Face locked to <<<image_4>>>; costume per <<<image_5>>>."
    features: "Female, auburn short bob, small scar on cheek, brown eyes. Green plaid shirt over torn black top, denim shorts, katana, burgundy mary-jane sneakers."
    movement_in_this_scene: "Standing over Sam during the proposal beat; when the creature tackles him she startles, a SHOCKED expression. In the rolling shot she is seen in the BACKGROUND behind the tumbling pair — facing toward camera/them, shocked face clearly readable, reaching out a beat too late."
  reptilian_figure:
    base: "Matching <<<image_7>>> — lean olive-green scaled creature, orange round eyes."
    movement_in_this_scene: "Leaps in and tackles Sam, rolling down the slope tangled with him, also lunging for the shiny ring mid-roll; gets comically kicked away when Sam recovers, bouncing off. No harm shown."

cinematic_storyboard:
  00_03_proposal_hold_then_hit:
    camera: "Low warm angle past Mary Jane on Sam holding the ring up; then a sudden WIDE as the creature leaps in."
    action: "Continuing from the proposal: Sam lies propped at Mary Jane's burgundy sneakers (<<<image_5>>>), holding the diamond ring (<<<image_8>>>) up in his LEFT hand toward her, hopeful grin. She looks down, touched. Then — cut WIDE — out of nowhere a lean creature (<<<image_7>>>) LEAPS into frame and tackles Sam. Mary Jane startles, shocked."
    lighting: "Soft warm morning overcast on the pair, flattening as the wide hits."
    sfx: "Sam's hopeful breath, then a sudden whoosh-THUMP of the tackle, Mary Jane's gasp, music jolting."
  03_07_roll_down_slope_mj_behind:
    camera: "Travelling/rolling camera tumbling WITH Sam and the creature down the sloped rooftop — framed so Mary Jane stays in the BACKGROUND, her shocked face clearly visible behind the tumbling pair."
    action: "Sam and the creature ROLL together down the sloped rooftop section (<<<image_6>>>), tangled and tumbling. The diamond ring (<<<image_8>>>) is knocked loose and bounces away ahead of them, glinting. Behind the rolling pair, up the slope, Mary Jane is seen reaching out with a shocked face. The corgi scrambles after them."
    lighting: "Pale morning light spinning with the tumble."
    sfx: "Bodies rolling and thumping, the ring pinging on concrete, Mary Jane's distant shocked call, the corgi yipping."
  07_10_both_lunge_for_ring:
    camera: "Tighter on the tumbling pair — quick beat catching both reaching."
    action: "Mid-roll, BOTH Sam and the creature lunge and grab for the bouncing diamond ring (<<<image_8>>>) — fingers and claws swiping at it as it skips just out of reach down the slope. A comedic scramble, neither getting it yet."
    lighting: "Pale morning light, ring glinting between them."
    sfx: "Grunts and chitters, the ring pinging just ahead, comedic scramble stings."
  10_12_recover_and_kick:
    camera: "Handheld snapping upright as Sam recovers — punchy on the kick."
    action: "Sam gets his feet under him and recovers out of the roll into a low crouch; he plants and lands ONE solid comedic KICK on the creature, sending it bouncing away off the slope. Playful cartoon hit — no harm, the creature just tumbles off comically."
    lighting: "Pale morning light, dynamic with the motion."
    sfx: "A comic 'thwack/boing' kick, the creature's yelp tumbling away, music driving."
  12_15_sprint_after_ring:
    camera: "Handheld follow from behind/three-quarter as Sam takes off downhill after the ring."
    action: "Sam locks onto the diamond ring (<<<image_8>>>) still bouncing away down the slope and SPRINTS after it — right arm bare, headphones at neck, goggles on forehead, corgi bolting alongside. End on Sam in full chase, the ring skipping ahead down toward the next rooftop level, Mary Jane's rooftop now behind/above."
    lighting: "Flat pale morning overcast, soft and even."
    sfx: "Fast boot impacts, corgi paws, ring pinging ahead, wind, driving music carrying into the chase."

production_notes:
  audio_design: "A warm hopeful note on the proposal hold, jolted by a sudden tackle sting; rolling/tumbling sounds with the ring pinging through; a comedic scramble; a punchy kick sting; then fast driving chase music as Sam sprints after the ring. Playful, never tense."
  subtext: "He proposed — and the universe immediately tackled him down a slope. The ring's loose again and he's not letting a monster have it."
  critical_constraint: "CONTINUITY: opens exactly on Sam face-up/propped at Mary Jane's feet holding the diamond ring (<<<image_8>>>) up in his LEFT hand, just after proposing. BEATS IN ORDER: (1) proposal hold; (2) a lean creature (<<<image_7>>>) LEAPS in and tackles Sam → cut wide, Mary Jane shocked; (3) Sam and the creature ROLL together down the sloped rooftop, the ring knocked loose and bouncing away — in this rolling shot Mary Jane is in the BACKGROUND behind them with a clearly shocked face; (4) mid-roll BOTH Sam and the creature lunge/grab for the ring; (5) Sam recovers his footing and lands ONE comedic KICK that bounces the creature away; (6) Sam sprints off down the slope after the bouncing ring — END on the chase. TONE: stylized cartoon action — playful comedic tumble, creature bounces, NO blood, NO injury, NO gore. RING = single real ring matching <<<image_8>>>, never prop-sheet panels/labels; only ONE ring. Sam: right sleeve torn off / left intact (per <<<image_2>>>), headphones AROUND NECK (modest, never on ears/in-ear), goggles on forehead. Faces locked: Sam <<<image_1>>>, Mary Jane <<<image_4>>>; her costume per <<<image_5>>>. Setting matches <<<image_6>>>, ONE continuous live space, never sheet panels/labels/swatches. EXACTLY ONE hero corgi (pink harness), secondary."
  avoid: "Any blood, wounds, injury, gore, or graphic violence (tackle, roll, and kick all playful and cartoonish; creature merely bounces); the rolling shot NOT keeping Mary Jane visible/shocked in the background; the ring not matching <<<image_8>>> or appearing as prop-sheet panels/labels; more than one ring; more than one kick (exactly one recovery kick); Sam holding the ring in the wrong hand at the start (it is his LEFT hand from the proposal); headphones on/over Sam's ears, a large pair on his head, in-ear/earbud, or duplicated headphones; headphones not around the neck; right sleeve intact (must be torn off, left intact); Sam's outfit deviating from <<<image_2>>>; identity drift on either face; the corgi missing or duplicated; jitter beyond intentional handheld, bent or distorted limbs, temporal flicker."
```

## Beat sheet

| Time | Beat | สิ่งที่เกิด |
|---|---|---|
| 00–03 | Proposal → Hit | แซมชูแหวนมือซ้าย → ตัด WIDE เอเลี่ยนพุ่งชน แมรี่เจนตกใจ |
| 03–07 | Roll down slope | กลิ้งลงหลังคาลาดด้วยกัน แหวนกระเด็นนำหน้า **แมรี่เจนอยู่แบ็คกราวด์หน้าตกใจ** |
| 07–10 | Both lunge | ทั้งคู่คว้าแหวนกลางกลิ้ง คว้าไม่ทันทั้งคู่ |
| 10–12 | Recover + kick | แซมตั้งหลักย่อ → **เตะ 1 ที** เอเลี่ยนกระเด็นตกไป |
| 12–15 | Sprint | วิ่งไล่แหวนลงเนิน คอร์กี้วิ่งตาม จบที่กำลังไล่ |

## Run log

| วันที่ | Tool | ผล | ปัญหาที่เจอ |
|---|---|---|---|
|  |  |  |  |

## Notes


---
[[Action]] · [[Home]]

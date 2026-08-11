---
title: Vampire Hunt — The Surge
category: Action
tags:
  - prompt/video
  - category/action
  - subgenre/supernatural
  - subgenre/fight-choreography
  - technique/reference-to-video
  - technique/speed-ramp
tool: Seedance 2.5
duration: 30s
aspect: "16:9"
references: 3
status: draft
rating: 
created: 2026-08-09
---

# Vampire Hunt — The Surge

> [!abstract] สรุป
> แวมไพร์หนุ่มบุกเดี่ยวใส่กลุ่มนักล่าในลานตู้คอนเทนเนอร์กลางฝน — 30 วินาทีเป็น **การเคลื่อนที่ทางเดียวจากซ้ายไปขวา** ไม่มีหยุด ไม่มีถอย จบที่กัดคอตัวสุดท้ายแล้วหายใจเข้ากล้องหนึ่งครั้ง

## Reference images

| Slot | ใช้เฉพาะ | ห้ามลอก |
|---|---|---|
| `<<<image_1>>>` | ใบหน้าพระเอก — โครงหน้า, ตา, ผมหน้าม้าดำหนา, ผิวขาวซีด | ท่า headshot ตรงหน้าพื้นขาว |
| `<<<image_2>>>` | เสื้อผ้า — trench coat หนังดำ, mock-neck เทา, กางเกงดำ | ท่ายืนนิ่งปล่อยแขนหน้าฉากเทา |
| `<<<image_3>>>` | โลเคชั่น — ลานตู้คอนเทนเนอร์เปียกฝน, ไฟโซเดียมดวงเดียว | ภาพ wide เปล่าๆ / มุมสูงไกล |

## Key constraints (จุดที่พังบ่อย)

- [ ] **ทิศทาง** — พระเอกอยู่ซ้าย วิ่งไปขวา นักล่าอยู่ขวาทั้งหมด **ไม่มีใครอยู่ข้างหลังเขา**
- [ ] **ลูกธนู** — บินขวา→ซ้ายเสมอ และ**ต้องเห็นคนยิงอยู่ในเฟรมเดียวกัน** ห้ามยิงจากนอกจอ
- [ ] **ความเร็ว** — ต้องเป็น blur ไม่ใช่วิ่ง ห้ามเห็น stride cycle ปกติของมนุษย์
- [ ] **การขึ้นที่สูง** — เหยียบรถเข็นเหล็กเท่านั้น **ห้าม wall run / ปีนตู้**
- [ ] **การกัด** — กัด**ข้างคอใต้กราม** หน้าเหยื่อหันออก **ห้ามปากชนปาก / ห้ามเฟรมคล้ายจูบ**
- [ ] **ใบหน้า** — ไม่มีแผลตลอดคลิป เลือดขึ้นหน้าได้เฉพาะที่ปาก/คาง/เขี้ยว หลังกัดเท่านั้น
- [ ] **ตา** — ม่านตาแดงอย่างเดียว ตาขาวต้องขาวสะอาด ห้ามแดงทั้งลูก
- [ ] **กล้อง** — กล้องช้าและนิ่ง ความเร็วมาจากตัวละครล้วนๆ ห้าม whip camera

## Full prompt

```yaml
title: "Vampire Hunt — The Surge"
reference_handling: "CRITICAL: <<<image_1>>> is used STRICTLY for the hero's facial identity — bone structure, eye shape, thick messy black fringe, pale porcelain skin, full lips. <<<image_2>>> is used STRICTLY for wardrobe — distressed black leather trench coat, charcoal grey mock-neck top, black trousers. <<<image_3>>> is used STRICTLY for location design — rain-soaked industrial container yard at night, corrugated steel warehouse walls, stacked shipping containers, chain-link gate, single overhead sodium lamp, rusted flatbed cart, black mirror puddles. DO NOT reproduce <<<image_1>>>'s frontal passport-style headshot on white background. DO NOT reproduce <<<image_2>>>'s static standing pose with arms hanging at sides against flat grey studio backdrop. DO NOT reproduce <<<image_3>>> as an empty establishing wide, and DO NOT copy its distant high-corner vantage — the camera stays close to the hero at all times, near enough that his face and hands read clearly. This clip opens MID-FIGHT: contact is already happening in frame one."
style: "Brutal supernatural action cinema. John Wick fight geography meets Blade night-horror grain. Teal-black night grade with sodium-orange practicals. 35mm film tone, anamorphic."
visual_feel: "Rain-soaked and reflective. Handheld weight with real momentum. One unbroken surge of violence moving in a single direction — every movement grows out of the previous one with no reset and no pause. Full-speed action carries heavy directional motion blur and water spray; the single micro-slow beat is razor-sharp by contrast. Heavy film grain, volumetric mist through lamp cones."
duration: "30 seconds"

spatial_geography:
  screen_direction: "LOCK THIS FOR THE WHOLE CLIP. The hero starts on the LEFT side of frame and drives RIGHT. Every hunter is on the RIGHT side, in the deeper half of the yard by the chain-link gate. He never reverses direction, never retreats left, never has anyone behind him."
  threat_direction: "Every attack comes from the RIGHT — the direction he faces and moves toward. All crossbow bolts fly RIGHT-TO-LEFT, from the hunters toward the hero. NO projectile ever enters frame from behind him, from the left edge, or from off-screen on the side away from the hunters. When a bolt is fired, the shooter who fires it is VISIBLE IN THE SAME FRAME on the right side, crossbow raised, so the origin of the shot is never ambiguous."
  jump: "There is NO wall run, NO climbing, NO vertical scaling of any container. He gains height by stepping on a solid object at ground level mid-sprint — the rusted flatbed cart — and launching himself forward and up through the air, still travelling RIGHT toward the hunters."

character_modeling:
  hero_vampire:
    base: "Young East Asian male vampire. Face matching <<<image_1>>> — sharp jaw, thick messy black fringe falling over the brow, pale porcelain skin, full lips, high cheekbones. Wardrobe matching <<<image_2>>> — distressed black leather trench coat to mid-calf, charcoal grey mock-neck, black trousers, black boots."
    state_in_this_scene: "Already deep into the fight. Coat soaked through and hanging heavy, arterial spray streaked across the left shoulder of the leather, right sleeve red to the elbow. Hair plastered wet. Fangs already fully extended. Bodies already down in the puddles behind him."
    eyes: "ONLY THE IRIS IS RED. Burning arterial red with a faint inner glow, pupil narrowed to a vertical slit. The sclera stays clean white at all times — NO red veining, NO bloodshot whites, NO full-eye red."
    face_rule: "His face stays completely unbroken for the entire clip — no cuts, no scratches, no bruises, no dirt, no blood on cheeks, brow, forehead, or nose. The ONLY blood permitted on his face appears after the bite: fresh red on his lips, chin, and the edges of his fangs. Nowhere else, and never before that moment."
    regeneration: "Any cut on his skin closes on its own within one second — edges knitting shut, blood line vanishing into unbroken porcelain. He never touches a wound or reacts to it."
    speed: "THIS IS THE DEFINING TRAIT AND IT MUST READ ON SCREEN. He does not jog, does not climb, does not take visible running strides. When he crosses ground he becomes a low blurred surge — twelve meters in a fraction of a second, three ground contacts total for the whole distance, a wall of water erupting behind him in a rooster tail, his coat snapped straight out horizontally behind him by the speed. Hunters' heads whip around too late and find empty air. Then he stops dead, perfectly still, no deceleration and no stumble. The contrast between the blur and the stillness is what sells him — never an ordinary human tempo in between."
    kill_style: "His attacks destroy anatomy. He tears limbs off at the joint, folds knees and elbows backward, twists heads past the spine, drives objects through skulls. Every kill is one motion — grab, break, release, gone. He never trades blows, never blocks twice, never grapples."
    movement_in_this_scene: "He NEVER walks casually. He NEVER climbs or scales anything. He NEVER stands with arms at his sides. He NEVER appears as a small distant figure in a wide yard. He is swinging, surging, airborne, landing, or killing in every shot until the final beat."
    emotional_state: "Predatory calm. Relaxed inside the violence. No strain, no anger, no showmanship."
  hunters:
    base: "Remaining vampire hunters, mixed male and female, clustered on the RIGHT in the deep half of the yard. Weathered tactical coats, leather harnesses, oilcloth capes, fingerless gloves, wet hair plastered to faces."
    features: "Curved single-edge swords, short-handled iron axes, crossbows loaded with black iron bolts. Wooden stake sheaths across their chests. Faces tight with fear now, breath fogging hard."
    physics: "Ordinary human speed — heavy, committed, telegraphed, visibly a full tier slower than the hero. When broken they go fully ragdoll, limbs hanging wrong, water exploding on landing."
    movement_in_this_scene: "They hold the right side of the yard and are killed one or two at a time as he drives into them. None of them ever gets behind him."

cinematic_storyboard:
  00_04_the_whip:
    camera: "Handheld medium, tracking with him as he turns. Close, steady."
    action: "Opens on contact. He blurs into an axeman's guard on his right, clamps a hand around the forearm, and whips the entire body off its feet in a flat horizontal arc — boots leaving the ground, water tearing off in a spiral — and hammers him into a swordsman closing in from further right. Both bodies fold together and skid into a puddle. He releases the arm and his own rotation carries him forward without a pause, already facing the rest of them."
    lighting: "Sodium cone above and ahead, hard rim on wet leather, black dead zones behind."
    sfx: "Shoulder joint popping, two bodies colliding, deep steel boom, water blast."

  04_06_the_surge:
    camera: "Low tracking shot at knee height, moving right with him. Smooth, one axis."
    action: "He drops low and detonates forward to the RIGHT. Not a run — a blurred surge across twelve meters of wet asphalt with only three boot contacts, each one blasting a sheet of water into the air behind him. His coat snaps straight out horizontally. A hunter swings a sword through the space he already left. Ahead on the right, a crossbowman braces and starts bringing his stock up."
    lighting: "Sodium lamp streaking past overhead, wet ground flaring with reflected light in his wake."
    sfx: "Three explosive water impacts in rapid succession, air tearing, a sword whistling through nothing."

  06_08_the_launch:
    camera: "Side-on at ground level, panning right to stay with him. Controlled."
    action: "Mid-surge he plants one boot on the top rail of the rusted flatbed cart and LAUNCHES — the cart rocking hard on its wheels, rust flaking off, water bursting off the rail — throwing himself forward and up into the air, still travelling right, coat opening wide behind him. On the right side of the frame the crossbowman drops to one knee, locks the stock into his shoulder, and aims up at him."
    lighting: "Backlit by the sodium lamp as he rises across it, rain streaking through the beam."
    sfx: "Boot on steel rail, cart frame rocking, coat snap, crossbow string ratcheting."

  08_11_the_air_dodge:
    camera: "Side-on wide-medium, perpendicular to the shot line. Hero airborne LEFT of frame, kneeling shooter on the RIGHT, both in frame together. Slow drift in."
    action: "MICRO-SLOW. The bolt leaves the crossbow on the right and crosses the frame RIGHT-TO-LEFT toward the hero's chest — the full flight path visible, shooter and target in the same shot, water shedding off the spinning shaft in a spiral. Airborne and rotating, the hero twists his torso hard, spine arching, coat wrapping around him, and the shaft passes a hand's width from his ribs. His right hand comes across his body and closes around it mid-flight. Red irises inside clean white sclera track it the whole way. Rain hangs suspended around him."
    lighting: "Rim-lit from the lamp above, face lit from below by wet ground bounce."
    vfx: "Micro-slow at quarter speed. Suspended raindrops drifting. Snaps to full speed the instant his fingers close."

  11_13_the_return:
    camera: "Fast follow behind the thrown bolt, travelling LEFT-TO-RIGHT toward the kneeling shooter."
    action: "Full speed. Still airborne, he snaps his arm and hurls the bolt back along the exact line it came from. The camera rides it right across the yard — rain tearing past, the kneeling shooter rushing up to meet it — and it punches through his throat and out the back of his neck, knocking him off his knee flat onto his back in a puddle. The crossbow clatters away."
    lighting: "Bolt catching sodium light along its shaft. Shooter lit hard by the overhead lamp as it arrives."
    sfx: "Air tear, wet punch-through, body into water, crossbow clatter."

  13_17_landing_kill:
    camera: "Whip down to ground level beside the landing point, then hold low."
    action: "He drops into frame and lands in a full crouch right beside the man he just killed, one hand flat in the puddle, water blasting out in a ring — his airborne rotation carrying straight into the movement with no pause. A swordswoman is already swinging down at him. Without rising he catches her ankle, rips her off her feet, and slams her spine-first across the buckling frame of the flatbed cart. He rises out of the crouch in the same motion."
    lighting: "Hard sodium key from above, his shadow thrown long across the wet asphalt."
    sfx: "Water ring, ankle joint tearing, spine on steel, metal buckling."

  17_22_two_more:
    camera: "Over-the-shoulder from directly behind him, pushing right with him."
    action: "He keeps driving right without pausing. The first of two hunters swings an axe; he takes it out of the air, buries it in the man's own skull with one downward drive, and lets go of the handle before the body falls. The second reaches him mid-step; he catches the wrist, folds the arm backward at the elbow with a wet snap, and drives the man face-first into the corrugated steel hard enough to leave a dent — never breaking stride."
    lighting: "Sodium pool ahead of him, both hunters lit, his back in silhouette."
    sfx: "Axe into bone, elbow reversing, skull on steel, two bodies into water."

  22_27_the_neck_bite:
    camera: "Behind the victim's right shoulder, looking past his jaw at the exposed left side of his throat. Slow arc in, holding the throat in frame."
    action: "The last hunter stumbles back and the hero is simply already there. He grips the man's shoulder and the top of his head and forces the head hard to one side and back — chin lifted, the side of the neck stretched open and fully exposed, the victim's face turned completely AWAY from the hero. The hero's mouth goes to the SIDE OF THE NECK, low under the jaw over the carotid, and his fangs sink into the skin there. Blood runs down the collar. He holds two full seconds, throat working once, then opens both hands and lets the body drop straight down into the puddle at his feet."
    lighting: "Backlit rim through the rain, wet specular along the stretched throat, faces mostly in shadow."
    sfx: "Fangs breaking skin, one wet swallow, the body hitting water. Rain returns underneath."

  27_30_the_breath:
    camera: "Medium close-up, low angle. Locked off. Hold."
    action: "He straightens. His face is completely unmarked — clean pale skin, no cuts, no dirt — except for fresh red across his lips and chin and along the edges of his fangs. Red irises inside clean white sclera. He turns his face into the lens and takes one slow breath: chest rising, nostrils flaring slightly, a plume of fog leaving his mouth into the cold rain. His expression does not change. No smile. Cut on the held frame."
    lighting: "Backlit by the sodium lamp, face lit mostly by the red glow of his own irises."
    sfx: "Rain on corrugated steel. One long inhale and exhale. Silence underneath."

production_notes:
  continuity: "This must read as ONE unbroken surge, not a series of separate shots. Every beat begins from the exact body position and momentum the previous beat ended on — the throw becomes the sprint, the sprint becomes the launch off the cart, the launch becomes the airborne dodge, the dodge becomes the throw-back, the fall becomes the landing crouch, the crouch becomes the next kill. No cutaways, no resets to a neutral stance, no repositioning, and he never stops moving until the bite."
  speed_rendering: "The hero's superhuman speed must be visible, not implied. Sell it with: extreme directional motion blur on his body while the background stays readable, water erupting in sheets behind each of the three ground contacts, his coat pinned horizontal by airspeed, hunters reacting a full beat late and swinging at empty space, and dead-stop stillness at the end of each burst with zero deceleration. Per speed asymmetry the CAMERA stays slow and controlled throughout — the speed comes entirely from the subject, never from whipping the camera."
  audio_design: "00-04: joints popping, bodies on steel, rain roar under everything. 04-08: three explosive water impacts, air tearing, cart rocking, crossbow ratchet. 08-11: strips to a low sub-bass drone and a suspended bolt whistle, rain reduced to a distant hiss. 11-13: hard slam back to full — air tear, wet punch-through. 13-22: layered anatomical violence, no score, only rhythm. 22-27: everything drops away to the bite. 27-30: rain on steel and one long breath."
  lighting: "Single overhead sodium lamp as the only warm source. Everything else cold teal moonlight and reflected wet-ground bounce. Deep pools of black between light sources that he blurs through."
  subtext: "He is not defending a position — he is crossing one. The whole clip moves in a single direction and the last hunter is simply where the movement stops."
  critical_constraint: "SPEED: superhuman blur is mandatory in the 04-08s surge — no jogging, no visible stride cycle, no ordinary human tempo anywhere. NO WALL RUN, NO CLIMBING: he gains height only by stepping on the rusted flatbed cart at ground level and launching forward. BOLT DIRECTION: the hero moves LEFT to RIGHT, all hunters are on the RIGHT, and every bolt flies RIGHT-TO-LEFT with the firing shooter visible in the same frame — nothing is ever fired from behind him or from the left. BITE: fangs enter the SIDE OF THE NECK under the jaw, victim's head forced away and chin up with the throat exposed. The hero's mouth must NEVER touch the victim's mouth, lips, cheek, or face — this is a throat bite from the side, never face-to-face, never anything resembling a kiss. FACE: zero damage all clip; the only blood is on his lips, chin, and fangs after the bite. EYES: red iris only, sclera clean white. CAMERA SCALE: never a distant high wide of a small figure. ENDING: one breath into the lens, no smile, no pose."
  avoid: "Jitter, bent or distorted limbs on the hero, temporal flicker, identity drift, red or bloodshot sclera, any wound or blood on his cheeks brow forehead or nose, hero jogging or running at normal human speed, visible ordinary stride cycle, hero climbing or wall-running or scaling a container, projectiles entering frame from behind or from the left, enemies positioned behind the hero, bolts fired by an unseen off-screen shooter, mouth-to-mouth or face-to-face contact during the bite, biting the lips cheek or face, kiss-like framing, distant high-angle wide shots where the hero is small in frame, cutaways that break momentum, hero pausing between moves, slow-motion outside the single specified beat, victory pose or smile at the end."
```

## Beat sheet

| Time | Beat | สิ่งที่เกิด |
|---|---|---|
| 00–04 | The Whip | เหวี่ยงคนถือขวานฟาดใส่คนถือดาบ |
| 04–06 | The Surge | พุ่ง 12 เมตร แตะพื้น 3 ครั้ง |
| 06–08 | The Launch | เหยียบรถเข็นกระโดดขึ้นอากาศ |
| 08–11 | The Air Dodge | **micro-slow** บิดตัวหลบ คว้าลูกธนูกลางอากาศ |
| 11–13 | The Return | ขว้างกลับ ทะลุคอคนยิง |
| 13–17 | Landing Kill | ลงย่อ กระชากข้อเท้า ฟาดหลังใส่รถเข็น |
| 17–22 | Two More | ขวานปักหัวเจ้าของ + หักศอกอัดหน้าใส่ผนังเหล็ก |
| 22–27 | The Neck Bite | กัดข้างคอ ค้าง 2 วิ ปล่อยร่างลง |
| 27–30 | The Breath | หายใจเข้ากล้อง 1 ครั้ง ไม่ยิ้ม |

## Run log

| วันที่ | Tool | ผล | ปัญหาที่เจอ |
|---|---|---|---|
|  |  |  |  |

## Notes


---
[[Action]] · [[Home]]

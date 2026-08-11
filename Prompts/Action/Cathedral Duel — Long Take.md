---
title: Cathedral Duel — Long Take: Gun and Blade Continuous
category: Action
tags:
  - prompt/video
  - category/action
  - subgenre/supernatural
  - subgenre/fight-choreography
  - technique/reference-to-video
  - technique/oner
  - technique/dual-character
tool: Seedance 2.5
duration: 15s
aspect: "16:9"
references: 5
status: draft
rating: 
created: 2026-08-09
---

# Cathedral Duel — Long Take

> [!abstract] สรุป
> ดวลกันกลางโบสถ์โกธิค — **Silver Blade** (ดาบคาตานะ) ปะทะ **Blood Moon** (ปืนคู่) 15 วินาที **ลองเทคเดียวไม่มีตัด** 18 การปะทะ ทุกนัดที่ยิงต้องมีการรับ ทุกดาบที่ฟันต้องมีการบล็อก

## Reference images

| Slot | ใช้เฉพาะ |
|---|---|
| `<<<image_1>>>` | **Silver Blade — หน้า** ชายเอเชีย ผมแพลตินัมเงิน ตาเทาเงิน ผิวซีดเย็น |
| `<<<image_2>>>` | **Silver Blade — ชุด** โค้ทโกธิคยาวถึงพื้นสีถ่าน ขาดเป็นรอยฟัน คราบเลือดแห้ง บู๊ทหัวเข็มขัดสูงถึงเข่า ถือคาตานะ |
| `<<<image_3>>>` | **Blood Moon — หน้า** ชายเอเชีย ผมฟ้าเหล็กอ่อน ม่านตาแดงเลือดหมู ต่างหูห่วงหูซ้าย |
| `<<<image_4>>>` | **Blood Moon — ชุด** โค้ทแดงไวน์ยาวเหนือเข่า เชิ้ตถ่านเปิดคอ กางเกงหนังดำ **ปืนเงินสลัก 2 กระบอก สองมือเสมอ** |
| `<<<image_5>>>` | **โลเคชั่น** โบสถ์ Cathedral of Sacred Blood — เนฟโกธิค เสาหิน กระจกสีแดงเข้ม แสงแดงสาดพื้นหินเปียก แท่นบูชาปลายทาง เทียนริมทางเดิน หมอกเย็นระดับพื้น |

**ห้าม** ให้ตัวละครยืนท่านิ่งแบบรูป reference

## Key constraints (จุดที่พังบ่อย)

- [ ] **ลองเทคเดียว** — ห้ามตัด ห้าม jump cut กล้อง handheld เคลื่อนตลอด แต่ห้ามหลุดทั้งสองคนออกจากเฟรมพร้อมกัน
- [ ] **ปืนคู่เด็ดขาด** — Blood Moon ถือปืน **2 กระบอก ทุกเฟรม** ห้ามเหลือกระบอกเดียว ห้ามเก็บเข้าซอง
- [ ] **ตรรกะปืน-ดาบ** — ยิงทุกนัด Silver Blade ต้องตอบ (ปัดด้วยดาบ/หลบ) ฟันทุกครั้ง Blood Moon ต้องตอบ (บล็อกด้วยปืน/ปัด/หลบ) **ไม่มีนัดไหนหรือดาบไหนที่ไม่มีการตอบ** — นี่คือแก่นของฉาก
- [ ] **ระยะกล้าง** — medium-close ตลอด เห็นทั้งคู่ในเฟรมเดียวกันเกือบทุกบีต
- [ ] **สโลว์โมชั่น** — เฉพาะบีต 9 กับบีต 15 เท่านั้น
- [ ] **ไม่มีดนตรี** — foley ล้วน เสียงหายใจใกล้ๆ คือแกนอารมณ์
- [ ] **ไม่มีตัวประกอบ** — ไม่มีศพ ไม่มีฝูงชน มีแค่สองคน

## Full prompt

```yaml
title: "CATHEDRAL DUEL — LONG TAKE: GUN AND BLADE CONTINUOUS"

reference_handling: "
  <<<image_1>>> = Silver Blade face lock — Asian male, silver-white platinum hair, silver-grey eyes, pale cold skin.
  <<<image_2>>> = Silver Blade character sheet — torn floor-length charcoal gothic coat, slash damage, dried bloodstains, leather strap belt system, knee-high buckle boots, katana drawn in hand.
  <<<image_3>>> = Blood Moon face lock — Asian male, light steel blue hair, deep crimson red irises, hoop earring left ear, natural photographic skin texture.
  <<<image_4>>> = Blood Moon character sheet — burgundy wine-red mid-thigh coat, dark charcoal shirt open at collar, black leather pants, knee-high boots, TWO ornate silver pistols both hands always, black half-finger gloves.
  <<<image_5>>> = Cathedral of Sacred Blood location sheet — Gothic nave, stone columns, deep red stained glass, red light pools on wet dark stone floor, altar far end, candles side aisles, cold mist floor level.
  <<<image_1>>>–4 STRICTLY CHARACTER DESIGN ANCHORS. <<<image_5>>> STRICTLY ENVIRONMENT ANCHOR.
  DUAL PISTOLS ABSOLUTE: Blood Moon holds TWO ornate silver pistols — one each hand — in every single frame. Never one gun. Never holstered. Non-negotiable.
  THIS IS A CONTINUOUS LONG TAKE — no cuts. One unbroken camera movement tracking both characters at medium-close range throughout the entire 15 seconds.
  GUN-SWORD LOGIC ABSOLUTE: every gunshot triggers immediate visible response from Silver Blade — blade deflect or body dodge. Every sword strike triggers immediate visible response from Blood Moon — gun block, gun parry, or body dodge. No weapon fires or strikes without a counter. This is the entire logic of the scene.
  DO NOT show either character in neutral standing reference poses."

style: "High-budget vampire action cinema. John Wick Chapter 4 corridor fight — continuous single-take, handheld, medium-close range. Two combatants who never stop moving. Gothic cathedral. Photorealistic 4K. The camera is a third participant — it moves with them, circles them, never cuts away."

visual_feel: "Handheld with controlled micro-shake — never stabilizes to tripod smoothness, never chaotic. Medium-close range throughout — both characters in frame simultaneously in most beats. Red stained glass ambient dominant. Film grain in shadows. Fast action paired with controlled camera — camera slightly slower than the action, always catching up. Micro slow-motion only on beat 9 and beat 15. Every strike and shot has physical weight."

duration: "15 seconds"

character_modeling:
  silver_blade:
    base: "Matching <<<image_1>>> face lock and <<<image_2>>> character sheet."
    features: "Asian male 25–30. Silver-white platinum hair. Silver-grey eyes, cold. Pale skin, natural photographic pore texture. Torn floor-length charcoal gothic coat — slash tears, dried bloodstains left lapel. Leather strap belt system. Knee-high buckle boots. Katana drawn — blade out, in hand, entire clip."
    movement_in_this_scene: "Silver Blade never stops moving between strikes — constant footwork, weight shifting, stance adjustments. Deflections are committed single-arm movements — the full force of the parry visible. Dodges are minimal: a head turn, a body twist, a crouch — not theatrical leaps. Every response to a gunshot is immediate and physically specific. His expression never changes — zero throughout."
    emotional_state: "Pure combat state. No thought, no strategy visible — three centuries of muscle memory executing. Cold."

  blood_moon:
    base: "Matching <<<image_3>>> face lock and <<<image_4>>> character sheet."
    features: "Asian male 25–30. Light steel blue hair. Deep crimson red irises — wine-dark red. Hoop earring left ear. Natural photographic skin texture. Burgundy wine-red mid-thigh coat. Dark charcoal shirt open two buttons. Black leather pants. Black half-finger gloves. TWO ornate silver pistols — vine-and-thorn engraving — one in each hand throughout entire clip without exception."
    movement_in_this_scene: "Blood Moon fires selectively — never sprays. Each shot is placed. His gun parries use the barrels as physical blocking surfaces — he does not fire during parries, he uses the guns as hard objects. Dodges are economical: duck, step, pivot. He fires both guns simultaneously on beats 5 and 13. He fires single shots on beats 1, 3, 7, 9, 11. Both guns always present, always visible."
    emotional_state: "Focused. The smile is gone. He is in it."

cinematic_storyboard:
  00_01_beat1_gun_deflect:
    camera: "Handheld medium-close, both characters visible. Slow push-in from the left."
    action: "Blood Moon on RIGHT raises LEFT pistol — fires one shot LEFT toward Silver Blade. Silver Blade on LEFT — katana swings RIGHT in a sharp deflection arc, blade catching the bullet. Sparks spray RIGHT from the contact point. Silver Blade's arm fully extended on the deflection — the force visible in his shoulder. Both pistols still in Blood Moon's hands — right pistol lowered, left pistol raised post-fire."
    lighting: "Muzzle flash — brief white-gold left side. Deflection spark — white-gold right. Red stained glass ambient dominant."
    sfx: "Gunshot — sharp, cathedral reverb. Blade-on-bullet — metal ring. Spark hiss. Both breathing — close, controlled."

  01_02_beat2_sword_gun_block:
    camera: "Handheld, circling slightly RIGHT, maintaining medium-close."
    action: "Silver Blade steps forward immediately — katana driving in a diagonal strike toward Blood Moon's right side. Blood Moon raises BOTH pistols simultaneously, crossing them — left barrel over right — catching the blade on the crossed barrels. The impact stops the sword. Blood Moon's arms absorb the force — elbows bending then locking. Both gun barrels pressing up against the katana blade. Silver Blade pressing down. Standoff for 0.5 seconds."
    lighting: "Spark at blade-on-barrels contact — white-gold center frame. Red ambient on both faces."
    sfx: "Blade on crossed barrels — hard doubled metal ring. Both feet adjusting on wet stone — footwork sound. Strain breathing."

  02_03_beat3_undershot_jump:
    camera: "Handheld drops slightly lower, following the action."
    action: "Blood Moon breaks the block — angles BOTH pistols DOWNWARD, firing LEFT pistol once under the locked blade toward Silver Blade's legs. Silver Blade responds: jumps — both feet leaving the stone floor, clearing the low shot. The bullet skips off the wet stone floor beneath him — small spark at floor level. Silver Blade lands immediately, weight forward."
    lighting: "Muzzle flash downward — white-gold low. Floor spark at bullet skip. Red ambient."
    sfx: "Gunshot low — sharp. Bullet on wet stone — flat crack. Silver Blade's jump and landing — fabric displacement, boot impact on wet stone."

  03_04_beat4_aerial_slash_gun_block:
    camera: "Handheld tilts up slightly following Silver Blade's downward strike."
    action: "Silver Blade's forward landing momentum converts directly into a downward diagonal slash — bringing the katana down hard toward Blood Moon's left shoulder. Blood Moon raises RIGHT pistol up and LEFT — barrel vertical, catching the blade on the side of the slide. The impact drives his right arm down — he absorbs it, knees bending slightly under the force. Left pistol remains ready at his side."
    lighting: "Spark on blade-on-slide contact — small, sharp. Red ambient. Both faces visible at medium-close."
    sfx: "Blade on pistol slide — sharp metallic impact, higher pitch than barrel contact. Blood Moon's knee bend — fabric compression. Both exhales on impact."

  04_05_beat5_double_shot_double_deflect:
    camera: "Handheld steps back slightly — widening to show full upper bodies."
    action: "Blood Moon fires BOTH pistols SIMULTANEOUSLY — right gun and left gun at the same instant, both aimed at Silver Blade's torso. Silver Blade spins his katana in a rapid figure-eight arc — blade intercepting LEFT bullet first (sparks LEFT), continuing the arc to intercept RIGHT bullet (sparks RIGHT). Two separate deflection sparks, two separate directions, one continuous blade movement. Both bullets deflected."
    lighting: "Double simultaneous muzzle flash — two white-gold bursts. Left deflection spark then right deflection spark in rapid sequence."
    sfx: "Two simultaneous gunshots — overlapping cracks, double cathedral reverb. Two blade-on-bullet impacts rapid — left then right, less than 0.2 seconds apart. Double spark hiss."

  05_06_beat6_horizontal_slash_duck:
    camera: "Handheld steady, medium-close side angle."
    action: "Silver Blade steps in — katana swinging in a committed horizontal arc at Blood Moon's mid-torso level, traveling RIGHT across frame. Blood Moon drops LOW immediately — deep knee bend, body going under the blade. The katana passes through the air above his head — visible above his crouching form. Blood Moon's blue hair catches the air displacement from the close pass. Both pistols still in his hands, lowered during the duck."
    lighting: "Blade motion blur through the air — silver arc above the crouching Blood Moon. Red ambient. Candles in side aisles visible in background."
    sfx: "Blade cutting air — sharp fabric-tear sound close to Blood Moon's head. His controlled exhale as he drops. Knee bend on wet stone."

  06_07_beat7_duck_shot_head_dodge:
    camera: "Handheld drops with Blood Moon, stays low."
    action: "Blood Moon — still in his low duck position — raises RIGHT pistol upward at an angle, firing ONCE toward Silver Blade's head from below. Silver Blade's head snaps LEFT — turning his face away from the shot path, the bullet passing within centimeters of his right ear. His silver-white hair moves from the air displacement of the near miss. He does not step back — stays in place, head turned, eyes tracking Blood Moon."
    lighting: "Muzzle flash upward-angled — white-gold from below. Near-miss air displacement barely visible as heat shimmer past Silver Blade's ear."
    sfx: "Gunshot from below — different acoustic quality, upward-directed reverb. Bullet air displacement past Silver Blade's ear — high whistle. His sharp breath from the near miss."

  07_08_beat8_upward_slash_jump_over:
    camera: "Handheld rises with the action, tilting up."
    action: "Silver Blade brings the katana UP in a rising slash — blade traveling upward at a diagonal, aimed at Blood Moon as he rises from the duck. Blood Moon JUMPS — pushing off both feet, body clearing upward over the rising blade. The blade passes beneath his boots — visible under his suspended form. Blood Moon is briefly airborne, both pistols out at his sides for balance."
    lighting: "Blade motion blur rising — silver diagonal upward. Red stained glass light catches Blood Moon's suspended burgundy coat from below."
    sfx: "Rising blade through air — ascending pitch. Blood Moon's jump — explosive push off wet stone. Brief air suspension — coat fabric."

  08_09_beat9_aerial_shot_deflect_slowmo:
    camera: "Handheld STATIC for this beat — holds position, does not follow."
    action: "MICRO SLOW-MO — Blood Moon fires RIGHT pistol while airborne — aimed downward at Silver Blade. Silver Blade's katana rises to meet it — blade tip catching the bullet mid-air. ECU insert: bullet deforming against blade edge, spark at contact, bullet fragments diverging. Normal speed returns as Blood Moon lands — both feet hitting stone simultaneously."
    lighting: "Muzzle flash in slow-mo — white-gold expanding slowly. Spark at blade-bullet contact — frozen in slow-mo. Red ambient."
    vfx: "Micro slow-mo bullet deformation on blade edge. Spark at contact. Bullet fragments diverging."
    sfx: "Gunshot in slow-mo — lower pitch, stretched. Blade-on-bullet ring — extended, decaying slowly. Blood Moon's landing snaps back to normal speed — double boot impact, wet stone."

  09_10_beat10_diagonal_slash_pistol_parry:
    camera: "Handheld resumes movement — circling LEFT around both characters."
    action: "Silver Blade — immediately after the aerial deflection — brings the katana in a diagonal slash from upper-right to lower-left. Blood Moon raises LEFT pistol — not to fire, but barrel horizontal as a parrying surface, catching the blade on the barrel at mid-length. The parry redirects the blade's path — pushing it LEFT and down. Blood Moon's left arm strains with the redirect force. Right pistol remains ready at his side, not raised."
    lighting: "Blade on barrel — small spark. Red ambient. Camera circling gives dynamic angle on the parry."
    sfx: "Blade on barrel — sharp metallic redirect. Blood Moon's footwork — pivot on wet stone. The blade scraping down the barrel as it's redirected — sustained metal friction."

  10_11_beat11_point_blank_body_twist:
    camera: "Handheld tight — medium-close, both faces visible."
    action: "Blood Moon — left arm still extended from the parry — snaps RIGHT pistol up to 20 centimeter range from Silver Blade's torso, fires ONCE. Silver Blade twists his body 45 degrees RIGHT — pulling his torso out of the bullet path. The shot passes through where his chest was — his coat left side rippling from the air displacement. Silver Blade's face: still zero expression, eyes locked on Blood Moon."
    lighting: "Point-blank muzzle flash — harsh white-gold at close range, briefly flooding both their faces."
    sfx: "Gunshot at 20cm — concussive, wrong-sounding, too close. Air displacement through Silver Blade's coat — fabric snap. His controlled twist — no sound except the coat."

  11_12_beat12_double_strike_block_dodge:
    camera: "Handheld pulls back fractionally — needs room for the double strike."
    action: "Silver Blade presses — two consecutive strikes in rapid succession. STRIKE ONE: horizontal right — Blood Moon raises BOTH pistols crossed, blocking the blade on the crossed barrels. STRIKE TWO immediately: Silver Blade redirects downward without resetting — Blood Moon releases the block and steps LEFT, the blade passing through where his torso was. One block, one dodge, no gap between them."
    lighting: "Strike one spark — crossed barrels. Strike two — blade through air, no contact. Red ambient throughout."
    sfx: "Strike one — blade on crossed barrels, hard doubled ring. Strike two — blade through air, fabric displacement. Blood Moon's stepping footwork — rapid, wet stone. No pause between strikes — continuous sound."

  12_13_beat13_triple_shot_double_deflect_one_dodge:
    camera: "Handheld holds steady — this beat needs clarity."
    action: "Blood Moon fires THREE shots in rapid sequence — LEFT gun, RIGHT gun, LEFT gun. Silver Blade: deflects SHOT ONE with blade (spark RIGHT), deflects SHOT TWO with blade continuing the arc (spark LEFT), DODGES SHOT THREE by dropping his head and right shoulder sharply — bullet passing above his shoulder. Three distinct responses to three shots. No wasted movement."
    lighting: "Three rapid muzzle flashes — left, right, left — strobing. Two deflection sparks. Red ambient."
    sfx: "Three rapid gunshots — staccato, fast, barely separated. Two blade-on-bullet rings rapid. Third shot air displacement past his shoulder — whistle. Breathing elevated now — both of them."

  13_14_beat14_final_thrust_cross_block:
    camera: "Handheld slows — barely moving. Both characters filling frame."
    action: "Silver Blade steps in close — katana driving forward in a direct committed thrust toward Blood Moon's chest. Blood Moon raises BOTH pistols simultaneously — crossing them in an X directly in front of his chest, both barrels catching the blade tip. The thrust stops. Both arms locked. Blade held between crossed barrels, tip 5 centimeters from Blood Moon's sternum. Both characters completely still for the first time."
    lighting: "Spark at blade-tip on crossed barrels — small, precise. Red stained glass ambient on both faces. Breath mist between them."
    sfx: "Blade-tip on crossed barrels — sharp precise ring. Both feet planting — final footstep, wet stone. Then silence except breathing."

  14_15_beat15_slowmo_standoff:
    camera: "Handheld goes completely still. MICRO SLOW-MO. Then ECU two-shot hold."
    action: "MICRO SLOW-MO — the crossed pistol barrels and katana blade tip in sharp focus. Sparks from the contact point expanding slowly outward. Both sets of hands visible — Silver Blade's on the hilt, Blood Moon's on both grips, knuckles defined. Then: normal speed returns. Camera slowly pushes in to ECU two-shot — Silver Blade LEFT, Blood Moon RIGHT. Blade and crossed pistols between them at bottom of frame. Both faces. Silver Blade: zero expression. Blood Moon: the half-smile returning — one degree, right corner only. Neither moves. Hold."
    lighting: "Micro slow-mo spark expanding — white-gold slow. ECU: red stained glass ambient on both faces. Breath mist between them catching red light. Hoop earring catching distant candlelight."
    vfx: "Micro slow-mo spark expansion at blade-barrel contact. Slow-mo to normal speed transition — smooth."
    sfx: "Spark in slow-mo — extended hiss, decaying. Normal speed return — silence. Both breathing — close, intimate, slowing. Cathedral ambient. No music. Hold."

production_notes:
  audio_design: "Strictly no music. Foley only throughout. Close breathing is the emotional spine of the entire long take — it elevates through beats 1–13, peaks at beat 13, begins slowing at beat 14, intimate and close at the final hold. All SFX material-specific per beat: gunshots with cathedral reverb, blade-on-bullet rings, blade-on-barrel impacts, spark hiss, boot footwork on wet stone, coat fabric displacement, near-miss air whistles. Point-blank shots sound acoustically wrong — too close, too concussive, less reverb."
  lighting: "Cathedral of Sacred Blood — deep red stained glass dominant throughout entire long take. Warm amber candle points in side aisles as secondary. Cold mist at floor level catching red light. Muzzle flashes as practical light events — brief, physical. No sustained lighting effects."
  subtext: "18 exchanges in 15 seconds between two beings who have been alive for three centuries. Neither has found a fight worth finishing since before living memory. The half-smile returning at the end is not arrogance. It is gratitude."
  critical_constraint: "THIS IS A SINGLE CONTINUOUS LONG TAKE — no cuts, no jump cuts, no hard edits. The camera is handheld and moves continuously but never loses both characters from frame simultaneously. Medium-close range maintained throughout — both combatants visible in most beats. DUAL PISTOLS: Blood Moon holds both ornate silver pistols in both hands in every frame without exception. GUN-SWORD LOGIC: every gunshot has Silver Blade response, every sword strike has Blood Moon response — this rhythm is the entire scene and must be unbroken. Environment from <<<image_5>>> — same cathedral, same red light, same columns. NO other characters, NO bodies, NO crowd."
  avoid: "Cuts or jump cuts of any kind, jitter beyond intentional handheld micro-shake, bent or distorted limbs, identity drift, single pistol on Blood Moon, any gunshot without Silver Blade response, any sword strike without Blood Moon response, music, crowd or background figures, characters frozen in reference-image standing poses."
```

## Beat sheet — 15 บีต

| Beat | Time | ใครเริ่ม | การกระทำ | การตอบ |
|---|---|---|---|---|
| 1 | 00–01 | Blood Moon | ยิงปืนซ้าย 1 นัด | ดาบปัดกระสุน |
| 2 | 01–02 | Silver Blade | ฟันทแยง | ไขว้ปืน 2 กระบอกรับ |
| 3 | 02–03 | Blood Moon | ยิงลอดใต้ดาบไปที่ขา | กระโดดข้าม |
| 4 | 03–04 | Silver Blade | ฟันลงจากแรงลงพื้น | ปืนขวาตั้งรับที่สไลด์ |
| 5 | 04–05 | Blood Moon | **ยิงพร้อมกัน 2 กระบอก** | ดาบวาดเลข 8 ปัดทั้งคู่ |
| 6 | 05–06 | Silver Blade | ฟันแนวนอนระดับเอว | ย่อตัวต่ำลอด |
| 7 | 06–07 | Blood Moon | ยิงขึ้นจากท่าย่อ | สะบัดหัวหลบเฉียดหู |
| 8 | 07–08 | Silver Blade | ฟันขึ้นทแยง | กระโดดข้ามใบมีด |
| 9 | 08–09 | Blood Moon | ยิงลงกลางอากาศ | **🐢 SLOW-MO** ดาบรับกระสุน |
| 10 | 09–10 | Silver Blade | ฟันทแยงบนลงล่าง | ลำกล้องซ้ายปัดเบี่ยง |
| 11 | 10–11 | Blood Moon | ยิงจ่อระยะ 20 ซม. | บิดตัว 45° หลบ |
| 12 | 11–12 | Silver Blade | ฟัน 2 ครั้งติด | บล็อก 1 หลบ 1 |
| 13 | 12–13 | Blood Moon | **ยิงรัว 3 นัด** ซ้าย-ขวา-ซ้าย | ปัด 2 หลบ 1 |
| 14 | 13–14 | Silver Blade | แทงตรงเข้าอก | ไขว้ปืนเป็น X รับปลายดาบ |
| 15 | 14–15 | — | นิ่ง | **🐢 SLOW-MO** → ECU สองคน จบที่ยิ้มมุมปาก |

## Run log

| วันที่ | Tool | ผล | ปัญหาที่เจอ |
|---|---|---|---|
|  |  |  |  |

## Notes


---
[[Action]] · [[Home]]

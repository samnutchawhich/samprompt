---
title: NPC — Costume Sheet Prompts
category: Music
tags:
  - prompt/image
  - category/music
  - project/npc-mv
  - technique/character-lock
  - technique/costume-sheet
tool: Seedance 2.5 / Dreamina
related: "[[NPC — MV Design]]"
status: draft
created: 2026-08-11
---

# NPC — Costume Sheet Prompts

พร็อมต์เจนภาพ **ชีทตัวละครนางเอก (NPC)** 5 ลุค — ใช้เป็น reference ก่อนไปเจนวิดีโอ

## ⚠️ ลำดับการทำ — ทำผิดลำดับจะได้คนละคน

รูป reference ที่มีเป็น **headshot** ไม่มีลำตัว โมเดลจะเดาร่างขึ้นมาเองทุกครั้ง สัดส่วนจะไม่ตรงกัน

**ต้องทำตามลำดับนี้:**

1. เจน **ลุค 1** ด้วย `<<<image_1>>>` (face lock) อย่างเดียว → รันหลายรอบจนได้ร่างที่ชอบ
2. **บันทึกภาพนั้นเป็น `<<<image_2>>>`** = body lock
3. เจนลุค 2–5 ด้วย **image_1 + image_2 คู่กัน** → จะได้คนเดิมทั้งชีท
4. ค่อยเอาทั้ง 5 ภาพมาเรียงเป็นชีท

> ❌ **อย่าเจนทั้ง 5 ลุคในภาพเดียว** หน้าจะเพี้ยนทุกช่อง เพราะโมเดลต้องแบ่งความละเอียดให้ 5 ตัว

---

## 🔒 MASTER BLOCK — วางไว้ต้นทุก prompt (เหมือนกันทุกลุค)

```
Character reference sheet panel. Full-body front view, neutral A-pose, arms
relaxed at the sides, feet shoulder-width apart, looking straight into the
camera, neutral expression, mouth closed.

FACE LOCK: face exactly matching <<<image_1>>> — East Asian woman, late
twenties, long straight black hair falling to the shoulders with soft layers
drifting forward over the cheeks, bare natural skin with visible pores and real
texture, no makeup, dark brown eyes, calm blank expression, natural soft lips,
softly rounded jaw, slight natural asymmetry. Do NOT beautify. Do NOT smooth or
retouch the skin. Do NOT add makeup. Do NOT slim or sharpen the face. Do NOT
enlarge the eyes.

BODY LOCK: body exactly matching <<<image_2>>> — slim, average height, natural
shoulders, ordinary proportions, not model-tall, not idealised.

FRAMING: full body, head to feet, centred, headroom above and floor visible
below. Nothing cropped.

LIGHTING: flat even frontal softbox, no dramatic shadow, no rim light, no
coloured light.

BACKGROUND: plain seamless mid-grey, completely empty.

RENDER: photographic, sharp, natural colour, real fabric behaviour, no
stylisation, no illustration, no 3D look.

DO NOT: crop the feet, tilt the camera, add props that are not listed, add any
background object or text, change the face, add a smile, add jewellery.
```

> ตอนเจนลุค 1 ครั้งแรก **ลบบรรทัด BODY LOCK ออก** เพราะยังไม่มี image_2

---

## 👗 ลุค 1 · DEFAULT — สกินเริ่มต้น

ต่อท้าย MASTER BLOCK ด้วยบล็อกนี้

```
WARDROBE: oversized crew-neck knit sweater in oatmeal cream, completely plain,
no pattern, no logo, slightly slouched at the shoulders, sleeves ending at the
wrist. Light grey straight-leg trousers, simple, no detailing. Off-white canvas
sneakers, lightly scuffed.

PROP: one small blank white name tag pinned at the left chest — completely
EMPTY. No letters, no numbers, no logo, no writing of any kind.

PALETTE: cream, oatmeal, light grey, off-white ONLY. No saturated colour
anywhere in frame.

INTENT: she must read as an unstyled default — plain, forgettable, no
personality expressed through clothing. Nothing about the outfit should be
interesting.
```

**ลุคนี้ใช้เยอะสุดในเพลง** (Intro, Verse 1, Chorus 1, Outro) — ต้องเจนให้ดีที่สุด

---

## 👗 ลุค 2 · GLITCH — ระบบเริ่มรั่ว

```
WARDROBE: identical to LOOK 1, completely unchanged — same oatmeal cream knit
sweater, same light grey trousers, same off-white sneakers, same blank name tag.

GLITCH EFFECT: RGB channel separation — red and cyan ghost outlines offset a few
pixels away from her silhouette. The outline of her left arm and the sweater hem
break apart into hard square pixel blocks. Three or four strands of hair frozen
mid-air, hanging against gravity. One horizontal scanline tear slicing across
the chest, shifting that band of the image sideways.

INTENT: the clothing MUST be exactly the same as LOOK 1. The unease comes
entirely from the same person being rendered wrong — not from a new outfit.
```

> **ห้ามเปลี่ยนชุด** ถ้าชุดเปลี่ยน มุกนี้พังทันที

---

## 👗 ลุค 3 · SHOPKEEPER — บทที่ถูกเขียนให้

```
WARDROBE: LOOK 1 clothing worn underneath, plus a brown canvas apron over it,
tied at the waist, slightly worn at the edges. Grey cloth armbands on both
forearms.

PROP: the same blank name tag, now pinned on the apron chest — still completely
EMPTY, no letters. Above her head floats a small warm orange-pink neon sign
reading OPEN, softly glowing.

PALETTE: cream, brown, grey, with the single warm orange-pink glow of the neon
as the only colour accent.

INTENT: a retail uniform with no branding on it anywhere. She looks employed by
something that never bothered to name her.
```

---

## 👗 ลุค 4 · OVERWRITTEN — ถูกเขียนทับ

```
WARDROBE: short pastel-pink dress with three tiers of ruffles, oversized
matching bow at the collar, white lace ankle socks, chunky white platform shoes.

MAKEUP: heavy doll makeup — two round circles of pink blush high on the cheeks,
glossy enlarged eyes with false lashes, tiny painted lips, pale powdered base.

PALETTE: hyper-saturated pastel pink, white and gold. Everything one step too
bright.

CRITICAL: despite the heavy makeup, her eyes stay completely EMPTY and her
expression stays blank and unreadable. She is not performing cuteness — she is
wearing it. The overall effect must feel uncomfortable, not charming: a cute
costume worn by something that does not understand what cute means.
```

> **นี่เป็นลุคเดียวที่แต่งหน้า** ลุคอื่นห้ามแต่งเด็ดขาด
>
> จุดที่ทำให้ลุคนี้ทำงาน: **หน้าแต่งจัดแต่ตายังว่างเปล่า** ถ้าโมเดลใส่แววตาหรือรอยยิ้มมาให้ = ผิด รันใหม่

---

## 👗 ลุค 5 · AWAKE — มีชื่อแล้ว

```
WARDROBE: the same knit sweater as LOOK 1 but richer and warmer in colour, with
visible individual knit stitches, real fibre fuzz and light pilling on the
sleeves. Same trousers, now with natural creases behind the knees. Same
sneakers, now visibly worn.

SKIN: bare natural face as always, but now with a faint sheen of sweat at the
nose and temples, a light natural flush across the cheeks and nose bridge, and
one or two small real blemishes. Fully human texture.

PROP: the name tag now HAS text written on it — but the letters are rendered
out of focus and unreadable. The viewer can clearly tell a name exists without
being able to read it.

LIGHTING: OVERRIDE the master lighting. Directional soft light from camera left.
A soft real shadow falls along her right cheek and under the jaw, and a cast
shadow falls on the floor beside her feet.

INTENT: this is the only look where she is physically present in a real space.
She must feel like she has weight and occupies air.
```

> **ลุคนี้ใช้ครั้งเดียวในเพลง (Bridge เท่านั้น)** และเป็น**ลุคเดียวที่มีเงา** — จุดสังเกตที่คนดูจะจับได้ทีหลัง

---

## 🗂 พอได้ครบ 5 ลุค — เรียงเป็นชีท

ถ้าอยากได้เป็นภาพชีทเดียว ให้ทำใน Photoshop/Canva ง่ายกว่าเจน:

```
┌──────┬──────┬──────┬──────┬──────┐
│  01  │  02  │  03  │  04  │  05  │
│DEFAULT│GLITCH│SHOP  │OVER- │AWAKE │
│      │      │KEEPER│WRITTEN│      │
└──────┴──────┴──────┴──────┴──────┘
        NPC — CHARACTER SHEET
```

พื้นเทาเดียวกันทั้งแถบ ใส่ชื่อลุคใต้แต่ละช่อง

---

## ✅ Checklist ตรวจก่อนเอาไปใช้

- [ ] หน้าตรงกับ reference ทั้ง 5 ลุค (ดูจมูกกับรูปทรงตากับคางเป็นหลัก)
- [ ] ลุค 1, 2, 3, 5 **ไม่มีการแต่งหน้า** — มีแต่ลุค 4
- [ ] ลุค 2 ชุดเหมือนลุค 1 **เป๊ะ** ไม่ใช่คล้าย
- [ ] ป้ายชื่อ **เปล่า** ในลุค 1–4 · **มีตัวอักษรเบลอ** ในลุค 5
- [ ] ลุค 4 ตายังว่างเปล่าทั้งที่หน้าแต่งจัด
- [ ] ลุค 5 มีเงาบนพื้น · ลุคอื่นไม่มี
- [ ] เห็นเต็มตัวถึงปลายเท้าทุกลุค ไม่มีตัดขา
- [ ] สัดส่วนร่างเหมือนกันทั้ง 5 ลุค

---

## Run log

| วันที่ | ลุค | Tool | ผล | ปัญหา |
|---|---|---|---|---|
|  |  |  |  |  |

## Notes


---
[[NPC — MV Design]] · [[NPC]] · [[Music]] · [[Home]]

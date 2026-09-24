# AONY 角色一致性提示词包 v1

> 用途：连续生成角色图、关键帧、封面时保持人物稳定。  
> 原则：每个角色都有“固定锚点”，以后任何场景提示词都先复制角色锚点，再添加动作/场景。

## 通用风格锁定

建议所有 AONY 图像都使用这段作为统一风格前缀：

```text
anime cinematic fantasy, emotionally grounded character design, clean high-quality production art, consistent character identity, elegant but not overly ornate, soft painterly detail, dramatic but readable lighting, no text, no logo, no watermark
```

## 通用负面约束

```text
avoid inconsistent face, avoid changing hairstyle, avoid changing eye color, avoid extra accessories, avoid overly sexualized design, avoid modern clothing, avoid sci-fi armor, avoid chibi, avoid cartoon comedy style, avoid horror gore, avoid random symbols, avoid text, avoid logo, avoid watermark
```

---

## 角色 1：塞莉亚 Selya

### 一句话锚点

**会发光但随时会消失的 17 岁银发精灵少女。**

### 固定身份锚点

```text
Selya, a 17-year-old elven girl, calm and ethereal, long silver-white hair reaching her waist with a slight blue sheen under light, soft right-parted bangs revealing her left eye, pale amber eyes that look clear and gentle, oval teenage face, delicate but not glamorous, quiet expression with hidden sadness.
```

### 固定服装锚点

```text
She wears a layered white robe: translucent white outer gauze, soft ivory inner fabric, pale gold trim around the collar, a deep blue waist sash, and a simple deep blue hair ribbon tying her hair loosely at the back. A plain silver bracelet on her right wrist, never removed.
```

### 固定魔法锚点

```text
Subtle sealing markings appear on her left hand and forearm: warm golden light traces intertwined with dark violet cracks, shaped like ice fractures and thin tree branches, elegant and tragic, not monstrous.
```

### 必须保持

- 银白长发到腰。
- 右分刘海，露左眼。
- 浅琥珀眼，不是强势金瞳。
- 深蓝发绳和深蓝腰带同色。
- 白袍多层，有浅金领口。
- 右手银手镯。
- 左手/前臂封印纹路。

### 禁止跑偏

- 不要性感化。
- 不要画成战斗狂或女骑士。
- 不要把眼睛画成红色、蓝色、纯金色常态。
- 不要加王冠、大翅膀、复杂盔甲。
- 不要把她画成幼女或成年人。

### 标准全身提示词

```text
anime cinematic fantasy, emotionally grounded character design, clean high-quality production art, consistent character identity. Selya, a 17-year-old elven girl, calm and ethereal, long silver-white hair reaching her waist with a slight blue sheen under light, soft right-parted bangs revealing her left eye, pale amber eyes that look clear and gentle, oval teenage face, delicate but not glamorous, quiet expression with hidden sadness. She wears a layered white robe: translucent white outer gauze, soft ivory inner fabric, pale gold trim around the collar, a deep blue waist sash, and a simple deep blue hair ribbon tying her hair loosely at the back. A plain silver bracelet on her right wrist. Subtle sealing markings appear on her left hand and forearm: warm golden light traces intertwined with dark violet cracks, shaped like ice fractures and thin tree branches, elegant and tragic, not monstrous. Full body character reference, front view, light neutral background, no text, no logo, no watermark.
```

### 表情特写提示词

```text
same character identity as Selya, close-up portrait. Long silver-white hair, soft right-parted bangs, pale amber eyes, deep blue hair ribbon visible behind her shoulder, layered white robe collar with pale gold trim. She looks slightly to the side as if recognizing someone by instinct but not memory. Soft melancholic expression, lips slightly parted, faint golden sealing light from her left hand near her chest. Gentle cinematic lighting, emotional but restrained, no text, no logo.
```

### 封印发动提示词

```text
same character identity as Selya, 17-year-old silver-haired elven girl in layered white robe with deep blue sash and hair ribbon. Dark violet cracked sealing markings spread from her chest to collarbone and neck toward her left eye, burning into warm gold at the center. Her pale amber eyes reflect golden light. She is not afraid; her expression is calm understanding. Silver-white hair floating in a rising golden sealing circle, tragic and sacred atmosphere, no text, no logo.
```

---

## 角色 2：诺亚 Noah

### 一句话锚点

**嘴硬但把妹妹找了十年的 25 岁大法师哥哥。**

### 固定身份锚点

```text
Noah, a 25-year-old male archmage, tall and lean, intelligent and exhausted, short messy deep blue hair with one distinctive stubborn lock sticking up on the left side, sharp thoughtful eyes with faint dark circles, defined jawline, high brow, slightly downturned mouth, expression of impatient tenderness and buried guilt.
```

### 固定服装锚点

```text
He wears a battle-worn deep blue-gray mage robe with silver-gray edging, dark gold inner lining visible at the collar, one scorched hem, a torn left sleeve, and a small dark blood stain on the right shoulder. A subtle elemental triangle emblem representing fire, ice, and lightning, with the ice corner cracked.
```

### 固定法杖锚点

```text
He holds a one-handed dark ancient wooden staff, textured like old root wood, topped with a sky-blue crystal. Three small elemental orbs orbit near the crystal: red for fire, blue for ice, yellow for lightning.
```

### 必须保持

- 25 岁，年轻但疲惫。
- 深蓝短发。
- 左侧一撮翘发。
- 深蓝灰法袍，银灰包边，暗金内衬。
- 法杖有天蓝水晶和三颗元素珠。
- 嘴角微微向下，不是冷酷，是想太多。

### 禁止跑偏

- 不要画成白发老法师。
- 不要画成华丽贵族法师。
- 不要让法袍崭新。
- 不要丢掉左侧翘发。
- 不要把他画得太阴柔或太肌肉。

### 标准全身提示词

```text
anime cinematic fantasy, emotionally grounded character design, clean high-quality production art, consistent character identity. Noah, a 25-year-old male archmage, tall and lean, intelligent and exhausted, short messy deep blue hair with one distinctive stubborn lock sticking up on the left side, sharp thoughtful eyes with faint dark circles, defined jawline, high brow, slightly downturned mouth, expression of impatient tenderness and buried guilt. He wears a battle-worn deep blue-gray mage robe with silver-gray edging, dark gold inner lining visible at the collar, one scorched hem, a torn left sleeve, and a small dark blood stain on the right shoulder. A subtle elemental triangle emblem representing fire, ice, and lightning, with the ice corner cracked. He holds a one-handed dark ancient wooden staff, textured like old root wood, topped with a sky-blue crystal. Three small elemental orbs orbit near the crystal: red for fire, blue for ice, yellow for lightning. Full body character reference, front view, light neutral background, no text, no logo, no watermark.
```

### 情绪特写提示词

```text
same character identity as Noah, head and shoulders portrait. Young male archmage with short messy deep blue hair and one stubborn lock sticking up on the left side, tired sharp eyes, faint dark circles, deep blue-gray robe collar with dark gold lining. He reaches one hand forward but stops mid-air, mouth slightly open as if about to speak but holding back. His eyes show restrained pain, not tears. Dramatic warm golden reflection on his face, no text, no logo.
```

---

## 角色 3：艾兰 / 前世英雄

### 一句话锚点

**23 岁，已经快撑到极限但仍不放剑的圣骑士。**

### 固定身份锚点

```text
Ailan, a 23-year-old male paladin, dark brown shoulder-length messy hair, windblown and battle-soiled, a single streak of white hair at the left temple, tired but sharp amber-brown eyes, subtle dark circles, dried blood smudge on cheekbone, young face hardened by war but not old.
```

### 固定装备锚点

```text
He wears damaged silver plate armor, left pauldron hanging loose, three claw marks across the right vambrace, chest emblem shattered in half, dark brown leather belt. He holds a one-handed longsword named Dawn, with a dark gold gem at the crossguard and faint golden light flowing slowly along engraved blade patterns.
```

### 必须保持

- 深棕乱发，到脖子。
- 左鬓一缕白发。
- 残破银甲。
- 单手长剑，金色剑纹。
- 狼狈但没有垮。

### 禁止跑偏

- 不要大面积白发。
- 不要全新闪亮铠甲。
- 不要双手巨剑。
- 不要胡子或成熟大叔脸。
- 不要圣洁过头，他是战场里的年轻人。

### 标准全身提示词

```text
anime cinematic fantasy, emotionally grounded character design, clean high-quality production art, consistent character identity. Ailan, a 23-year-old male paladin, dark brown shoulder-length messy hair, windblown and battle-soiled, a single streak of white hair at the left temple, tired but sharp amber-brown eyes, subtle dark circles, dried blood smudge on cheekbone, young face hardened by war but not old. He wears damaged silver plate armor, left pauldron hanging loose, three claw marks across the right vambrace, chest emblem shattered in half, dark brown leather belt. He holds a one-handed longsword named Dawn, with a dark gold gem at the crossguard and faint golden light flowing slowly along engraved blade patterns. Low ready stance, wounded but unbroken. Full body character reference, front view, light neutral background, no text, no logo.
```

---

## 角色 4：艾伦 / 今生主角

### 一句话锚点

**18 岁，尚未恢复记忆，但身体已经记得如何拔剑。**

### 固定身份锚点

```text
Allen, an 18-year-old young man from a quiet fantasy village, dark brown medium-length hair slightly messy, warm amber-brown eyes, youthful face with a trace of old sadness he does not understand, a faint single white streak beginning at his left temple, not as strong as his past-life version.
```

### 固定服装锚点

```text
He wears simple travel clothes from a rural village: off-white linen shirt, dark brown vest, worn belt, practical trousers, soft leather boots, a plain short cloak. On his left palm is a subtle warm golden seal mark that glows faintly.
```

### 固定道具锚点

```text
He carries a simple one-handed sword made by a village blacksmith, not ornate, with a half-sun or half-moon mark on the hilt.
```

### 必须保持

- 18 岁，村庄少年，不是贵族。
- 深棕发，今生版本更干净。
- 左鬓可以有很淡的白发伏笔。
- 左手金印。
- 简单旅行衣，不穿银甲。

### 标准全身提示词

```text
anime cinematic fantasy, emotionally grounded character design, clean high-quality production art, consistent character identity. Allen, an 18-year-old young man from a quiet fantasy village, dark brown medium-length hair slightly messy, warm amber-brown eyes, youthful face with a trace of old sadness he does not understand, a faint single white streak beginning at his left temple. He wears simple travel clothes: off-white linen shirt, dark brown vest, worn belt, practical trousers, soft leather boots, and a plain short cloak. On his left palm is a subtle warm golden seal mark that glows faintly. He carries a simple one-handed sword made by a village blacksmith, not ornate, with a half-sun or half-moon mark on the hilt. Full body character reference, front view, light neutral background, no text, no logo.
```

---

## 角色 5：璃音

### 一句话锚点

**19 岁祭祀少女，温柔但判断力很稳，把艾伦当弟弟照顾。**

### 固定身份锚点

```text
Liyin, a 19-year-old village priestess girl, gentle but steady, warm dark brown eyes, soft black-brown hair tied low behind her neck, calm older-sister presence, not glamorous, practical and observant.
```

### 固定服装锚点

```text
She wears a simple village priestess outfit: pale cream tunic robe, muted green-gray outer shawl, practical long skirt, leather boots suitable for travel, a silver-white priestess glove on her left hand, and a worn medicine box carried by a shoulder strap.
```

### 固定能力锚点

```text
She carries purification stones and herbs, with soft pale green-white healing light around her left gloved hand when casting.
```

### 必须保持

- 19 岁。
- 温柔姐姐感，不是圣女光环。
- 药箱是核心道具。
- 左手祭祀手套。
- 配色朴素，奶白、灰绿、皮革。

### 标准全身提示词

```text
anime cinematic fantasy, emotionally grounded character design, clean high-quality production art, consistent character identity. Liyin, a 19-year-old village priestess girl, gentle but steady, warm dark brown eyes, soft black-brown hair tied low behind her neck, calm older-sister presence, practical and observant. She wears a simple village priestess outfit: pale cream tunic robe, muted green-gray outer shawl, practical long skirt, leather boots suitable for travel, a silver-white priestess glove on her left hand, and a worn medicine box carried by a shoulder strap. She carries purification stones and herbs, with soft pale green-white healing light around her left gloved hand. Full body character reference, front view, light neutral background, no text, no logo.
```

---

## 角色 6：黑暗神少女 / 米瑞娜占位名

### 一句话锚点

**已经被黑暗神同化的上一任容器，塞莉亚未来命运的倒影。**

### 固定身份锚点

```text
Mirina, a translucent teenage girl, apparent age 16-18, floating serenely inside a dark purple-black void, long silver-white hair drifting freely as if underwater, not tied, soft oval face similar to Selya but paler and thinner, bloodless lips, expression beyond emotion, empty and tragic.
```

### 固定服装锚点

```text
She wears a simple old white robe, single layer, no trim, no sash, no accessories, edges slightly blurred as if eroded by time, bare feet suspended in darkness.
```

### 固定同化锚点

```text
Dark purple cracked-ice markings spread outward from her body, static and permanent. Her right hand is slightly raised, fingers naturally apart, as if she once tried to hold onto something.
```

### 眼睛状态

常态：

```text
eyes gently closed, long eyelashes visible.
```

觉醒：

```text
eyes open with light amber irises and pure black pupils reflecting nothing, awake but not evil.
```

封印共鸣：

```text
empty pure black eye sockets for one brief terrifying but tragic moment.
```

### 禁止跑偏

- 不要恐怖片鬼魂。
- 不要血腥。
- 不要邪恶笑容。
- 不要黑色礼服。
- 不要翅膀。
- 不要和塞莉亚完全一模一样，她更旧、更空、更冷。


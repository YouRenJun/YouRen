# Banner 插画提示词

使用内置 imagegen 生成浅色底图，再以浅色底图为编辑目标制作深色版本。文字采用独立矢量排版，不让模型生成身份文字。

## 浅色底图

```text
Use case: illustration-story.
Asset type: final-quality illustration layer for a GitHub Profile banner, very wide 3:1, target 2400 x 800 pixels. Create ONE image, no collage.

Brand: YouRen, an independent full-stack developer who builds useful AI applications, developer tools, archives, and interactive stories. Concept: a quiet workshop at dusk. It should feel specific, thoughtful and human, with a clean editorial composition, attractive mature 2D anime art and beautiful restrained light.

COMPOSITION: The LEFT 43 percent must remain a calm warm ivory wall, especially x=6%-42%, y=25%-68%, with no text and no objects. This area is reserved for a large wordmark to be typeset afterward. This is negative space in the same room, not a separate white panel or a split-screen. Gentle surface tone is fine. Compose the scene entirely across the RIGHT 55 percent. Slight architectural elevation / shallow perspective. A tall, simple architectural window with a distinctly chamfered upper-right corner, thin dark charcoal frame, warm pale afternoon sky and softly silhouetted olive foliage outside. A slim wooden desktop at roughly 73 percent of image height. One unbranded laptop sits around x=64%. Its screen faces diagonally left toward the viewer, with a tidy muted editor-like pane and only a few tiny abstract lines, no readable words or logos. Keep perspective and the laptop hinge credible.

CHARACTER: One original adult anime woman around x=80%, occupying about 18 percent of the width. In a natural seated three-quarter side view, facing left toward the laptop. Soft grey-olive long hair, low half-tied style, a tiny terracotta ribbon, warm amber eyes, ivory blouse and charcoal cardigan. Calm, absorbed, gentle expression; appealing polished anime facial anatomy. Natural hands working on the keyboard. She is integrated in the room and her silhouette is clearly legible. No hat. Her head and hair stay within the upper and right safe margins. Crop only the chair/lower legs at the bottom if needed, never the head.

A FEW SMALL OBJECTS: A paper envelope with the edge of a photograph peeking out, a small modular mechanical object, a thin booklet with two discreet page tabs. These gently suggest archives, tools and stories. Keep them few and subordinate. No coffee-shop clutter or ornamental gadgets.

LIGHTING: Rich but restrained golden late-afternoon window light from the right, a fine warm rim on hair and desk, neutral sage-grey shadows. The light is local: do not tint the entire image orange. Preserve contrast and crisp outlines. The left typesetting space stays ivory and evenly quiet.

PALETTE: ivory #F3EBDD, charcoal #282B2A, muted moss #707A60, warm amber #CB9458, tiny terracotta #A56449. Light theme. Sophisticated limited colors with careful secondary detail.

ART DIRECTION: expressive clean 2D anime character and meticulous editorial animation background, elegant linework, flat shapes with selective painterly light, restrained soft grain, beautifully composed negative space. Not photorealistic, not a 3D render, not washed-out or schematic. The character and architectural framing should remain distinct when the banner is shown only 360 pixels wide.

NO TEXT ANYWHERE. No wordmark yet; it will be typeset precisely later. No watermarks, logos, giant code blocks, JSON business card, terminal window, macOS traffic lights, handheld glass card, floating interfaces, neon cyberpunk, circuitry, luminous network nodes, game room RGB, fake buttons, thick borders, excessive blur, shiny plastic skin, multiple characters. Every essential element must be within 6 percent safe margins. Output a single coherent 3:1 panoramic illustration.
```

## 深色编辑

输入图：同目录的 `illustration-light.png`。保持人物、姿态、物件位置和 3:1 比例，仅调整环境色与光线。

```text
Use case: lighting-weather.
Edit target: the attached completed 3:1 panoramic anime workshop illustration. Create its matching DARK THEME version for the same GitHub Profile banner.

CHANGE ONLY the lighting and color treatment. Preserve the SAME original anime woman, exact face and hair design, terracotta ribbon, pose, hands on keyboard, laptop, desk, mechanical cube, booklet, envelope and photo, plants, shelves, architectural window with chamfered upper-right corner, framing and ALL spatial positions. Preserve the exact panoramic 3:1 aspect ratio and full image boundaries. Do not crop or recompose.

Make the interior a quiet charcoal / deep olive-grey room at the blue hour just after sunset. The LEFT 43 percent, reserved for a future ivory YouRen wordmark, must be a smooth subdued deep charcoal wall roughly #202724 to #292E29, with only subtle believable wall texture and very faint soft shadows. No lettering. No bright patches anywhere in the left text area x=6%-42%, y=25%-68%. Maintain continuity with the right scene: do not put a rectangle or vertical split behind it.

Outside the window retain the SAME tree and distant landscape geometry but change the sky to muted dusk blue-grey with a soft narrow amber horizon. Add a restrained warm rim light on the woman's hair and window frame and softly warm desk illumination from the existing small lamp on the right. Keep the original olive-grey hair hue readable, charcoal cardigan distinct from the room, and the calm adult anime face appealing and clear. Preserve the ivory blouse with realistic lower light. Avoid crushed blacks; keep linework and important shapes visible. Laptop screen stays a low-brightness editor; no extra code or UI.

Art style remains exactly the original mature 2D anime editorial illustration with restrained natural detail. This is a companion variant of the same scene, not a different picture. No new items, no stars, no moon, no neon, no purple cyberpunk, no blue color wash, no glowing signs, no text, no watermark, no borders. Output one finished 3:1 dark-theme illustration layer.
```


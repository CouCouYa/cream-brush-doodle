# 奶油粗笔涂鸦提示词

下面的中文版本可直接用于支持图片参考的图像生成工具。上传自己的角色图；如能上传第二张图，使用本文件夹里的 `style-anchor.png` 作为画风参考。没有第二张图时删除关于图二的句子，保留画风描述。将方括号内容替换成实际描述。

```text
请把图一中的角色画成一张奶油粗笔涂鸦插画。图一只负责角色身份；图二只负责笔触、色块、简化程度和纸面背景，不复制图二角色的物种、配色、服装、配件或动作。

角色必须保留：[根据图一填写物种、脸型与口鼻、耳形、发型或毛簇、主色、独特纹样、眼睛颜色、服装及标志性配件]。将这些特征简化成清楚的大形状，保证仍然是同一个角色，不改成内置参考图的角色。

构图：[默认方形半身头像，头部略大，保留角色原有朝向与气质，完整露出重要耳朵和头饰，四周留出适量空白；用户有指定则替换]。

日系可爱绘本涂鸦，粗头画笔手绘。深巧克力褐色的大胆粗轮廓，粗细不均、局部断开，圆钝的起收笔，可见刷毛走向。轮廓与局部深色块自然融合，避免均匀封闭的细描线。

用不透明的大色块松散铺色，沿用角色本身的配色。保留干刷飞白、纸面空洞、擦痕和少量超出轮廓的笔触。让奶油白纸面参与亮部造型，不把每个区域填满。用少数平面色块概括阴影，不做光滑渐变。毛发和头发用几大簇块状形状表现，衣服用大笔触归纳。五官简洁而有神，保留原本的眼色与口鼻特征。

暖奶油白纸面背景，留白清爽。大胆、自然、轻松可爱的手绘小稿，角色设计清楚，绘画边缘松散；笔触有完成度，但不精修抛光。

避免：写实皮肤或逐根毛发、3D、复杂光影、光滑渐变、过细线稿、光滑矢量描边、满屏纹理噪点、复杂背景、额外角色、原图没有的皇冠或饰物、文字和水印。
```

## English style block

可将这一段追加到已经写好的角色描述后。身份来源和风格参考的区分仍需保留。

```text
Cute hand-painted storybook doodle portrait on warm cream-white paper. Bold, very thick, irregular chocolate-brown brush contours with deliberate gaps, blunt rounded stroke endings and visible bristle tracks. Economical spontaneous strokes; contours merge into a few dark shapes. Opaque flat color patches loosely blocked in, uncovered cream-paper holes, dry-brush streaks and occasional paint outside the outlines. Preserve the subject's own palette and distinctive markings. Simplify hair and fur into a few chunky tufts, eyes into expressive simple shapes while retaining their color, and clothing into broad readable shapes. Minimal flat shading, no smooth gradients. Slightly oversized head, clear silhouette, generous breathing room, naturally unfinished playful sketchbook quality. No polished vector outlines, 3D rendering, individual fur strands, added accessories, extra characters, text or watermark.
```

## 参数建议

- 首次使用采用方形头像，便于观察画风；无需绑定某一家模型的专用参数。
- 工具支持多图参考时，将角色图与画风参考图同时输入，并明确各自用途。
- 这是可复用提示与参考图流程，不是训练过的模型或 LoRA；不同工具与不同输入会产生差异。

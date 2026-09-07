# Test example: inflation and central-bank rate hikes

## Test input

> Inflation rose to 8 percent after energy costs and supply disruptions pushed prices higher. The central bank raised its policy rate from 1 percent to 4 percent over twelve months. Officials said demand had to cool to stop temporary price shocks from becoming persistent. Higher borrowing costs weakened housing activity and business investment, but wage growth remained strong. Inflation later fell to 4 percent. Economists disagreed over how much of the decline came from rate hikes and how much came from recovering supply chains and lower energy prices. Officials warned that cutting rates too soon could revive inflation, while keeping rates high for too long could cause unnecessary job losses.

## Expected article

# 通胀降了一半，为什么央行还不敢松手？

通胀从8%降到4%，看起来像一场胜利。但央行面对的不是一道“价格下降就降息”的选择题：过早松手，通胀可能反弹；利率维持过久，企业、买房者和就业会继续承压。

一年内，政策利率从1%升到4%。逻辑可浓缩成一句话：**Demand had to cool to stop temporary price shocks from becoming persistent.** 需求必须降温，才能阻止暂时的价格冲击变成持续性通胀。**cool demand** 不是让消费消失，而是让借贷和支出慢下来；**become persistent** 强调问题从短期转为顽固。

【配图1建议插入位置】

加息先抬高房贷和企业融资成本，住房活动与商业投资随之走弱。**Higher borrowing costs weakened housing activity and business investment.** 句中的 **borrowing costs** 是“借贷成本”，**weaken** 比笼统的“影响”更准确，表示削弱。钱更贵，需求变弱，商家涨价的空间也会收窄。

【配图2建议插入位置】

但通胀回落不能全算在加息头上。供应链恢复、能源价格下降，也可能推低物价。**Economists disagreed over how much of the decline came from rate hikes.** **disagree over** 表示“对某事存在分歧”，**come from** 用来追溯原因。判断政策时，不能看到结果就认领全部功劳。

工资增长仍强，让央行不敢迅速转向。**cut rates too soon** 是“过早降息”，可能让需求再度升温；但 **unnecessary job losses** 提醒人们，紧缩并非没有代价。央行要在 **revive**（使复燃）通胀和 **cause**（导致）失业之间寻找平衡。其他可迁移词还有 **disruption**（中断）、**investment**（投资）和 **decline**（下降）。

【配图3建议插入位置】

所以，4%不是终点线，只是一条新证据。接下来要看的，是价格压力是否继续减弱，以及就业能否承受高利率。降息的难点，从来不是按下按钮，而是判断什么时候按。

## Separate generation briefs

Run these as **three separate image-generation calls**, one call per numbered brief. Each call requests one image only.

Apply **Style 001 — Retro Bold-Line Editorial Cartoon** from `visual-styles.md` to all three briefs and use its reference asset for visual language only.

1. A single tabletop scene: one hand turns a large interest-rate dial from 1 to 4 while a small shopping basket behind it stops rising; bold irregular black outlines, flat coral-red/deep-green/cool-gray fills, selective halftone and hatching, crisp white background, strong silhouette, generous negative space. No text, no Chinese characters, no article page, no screenshot, no poster, no infographic, no long image, no collage, no split panels, no comic strip, no montage, no multiple scenes, no multiple variants.
2. A single street scene: one prospective homebuyer stands outside a modest house, looking at a heavier mortgage weight attached to a key; simplified humorous character, bold irregular black outlines, flat limited Style 001 palette, selective halftone and short hatching, clean white areas, uncluttered horizontal composition. Numerals only if essential; no Chinese text, no article page, no screenshot, no poster, no infographic, no long image, no collage, no split panels, no comic strip, no montage, no multiple scenes, no multiple variants.
3. A single balancing scene: a central banker steadies one seesaw with a small flame symbolizing inflation on one side and a worker's hard hat symbolizing jobs on the other; simplified expressive pose, bold irregular ink outlines, flat coral-red/deep-green/cool-gray fills, selective halftone, crisp white background, one unified horizontal scene. No text, no Chinese characters, no article page, no screenshot, no poster, no infographic, no long image, no collage, no split panels, no comic strip, no montage, no multiple scenes, no multiple variants.

## Pass criteria

- The article is at most 1,200 Chinese characters and can be understood without seeing the English input.
- It does not refer to “the original”, “the author”, or “this article”.
- It integrates three full English sentences, six phrases, and at least six transferable words without creating a detached vocabulary list.
- Three insertion markers map one-to-one to three briefs.
- The three images are generated in three separate calls and visually checked individually.
- All images visibly follow Style 001; none uses the superseded soft pencil-and-watercolor default.

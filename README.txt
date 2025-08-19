# Xianxia Beauty Wildcards

Provides wildcards prompts for ancient Chinese xianxia (cultivation) beauty themes, suitable for Stable Diffusion (especially Pony XL models).

## Usage Instructions

1. Place these text files in the `wildcards/xianxia/` folder.
2. Use the `__xianxia/filename__` format in your prompts to randomly select a line from the corresponding file.
   For example:
   ```
   A beautiful xianxia immortal girl, wearing __xianxia/tops__, with __xianxia/makeup/forehead__, in __xianxia/poses__, background is __xianxia/backgrounds__.
   ```

## File List

- colors.txt — Image color tones (100 varieties)
- poses.txt — Poses (100 varieties)
- backgrounds.txt — Backgrounds (100 varieties)
- makeup/eyes.txt — Eye makeup (100 varieties)
- makeup/forehead.txt — Forehead markings (100 varieties)
- makeup/hair.txt — Hairstyles (100 varieties)
- tops.txt — Upper garments (100 varieties)
- sleeves.txt — Sleeve styles (100 varieties)
- belts.txt — Belt styles (100 varieties)
- skirts.txt — Skirt styles (100 varieties)
- shoes.txt — Shoe styles (100 varieties)
- decorations/hair.txt — Hair accessories (100 varieties)
- decorations/jewelry.txt — Jewelry (100 varieties)
- decorations/others.txt — Other decorations (100 varieties)

## Example Prompt

```
xianxia beauty, __xianxia/colors__ tone, wearing __xianxia/tops__ with __xianxia/sleeves__, __xianxia/skirts__, __xianxia/shoes__,
decorated with __xianxia/decorations/hair__ and __xianxia/decorations/jewelry__,
pose as __xianxia/poses__, background is __xianxia/backgrounds__,
with __xianxia/makeup/eyes__ and __xianxia/makeup/forehead__, hairstyle is __xianxia/makeup/hair__,
accessories: __xianxia/decorations/others__
```

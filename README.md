# Xianxia Beauty Wildcards

Provides wildcards prompts for ancient Chinese xianxia (cultivation) beauty themes, suitable for Stable Diffusion (especially Pony XL models).

## Installation

### Stable Diffusion WebUI

1. Install the [Wildcards](https://github.com/AUTOMATIC1111/stable-diffusion-webui-wildcards) extension.
2. Place the `xianxia` folder under `extensions/stable-diffusion-webui-wildcards/wildcards/` in your stable-diffusion-webui installation directory.

### ComfyUI

1. Install a ComfyUI node package that supports wildcards format, such as [ComfyUI-Impact-Pack](https://github.com/ltdrdata/ComfyUI-Impact-Pack).
2. Place the `xianxia` folder under the `custom_wildcards/` directory of that node package.

## Usage

You can use the following prompt to utilize these wildcards:

```
xianxia beauty, __xianxia/races__ character, __xianxia/colors__ tone, wearing __xianxia/tops__ with __xianxia/sleeves__, __xianxia/skirts__, __xianxia/shoes__,
decorated with __xianxia/decorations/hair__ and __xianxia/decorations/jewelry__,
pose as __xianxia/poses__, background is __xianxia/backgrounds__,
with __xianxia/makeup/eyes__ and __xianxia/makeup/forehead__, hairstyle is __xianxia/makeup/hair__,
accessories: __xianxia/decorations/others__, __xianxia/emotions__ expression,
lighting: __xianxia/lighting__, texture: __xianxia/textures__, season: __xianxia/seasons__
```

### Advanced Usage Examples

```
beautiful __xianxia/races__ xianxia maiden, __xianxia/colors_advanced__ with __xianxia/textures__ surface,
wearing elegant __xianxia/qipao__ with __xianxia/collars__ and __xianxia/skirt_details__,
__xianxia/hairstyles_advanced__ with __xianxia/eyebrows__ and __xianxia/accessories_advanced__,
__xianxia/actions_advanced__ in __xianxia/environments__ setting,
__xianxia/emotions__ expression with __xianxia/lighting__ illumination,
surrounded by __xianxia/seasons__ atmosphere
```

📋 **For more prompt examples, see: [PROMPT_EXAMPLES.md](PROMPT_EXAMPLES.md)**

## File List

### Basic Categories
- colors.txt — Image color tones (100 varieties)
- races.txt — Character races (100 varieties)
- poses.txt — Sexy poses (100 varieties)
- backgrounds.txt — Backgrounds (100 varieties)
- tops.txt — Upper garments (100 varieties)
- sleeves.txt — Sleeve styles (100 varieties)
- belts.txt — Belt styles (100 varieties)
- skirts.txt — Skirt styles (100 varieties)
- shoes.txt — Shoe styles (100 varieties)

### Makeup & Styling
- makeup/eyes.txt — Eye makeup (100 varieties)
- makeup/forehead.txt — Forehead markings (100 varieties)
- makeup/hair.txt — Hairstyles (100 varieties)

### Decorations & Accessories
- decorations/hair.txt — Hair accessories (100 varieties)
- decorations/jewelry.txt — Jewelry (100 varieties)
- decorations/others.txt — Other decorations (100 varieties)

### Extended Categories (New)
- qipao.txt — Qipao styles (100 varieties)
- emotions.txt — Emotional expressions (100 varieties)
- environments.txt — Environmental atmospheres (100 varieties)
- lighting.txt — Lighting effects (100 varieties)
- textures.txt — Material textures (100 varieties)
- seasons.txt — Seasonal elements (100 varieties)
- collars.txt — Collar designs (100 varieties)
- skirt_details.txt — Skirt details (100 varieties)
- hairstyles_advanced.txt — Advanced hairstyles (100 varieties)
- eyebrows.txt — Eyebrow designs (100 varieties)
- accessories_advanced.txt — Advanced accessories (100 varieties)
- actions_advanced.txt — Advanced actions (100 varieties)
- colors_advanced.txt — Advanced colors (100 varieties)

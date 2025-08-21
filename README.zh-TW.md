# 修仙美女圖 Wildcards 提示詞

提供古代修仙美女主題的 wildcards 提示詞，適用於 Stable Diffusion (特別是 Pony XL 模型)。

## 安裝

### Stable Diffusion WebUI

1. 安裝 [Wildcards](https://github.com/AUTOMATIC1111/stable-diffusion-webui-wildcards) 擴充套件。
2. 將 `xianxia` 資料夾放到 stable-diffusion-webui 安裝路徑的 `extensions/stable-diffusion-webui-wildcards/wildcards/` 資料夾下。

### ComfyUI

1. 安裝支援 wildcards 格式的 ComfyUI 節點套件，例如 [ComfyUI-Impact-Pack](https://github.com/ltdrdata/ComfyUI-Impact-Pack) 。
2. 將 `xianxia` 資料夾放到該節點套件的 `custom_wildcards/` 資料夾下。

## 使用方式

你可以使用以下提示詞來使用這組 wildcards ：

```
xianxia beauty, __xianxia/colors__ tone, wearing __xianxia/tops__ with __xianxia/sleeves__, __xianxia/skirts__, __xianxia/shoes__,
decorated with __xianxia/decorations/hair__ and __xianxia/decorations/jewelry__,
pose as __xianxia/poses__, background is __xianxia/backgrounds__,
with __xianxia/makeup/eyes__ and __xianxia/makeup/forehead__, hairstyle is __xianxia/makeup/hair__,
accessories: __xianxia/decorations/others__, __xianxia/emotions__ expression,
lighting: __xianxia/lighting__, texture: __xianxia/textures__, season: __xianxia/seasons__
```

### 進階使用範例

```
beautiful xianxia maiden, __xianxia/colors_advanced__ with __xianxia/textures__ surface,
wearing elegant __xianxia/qipao__ with __xianxia/collars__ and __xianxia/skirt_details__,
__xianxia/hairstyles_advanced__ with __xianxia/eyebrows__ and __xianxia/accessories_advanced__,
__xianxia/actions_advanced__ in __xianxia/environments__ setting,
__xianxia/emotions__ expression with __xianxia/lighting__ illumination,
surrounded by __xianxia/seasons__ atmosphere
```

📋 **更多提示詞範例請參考：[PROMPT_EXAMPLES.zh-TW.md](PROMPT_EXAMPLES.zh-TW.md)**

## 檔案列表

### 基本分類
- colors.txt — 圖片主色調 (100 種)
- poses.txt — 性感姿勢 (100 種)
- backgrounds.txt — 背景 (100 種)
- tops.txt — 上衣 (100 種)
- sleeves.txt — 袖子樣式 (100 種)
- belts.txt — 腰帶 (100 種)
- skirts.txt — 裙子樣式 (100 種)
- shoes.txt — 鞋子樣式 (100 種)

### 化妝造型
- makeup/eyes.txt — 眼妝 (100 種)
- makeup/forehead.txt — 額頭標示 (100 種)
- makeup/hair.txt — 髮型 (100 種)

### 裝飾配件
- decorations/hair.txt — 髮飾 (100 種)
- decorations/jewelry.txt — 首飾 (100 種)
- decorations/others.txt — 其他裝飾 (100 種)

### 擴展分類 (新增)
- qipao.txt — 旗袍樣式 (100 種)
- emotions.txt — 情緒表情 (100 種)
- environments.txt — 環境氛圍 (100 種)
- lighting.txt — 光影效果 (100 種)
- textures.txt — 材質紋理 (100 種)
- seasons.txt — 季節元素 (100 種)
- collars.txt — 領型設計 (100 種)
- skirt_details.txt — 裙裝細節 (100 種)
- hairstyles_advanced.txt — 進階髮型 (100 種)
- eyebrows.txt — 眉型設計 (100 種)
- accessories_advanced.txt — 進階配件 (100 種)
- actions_advanced.txt — 進階動作 (100 種)
- colors_advanced.txt — 進階色彩 (100 種)

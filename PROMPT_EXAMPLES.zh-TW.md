# 修仙美女 Wildcards - 完整提示詞範例

本文件包含使用所有可用 wildcards 文件的完整提示詞範例，以最大化生成圖像的變化和細節。

## 完整覆蓋提示詞
使用此提示詞來使用所有 wildcards 分類：

```
masterpiece, best quality, ultra detailed, 8k, photorealistic,
beautiful __xianxia/races__ xianxia maiden, __xianxia/primary_colors__ dominant color dress with __xianxia/colors_advanced__ and __xianxia/colors__ secondary tones, __xianxia/textures__ surface texture,
wearing elegant __xianxia/qipao__ with __xianxia/collars__ collar and __xianxia/tops__ over __xianxia/sleeves__ sleeves,
__xianxia/skirts__ with __xianxia/skirt_details__ and __xianxia/belts__ belt, __xianxia/shoes__ footwear,
facial features: __xianxia/emotions__ expression, __xianxia/eyebrows__ eyebrows, __xianxia/makeup/eyes__ eye makeup, __xianxia/makeup/forehead__ forehead markings,
hair styling: __xianxia/makeup/hair__ and __xianxia/hairstyles_advanced__ hairstyles,
accessories: __xianxia/decorations/hair__ hair ornaments, __xianxia/decorations/jewelry__ jewelry, __xianxia/decorations/others__ and __xianxia/accessories_advanced__ additional accessories,
pose: __xianxia/poses__ and __xianxia/actions_advanced__ in __xianxia/environments__ environment with __xianxia/backgrounds__ background,
atmosphere: __xianxia/seasons__ seasonal elements, __xianxia/lighting__ lighting effects,
detailed, intricate, elegant, graceful, mystical, ethereal
```

## 分層結構提示詞 (推薦使用)
按分類組織以便更好地控制：

```
masterpiece, best quality, ultra detailed,

/* 人物基礎 */
beautiful __xianxia/races__ xianxia cultivator maiden, __xianxia/emotions__ expression, __xianxia/eyebrows__ eyebrows,

/* 化妝與特徵 */
__xianxia/makeup/eyes__ eye makeup, __xianxia/makeup/forehead__ forehead decoration,

/* 髮型設計 */
__xianxia/makeup/hair__ and __xianxia/hairstyles_advanced__ hair styling with __xianxia/decorations/hair__ hair accessories,

/* 服裝 - 上身 */
wearing elegant __xianxia/qipao__ or __xianxia/tops__ with __xianxia/collars__ collar and __xianxia/sleeves__ sleeves,

/* 服裝 - 下身 */
__xianxia/skirts__ with __xianxia/skirt_details__ details, __xianxia/belts__ belt, __xianxia/shoes__ footwear,

/* 色彩與材質 */
__xianxia/primary_colors__ primary color, __xianxia/colors_advanced__ and __xianxia/colors__ color accents, __xianxia/textures__ fabric texture,

/* 配件 */
adorned with __xianxia/decorations/jewelry__ jewelry, __xianxia/decorations/others__ and __xianxia/accessories_advanced__ accessories,

/* 姿勢與動作 */
__xianxia/poses__ pose, __xianxia/actions_advanced__ action,

/* 環境 */
in __xianxia/environments__ setting with __xianxia/backgrounds__ background,

/* 氛圍 */
__xianxia/seasons__ seasonal mood, __xianxia/lighting__ lighting,

elegant, graceful, mystical, detailed, intricate
```

## 中等複雜度提示詞
使用關鍵分類的平衡版本：

```
masterpiece, best quality, detailed,

__xianxia/emotions__ __xianxia/races__ xianxia beauty, __xianxia/colors_advanced__ with __xianxia/textures__ texture,
wearing __xianxia/qipao__ with __xianxia/collars__ and __xianxia/skirt_details__,
__xianxia/hairstyles_advanced__ with __xianxia/eyebrows__, __xianxia/makeup/eyes__ and __xianxia/makeup/forehead__,
decorated with __xianxia/decorations/hair__ and __xianxia/accessories_advanced__,
__xianxia/actions_advanced__ in __xianxia/environments__ with __xianxia/lighting__,
surrounded by __xianxia/seasons__ atmosphere
```

## 簡化版本
僅使用核心分類：

```
beautiful __xianxia/races__ xianxia maiden, __xianxia/colors__ and __xianxia/textures__,
__xianxia/tops__ with __xianxia/sleeves__, __xianxia/skirts__ and __xianxia/shoes__,
__xianxia/makeup/hair__ with __xianxia/decorations/hair__ and __xianxia/decorations/jewelry__,
__xianxia/poses__ in __xianxia/backgrounds__, __xianxia/lighting__ lighting
```

## 隨機組合提示詞
使用替代語法實現最大隨機化：

```
((masterpiece)), best quality, 8k, detailed,

[__xianxia/emotions__|serene] __xianxia/races__ xianxia [beauty|maiden|cultivator], 
(__xianxia/colors_advanced__|__xianxia/colors__) tones with __xianxia/textures__ surface,

{__xianxia/qipao__|__xianxia/tops__} with __xianxia/collars__ and __xianxia/sleeves__,
[__xianxia/skirts__|flowing robes] with __xianxia/skirt_details__ and __xianxia/belts__,
__xianxia/shoes__ footwear,

face: __xianxia/eyebrows__ brows, __xianxia/makeup/eyes__ eyes, __xianxia/makeup/forehead__ markings,
hair: (__xianxia/makeup/hair__|__xianxia/hairstyles_advanced__) with __xianxia/decorations/hair__,

accessories: __xianxia/decorations/jewelry__ + __xianxia/decorations/others__ + __xianxia/accessories_advanced__,

(__xianxia/poses__|__xianxia/actions_advanced__) in (__xianxia/environments__|__xianxia/backgrounds__),
__xianxia/seasons__ atmosphere, __xianxia/lighting__ illumination,

[elegant|graceful|mystical|ethereal], highly detailed
```

## 專項焦點提示詞

### 肖像專用
```
masterpiece, best quality, portrait,
__xianxia/emotions__ __xianxia/races__ xianxia beauty, __xianxia/colors_advanced__ tones,
__xianxia/eyebrows__ eyebrows, __xianxia/makeup/eyes__ eyes, __xianxia/makeup/forehead__ markings,
__xianxia/hairstyles_advanced__ with __xianxia/decorations/hair__ ornaments,
wearing __xianxia/qipao__ with __xianxia/collars__ collar,
__xianxia/decorations/jewelry__ jewelry, __xianxia/lighting__ lighting
```

### 全身專用
```
masterpiece, best quality, full body,
beautiful __xianxia/races__ xianxia maiden, __xianxia/emotions__ expression,
__xianxia/qipao__ with __xianxia/skirt_details__ and __xianxia/belts__ belt,
__xianxia/shoes__ footwear, __xianxia/colors_advanced__ colors,
__xianxia/poses__ pose, __xianxia/actions_advanced__ action,
in __xianxia/environments__ setting, __xianxia/seasons__ atmosphere
```

### 環境專用
```
masterpiece, best quality, scenic,
__xianxia/races__ xianxia maiden in __xianxia/environments__ with __xianxia/backgrounds__ background,
__xianxia/seasons__ seasonal elements, __xianxia/lighting__ dramatic lighting,
__xianxia/textures__ textures, __xianxia/colors_advanced__ color palette,
atmospheric, detailed landscape
```

## 文件覆蓋摘要
使用的 wildcards 文件總數：27 個

### 基本分類 (9 個文件)
- colors.txt, races.txt, poses.txt, backgrounds.txt, tops.txt, sleeves.txt, belts.txt, skirts.txt, shoes.txt

### 化妝造型 (3 個文件)  
- makeup/eyes.txt, makeup/forehead.txt, makeup/hair.txt

### 裝飾配件 (3 個文件)
- decorations/hair.txt, decorations/jewelry.txt, decorations/others.txt

### 擴展分類 (13 個文件)
- qipao.txt, emotions.txt, environments.txt, lighting.txt, textures.txt, seasons.txt, collars.txt, skirt_details.txt, hairstyles_advanced.txt, eyebrows.txt, accessories_advanced.txt, actions_advanced.txt, colors_advanced.txt

## 使用技巧
1. 使用「完整覆蓋提示詞」獲得最大變化
2. 使用「分層結構提示詞」獲得更好的組織和控制
3. 根據需要調整複雜度
4. 可以混合搭配不同提示詞風格的部分
5. 根據需要添加特定的品質標籤和負面提示詞

## 語法說明

### Wildcards 語法
- `__folder/file__` - 從指定文件中隨機選擇一個選項
- `[A|B|C]` - 從 A、B、C 中隨機選擇一個
- `{A|B}` - 類似於 `[A|B]` 但優先級不同
- `(A|B)` - 括號表示分組

### 品質標籤建議
- `masterpiece` - 傑作品質
- `best quality` - 最佳品質
- `ultra detailed` - 超高細節
- `8k` - 8K 解析度
- `photorealistic` - 照片寫實
- `detailed` - 詳細
- `intricate` - 複雜精緻
- `elegant` - 優雅
- `graceful` - 優美
- `mystical` - 神秘
- `ethereal` - 空靈

### 常用負面提示詞
```
lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry
```

## 進階使用技巧

### 權重調整
使用括號和數字調整提示詞權重：
- `(keyword)` - 增強 1.1 倍
- `((keyword))` - 增強 1.21 倍
- `(keyword:1.2)` - 精確增強 1.2 倍
- `[keyword]` - 減弱至 0.9 倍

### 組合範例
```
(beautiful xianxia maiden:1.2), __xianxia/emotions__ expression, 
((masterpiece)), [lowres:0.8], 
(__xianxia/colors_advanced__:1.1) with (__xianxia/textures__:0.9) texture
```

這樣可以精確控制每個元素在生成圖像中的重要性。
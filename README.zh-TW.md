# 修仙美女圖 Wildcards 提示詞

提供古代修仙美女主題的 wildcards 提示詞，適用於 Stable Diffusion (特別是 Pony XL 模型)。

## 安裝

### Stable Diffusion WebUI

1. 安裝 [Wildcards](https://github.com/AUTOMATIC1111/stable-diffusion-webui-wildcards) 擴充套件。
2. 將 `xianxia` 資料夾放到 stable-diffusion-webui 安裝路徑的 `extensions/stable-diffusion-webui-wildcards/wildcards/` 資料夾下。

### ComfyUI

1. 安裝支援 wildcards 格式的 ComfyUI 節點套件。
2. 將 `xianxia` 資料夾放到該節點套件的 `wildcards/` 資料夾下。

## 使用方式

你可以使用以下提示詞來使用這組 wildcards ：

```
xianxia beauty, __xianxia/colors__ tone, wearing __xianxia/tops__ with __xianxia/sleeves__, __xianxia/skirts__, __xianxia/shoes__,
decorated with __xianxia/decorations/hair__ and __xianxia/decorations/jewelry__,
pose as __xianxia/poses__, background is __xianxia/backgrounds__,
with __xianxia/makeup/eyes__ and __xianxia/makeup/forehead__, hairstyle is __xianxia/makeup/hair__,
accessories: __xianxia/decorations/others__
```

## 檔案列表

- colors.txt — 圖片主色調 (100 種)
- poses.txt — 性感姿勢 (100 種)
- backgrounds.txt — 背景 (100 種)
- makeup/eyes.txt — 眼妝 (100 種)
- makeup/forehead.txt — 額頭標示 (100 種)
- makeup/hair.txt — 髮型 (100 種)
- tops.txt — 上衣 (100 種)
- sleeves.txt — 袖子樣式 (100 種)
- belts.txt — 腰帶 (100 種)
- skirts.txt — 裙子樣式 (100 種)
- shoes.txt — 鞋子樣式 (100 種)
- decorations/hair.txt — 髮飾 (100 種)
- decorations/jewelry.txt — 首飾 (100 種)
- decorations/others.txt — 其他裝飾 (100 種)

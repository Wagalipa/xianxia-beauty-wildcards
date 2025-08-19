# 修仙美女圖 Wildcards 提示詞

提供古代修仙美女主題的 wildcards 提示詞，適用於 Stable Diffusion (特別是 Pony XL 模型)。

## 使用方式

1. 將這些文字檔放到 `wildcards/xianxia/` 資料夾下。
2. 在 prompt 中使用 `__xianxia/filename__` 的方式來隨機選取該檔案中的一行。
   例如：
   ```
   A beautiful xianxia immortal girl, wearing __xianxia/tops__, with __xianxia/makeup/forehead__, in __xianxia/poses__, background is __xianxia/backgrounds__.
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

## 範例 Prompt

```
xianxia beauty, __xianxia/colors__ tone, wearing __xianxia/tops__ with __xianxia/sleeves__, __xianxia/skirts__, __xianxia/shoes__,
decorated with __xianxia/decorations/hair__ and __xianxia/decorations/jewelry__,
pose as __xianxia/poses__, background is __xianxia/backgrounds__,
with __xianxia/makeup/eyes__ and __xianxia/makeup/forehead__, hairstyle is __xianxia/makeup/hair__,
accessories: __xianxia/decorations/others__
```

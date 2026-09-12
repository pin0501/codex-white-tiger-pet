# 白虎 · White Tiger Codex Pet

帶一點插畫筆觸、一點毛絨感的白虎 Codex 寵物。圓潤前掌、奶油白毛色與柔灰虎紋，陪你一起工作。

![白虎寵物預覽](./white-tiger.png)

**[下載最新版素材包](https://github.com/pin0501/codex-white-tiger-pet/releases/latest/download/white-tiger-codex-pet.zip)** · [使用授權](./LICENSE)

## 特色

- 9 種動作：待機、往右跑、往左跑、揮手、跳躍、失落、等待、工作、查看。
- 16 個視線方向，支援滑鼠視線追蹤。
- 透明 PNG，帶柔和插畫與細緻毛絨質感。
- 隨附可離線開啟的動畫預覽頁，可切換動作、視線追蹤與明暗背景。

## 安裝

適用於提供自訂寵物功能的 Codex 桌面版。各平台是否提供此功能，請以你安裝的 Codex 版本為準。

1. [下載 ZIP](https://github.com/pin0501/codex-white-tiger-pet/releases/latest/download/white-tiger-codex-pet.zip) 並解壓縮。
2. 將解壓縮後的 **`white-tiger-illustrated` 整個資料夾**複製到 Codex 的 `pets` 資料夾：

   | 系統 | 預設路徑 |
   | --- | --- |
   | Windows | `%USERPROFILE%\.codex\pets\` |
   | macOS / Linux | `~/.codex/pets/` |

   若已自行設定 `CODEX_HOME`，請使用該目錄下的 `pets` 子資料夾。若 `pets` 尚不存在，可自行建立。

3. 確認檔案排列如下，避免多包一層資料夾：

   ```text
   pets/
   └── white-tiger-illustrated/
       ├── pet.json
       ├── spritesheet.png
       └── README.md
   ```

4. 開啟 Codex 寵物設定，在自訂寵物清單重新整理並選擇 **「白虎」**。若尚未顯示，請重新啟動 Codex 再查看。

## 預覽與修改

在解壓縮後的資料夾中，以瀏覽器開啟 `white-tiger-preview.html`。請保留它與 `white-tiger-illustrated` 資料夾的相對位置。

素材規格：`spriteVersionNumber: 2`；透明 PNG **1536 × 2288 px**；**8 欄 × 11 列**；每格 **192 × 208 px**。修改圖片時請保留尺寸與格子排列。

## 使用授權

可免費下載、使用及修改，作為個人的 Codex 寵物；分享原版或修改版時，請保留本專案名稱、來源連結與授權文字。詳細條件見 [LICENSE](./LICENSE)。

插畫素材使用 OpenAI ImageGen 製作，以白老虎玩偶為靈感。本專案為非官方社群作品，與 OpenAI 或任何玩偶品牌無關。

---

## English

A gentle white tiger companion for Codex, with soft illustrated lines and a little plush texture.

### Download and install

1. [Download the latest ZIP](https://github.com/pin0501/codex-white-tiger-pet/releases/latest/download/white-tiger-codex-pet.zip) and extract it.
2. Copy the entire `white-tiger-illustrated` folder into `%USERPROFILE%\.codex\pets\` on Windows, or `~/.codex/pets/` on macOS / Linux. If you set `CODEX_HOME`, use its `pets` subfolder instead. Create the `pets` folder if needed.
3. In a Codex desktop version that supports custom pets, refresh the custom pet list and select **白虎**. Restart Codex if it does not appear. Feature availability depends on your platform and installed Codex version.

Includes 9 animation states, 16 gaze directions, a transparent sprite sheet, and an offline preview. Open `white-tiger-preview.html` in a browser while keeping it beside the `white-tiger-illustrated` folder.

Sprite format: version 2; 1536 × 2288 px; 8 columns × 11 rows; 192 × 208 px per cell. Preserve the sheet dimensions and layout when editing.

Free to download, use, and modify as a personal Codex pet. Keep the project name, source link, and permission notice when sharing. See [LICENSE](./LICENSE) for the full terms.

Artwork created with OpenAI ImageGen, inspired by a white tiger plush. This is an unofficial community project, unaffiliated with OpenAI or any plush brand.

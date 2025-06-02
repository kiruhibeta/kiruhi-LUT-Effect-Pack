# 🎥 OBS Integration Guide – Kiruhi LUT + Effects Pack

This guide will help you integrate the **Kiruhi LUT + Effects Pack** into **OBS Studio** for use in livestreams, virtual production, or recorded video sessions.

---

## ✅ Requirements

- OBS Studio (v27 or later recommended)
- The Kiruhi LUT + Effects Pack (downloaded and extracted)
- Basic familiarity with OBS scene setup

---

## 🧱 File Types in the Pack

| Type      | Extension | Usage in OBS                    |
|-----------|-----------|----------------------------------|
| LUTs      | `.cube`   | Color correction filter         |
| Effects   | `.mov`    | Media Source overlays (loopable) |
| Textures  | `.png`    | Image overlays (static or animated) |

---

## 🎨 How to Use LUTs in OBS

1. **Select a Video Source** (e.g. your webcam or capture card).
2. Right-click the source > `Filters`.
3. Click the `+` at the bottom left > choose **Apply LUT**.
4. Name the filter (e.g. `Kiruhi_Lofi`).
5. In the LUT path section, browse to and select a `.cube` file from the pack.
6. Adjust the LUT strength using the **Amount** slider.

> 📝 *Tip: LUTs work best when your webcam or input video is exposed and white-balanced correctly.*

---

## 🌌 How to Use Video Effects (Glitch, VHS, RGB Split)

1. Click `+` in the **Sources** panel > choose **Media Source**.
2. Browse to a `.mov` file from the `effects/` folder in the pack.
3. Enable **Loop** and **Restart playback when source becomes active**.
4. Resize and position it as needed.
5. Use **Blending Mode** (via right-click > `Blend Mode`) to experiment with overlays:
   - `Additive`
   - `Screen`
   - `Multiply`

---

## 🧪 Optional: Composite Effects with Filters

You can combine LUTs and effects for a stylized look:

- Apply a **LUT** filter to your main video.
- Add a **Media Source** with glitch textures above your camera feed.
- Adjust opacity or blend modes for creative control.

---

## 📁 Recommended Folder Structure

To keep your OBS project clean:

OBS/
├── LUTs/
│ └── Kiruhi/
│ ├── Kiruhi_Lofi.cube
│ └── Kiruhi_Analog.cube
├── Effects/
│ └── Kiruhi/
│ ├── VHS_Texture_01.mov
│ └── Glitch_Pulse.mov


Then link OBS to these folders when applying filters or adding media sources.

---

## 🚀 Creative Tips

- Combine **glitch effects** with **RGB split** for a retro-cyber aesthetic.
- Use **LUTs** to unify your stream’s color tone.
- Trigger **video overlays** via hotkeys or plugins like **Advanced Scene Switcher**.

---

## 📌 Support

If you encounter issues or need guidance, feel free to reach out via [Gumroad page](https://gumroad.com/kiruhi) or message on social platforms. Enjoy creating!

---


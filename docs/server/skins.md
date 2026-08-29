# Hoobs Skinifier & Custom 3D Skins

Hoobs Live features a built-in 3D skin customizer tool that lets players customize, preview, and apply custom skins with authentic 360-degree accessories.

🌐 **Access the tool**: [https://skin.hoobs.live](https://skin.hoobs.live)

---

## 🎨 Skinifier Features

- **Java & Bedrock Support**: Load any Java Edition username or Bedrock Gamertag, or upload custom PNG skin files directly.
- **3D Interactive Preview**: Powered by Three.js / Skinview3D with live walking, running, and idle animation presets.
- **Alex (3px Slim) & Steve (4px Classic)**: Automatic model detection and formatting.
- **Legacy 64x32 Conversion**: Automatically upgrades old 64x32 skins to modern 64x64 dual-layer skins without distortion.

---

## 🎩 Custom 360 Accessories

The Skinifier includes custom-modeled overlay accessories:

- **Hoobs Hoodie**: Black/charcoal hoodie featuring the official 8x8 Hoobs bacon logo on the chest, ribbed cuffs, and a folded hood on the back.
- **Santa Hat**: Holiday hat with a white fur brim and draped pom-pom.
- **Golden Crown**: Beveled royal crown sitting cleanly on the hairline.
- **Pumpkin Mask**: Halloween carved pumpkin headpiece.
- **Chest Logo**: Standalone authentic Hoobs bacon emblem.

---

## 🚀 1-Click Apply to Minecraft

Once you are happy with your custom skin:
1. Click **Apply to Minecraft** in the exporter.
2. Your customized skin will automatically download, and your browser will redirect directly to the official [Minecraft.net Skin Settings](https://www.minecraft.net/msaprofile/mygames/editskin).
3. Upload the skin file to immediately wear your new design on all Java servers!

---

## 📺 In-Stream Skin Rendering & Prewarming

The livestream runs a server-side 3D skin rendering engine (lexbot-skin.service) powered by ModernGL and EGL GPU acceleration:
- Skins are rendered as smooth, 60fps looping animated WebP files at /anim/standing/<player>.
- Bedrock and Java skins are prewarmed in the background when players connect to the server.
- If you change your skin and want the stream overlay to update immediately, type in chat:
  `
  !reload skin <player>
  `

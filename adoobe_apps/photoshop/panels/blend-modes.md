# Blend Modes

How does the top layer mix with the layer below?

and adjustment layer creates stlyes like contrast or brightness or color etc its doesnt have any content ..

In blend we have content on top layer and we decide with blend how i displays on below layer

we can also create an empty layer and create a blend mode to it .. to use blend modes

Think of it like this:

- You put one image on top of another.
- Blend mode controls how their pixels interact.
- It changes brightness, darkness, contrast, or color depending on the mode.

---

## The 6 Blend Mode Groups (Simple Explanation)

### 1️⃣ Normal Group

No special mixing

- Normal → Top layer covers bottom layer.
- Dissolve → Adds random noise look.

👉 Simple meaning: No blending math happening.

---

### 2️⃣ Darken Group

Removes light areas

These modes keep darker pixels and hide lighter ones.

- Darken → Keeps whichever pixel is darker.
- Multiply → Makes everything darker (white disappears).
- Color Burn → Very dark and high contrast.
- Linear Burn → Strong darkening.

👉 Use when: Adding shadows, dark textures, smoke.

---

### 3️⃣ Lighten Group

Removes dark areas

These keep lighter pixels and hide darker ones.

- Lighten → Keeps lighter pixel.
- Screen → Makes everything brighter (black disappears).
- Color Dodge → Very bright glow.
- Linear Dodge (Add) → Strong light boost.

👉 Use when: Adding fire, light effects, glow.

---

### 4️⃣ Contrast Group

Boosts contrast

Dark parts get darker, light parts get lighter.

- Overlay → Balanced contrast boost (most used).
- Soft Light → Soft contrast.
- Hard Light → Strong contrast.
- Vivid Light / Linear Light / Pin Light → Very strong, stylized.

👉 Use when: Making image pop, texture blending.

---

### 5️⃣ Inversion Group

Creates special effects

- Difference → Creates negative-style effect.
- Exclusion → Softer negative.
- Subtract / Divide → Math-based effects.

👉 Mostly for creative effects or technical use.

---

### 6️⃣ Component Group

Works with color only

These separate color from brightness.

- Hue → Uses color tone only.
- Saturation → Uses color intensity only.
- Color → Changes color but keeps brightness.
- Luminosity → Changes brightness but keeps color.

👉 Used in professional color grading.

---

## Very Simple Summary

| Group     | What It Does              |
| --------- | ------------------------- |
| Normal    | No mixing                 |
| Darken    | Removes light             |
| Lighten   | Removes dark              |
| Contrast  | Increases contrast        |
| Inversion | Special effects           |
| Component | Controls color separately |

---

## Blend Mode vs Adjustment Layer (Simple & Clear)

### 🔹 Blend Mode

Controls how one layer mixes with another layer.

**Example:**

- Put texture on top.
- Change to Overlay.
- Now both layers mix visually.

It changes interaction between layers.

### 🔹 Adjustment Layer

Used to edit the image's color, brightness, contrast, etc.

**Examples:**

- Brightness/Contrast
- Curves
- Hue/Saturation
- Color Balance

It changes image properties, not mixing behavior.

========================================================================================

## 🔥 Most Important Blend Modes (Industry Use)

If you master these, you're 80% done:

- Multiply
- Screen
- Overlay
- Soft Light
- Color
- Luminosity

========================================================================================

## 💡 Practical Example Workflow

### Portrait Color Grade

1. Add solid color layer
2. Change to Color mode
3. Reduce opacity
4. Add mask

### Adding Shadows

1. Paint black on new layer
2. Set to Multiply
3. Blur
4. Lower opacity

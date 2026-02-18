# Blend Modes

Blend Modes control how one layer interacts with the layer(s) beneath it


if you want to create a blend mode but doesnt want to duplicate or create any new year 

just create a adjustment layer by default it has no values or stling then create a blend mode 
---

## 1. Normal Group

### 🔹 Normal

- No blending.
- Top layer completely covers bottom (based on opacity).

### 🔹 Dissolve

- Random pixel replacement based on opacity.
- Creates grain/noise effect.

**Use Case:** Rarely used except for stylized grain effects.

---

## 2️⃣ Darken Group (Removes Lighter Pixels)

### 🔹 Darken

- Compares pixels → keeps darker value.

### 🔹 Multiply (Most Important)

- **Formula:** Base × Blend
- Always darkens.
- Pure white disappears.
- Used for shadows.

**Professional Use:**

- Adding shadows
- Color grading
- Compositing smoke, textures

### 🔹 Color Burn

- Increases contrast + darkens.
- Creates dramatic shadows.

### 🔹 Linear Burn

- Darker than Multiply.
- Reduces brightness linearly.

---

## 3️⃣ Lighten Group (Removes Dark Pixels)

### 🔹 Lighten

- Keeps lighter pixel.

### 🔹 Screen (Opposite of Multiply)

- **Formula:** 1 - (1 - A)(1 - B)
- Brightens image.
- Pure black disappears.
- Used for light effects.

**Professional Use:**

- Adding light leaks
- Glow effects
- Fire overlays

### 🔹 Color Dodge

- Boosts highlights aggressively.
- Creates glowing effect.

### 🔹 Linear Dodge (Add)

- Adds brightness values.
- Very strong light effect.

---

## 4️⃣ Contrast Group (Mix of Multiply + Screen)

These increase contrast by:

- Darkening darks
- Brightening lights

### 🔹 Overlay (Most Used)

- Multiply on dark areas
- Screen on light areas
- Midtones preserved

**Use:**

- Contrast boost
- Texture blending
- Color grading

### 🔹 Soft Light

- Gentle contrast.
- Good for skin retouching.

### 🔹 Hard Light

- Stronger than Overlay.

### 🔹 Vivid Light / Linear Light / Pin Light

- High contrast, stylized looks.
- Used in advanced compositing.

---

## 5️⃣ Inversion Group

### 🔹 Difference

- Subtracts darker from lighter.
- Creates negative effect.

### 🔹 Exclusion

- Softer Difference.

### 🔹 Subtract

- Subtracts pixel values.

### 🔹 Divide

- Divides pixel values.

**Used in:**

- Alignment checking
- Special effects
- Color correction tricks

---

## 6️⃣ Component Group (Color-Based Blending)

These separate color from brightness.

### 🔹 Hue

- Uses hue from blend layer.
- Keeps base brightness.

### 🔹 Saturation

- Transfers saturation only.

### 🔹 Color

- Transfers hue + saturation.
- Keeps luminance of base.

**Used in:** Professional color grading.

### 🔹 Luminosity

- Transfers brightness only.
- Used for high-end retouching.

---

## 🔥 Most Important Blend Modes (Industry Use)

If you master these, you're 80% done:

- Multiply
- Screen
- Overlay
- Soft Light
- Color
- Luminosity

---

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
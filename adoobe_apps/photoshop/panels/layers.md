# layers panel

## what is layers in photoshop

A Photoshop file is a stack of transparent sheets.
Each sheet contains different elements (text, image, shape, effects).
You can edit one sheet without touching the others.

layers are like sheets of paper stacked on top of each other. with this you can edit each sheet without affecting the others and each have different elements.

with layer you can do work on each sheet without affecting the others.like new tool or new work on new layer.

Layers follow top-to-bottom hierarchy:

- Top layer = visible above
- Bottom layer = background
- You can reorder by dragging

If something disappears:
👉 It may be hidden under another layer.

---

### Real-World Example

Imagine designing a YouTube thumbnail:

- Background image → Layer 1
- Cutout of person → Layer 2
- Text headline → Layer 3
- Color grading → Adjustment Layer
- Shadow effects → Layer Styles

Each can be modified separately.

---

# ui

you have layers option in right side of ui in panels and you see layers panel 

<img src="layers-panel.png" width="350" height="350">

the layers panel is divided into several sections:



### 1. Top Section – Layer Filtering Bar

This row helps you filter specific layer types.

🔍 “Kind” Dropdown
Lets you filter layers by type.
Icons next to “Kind”
These are quick filters:

- 🖼 Image icon → Pixel layers
- ◐ Half circle → Adjustment layers
- T → Text layers
- ⬛ Shape → Shape layers
- 📄 Smart Object icon
- 🔴 Color tag → Filter by layer color label

If filter is active, only those layers show.

---

### 2. Blending Mode & Opacity Area

Located right below filters.

***Blending Mode (Default: Normal)***

Dropdown (Normal, Multiply, Screen, Overlay, etc.)
Controls how this layer interacts with layers below it mathematically.

***Examples***:

- Multiply → Darkens
- Screen → Lightens
- Overlay → Contrast boost

***Shortcut***:
- Shift + + → Next blending mode
- Shift + - → Previous blending mode

#### Opacity

Controls transparency of the whole layer.

***Shortcut***:

Press number keys (with Move Tool selected)

5 → 50%
8 → 80%
0 → 100%
25 → 25%

---

### 3. Fill

Like opacity but only affects layer pixels, not layer styles (like shadows).
Used heavily in advanced effects.

---

### 4. Lock Options

Below blending mode:

***Icons***:

🔲 Lock Transparent Pixels
🖌 Lock Image Pixels
🔀 Lock Position
🔒 Lock All

***Professionals use***:
- Lock Transparent Pixels when painting on cutouts.

***Shortcut***:
- / (slash) toggles Lock Transparent Pixels


---

### 5. The Layer Stack (Main Area)

This is the vertical hierarchy.

Top layer = visible above
Bottom layer = base


#### Elements inside each layer row

***Eye Icon***

Toggle visibility.

***Shortcut***:
- Click
- Alt + Click → Solo view (hide all others)

***Thumbnail***

Small preview of layer content.
If checkerboard → transparent pixels.

***Layer Name***

Double click to rename (always rename in professional workflow).

***Lock icon (right side)***
If locked, you cannot edit.

***Background layer is locked by default.***

***To unlock***:
- Double click “Background”


---

### 6. Bottom Action Bar (Very Important)

These icons are critical.

***From left → right:***

#### 🔗 Link Layers

Links selected layers so they move together.

need to select more than one layer to link them. can use by holding  cmd (mac) or ctrl (windows) and clicking on layers.


#### fx (Layer Styles)

Adds:

Drop Shadow
Stroke
Outer Glow
Gradient Overlay
Bevel & Emboss

***Shortcut***:

Double click empty space of layer
Or right click → Blending Options

#### ⭕ Layer Mask

Adds white mask (reveals everything)
Black hides, white reveals.

***Shortcut***:
- Click mask icon
- Alt + Click → Black mask

#### ◐ Adjustment Layer

***Creates non-destructive adjustment:***

- Brightness/Contrast
- Levels
- Curves
- Hue/Saturation
- Color Balance

Professionals NEVER use Image → Adjustments.
They use adjustment layers.

#### 📁 New Group

Creates folder.

***Shortcut***:

Ctrl + G (Cmd + G Mac)

#### ➕ New Layer

Creates empty pixel layer.

***Shortcut***:

Ctrl + Shift + N

#### 🗑 Delete Layer

Deletes selected layer.

***Shortcut:***

Delete key

--- 

### Key Layer Properties

Inside the Layers Panel, you control:

| Property        | What It Does                          |
| --------------- | ------------------------------------- |
| Visibility (👁) | Show/Hide layer                       |
| Opacity         | Transparency control                  |
| Blending Mode   | How layer interacts with layers below |
| Lock            | Prevent edits                         |
| Layer Mask      | Hide parts non-destructively          |
| Effects (FX)    | Add shadow, glow, stroke, etc         |


## Types of Layers in Photoshop

### 1️⃣ Pixel (Raster) Layer

- Contains actual image pixels.
- Used for photos and painting.

### 2️⃣ Text Layer

- Editable typography.

### 3️⃣ Shape Layer

- Vector-based shapes (scalable without quality loss).

### 4️⃣ Adjustment Layer

- Applies color/lighting corrections without modifying the original image.

### 5️⃣ Smart Object

- A protected container layer that preserves original data.




---

## Most Used Professional Shortcuts

These are the ones that actually matter in real workflows:

### Layer Creation & Management

Ctrl + Shift + N → New layer
Ctrl + J → Duplicate layer
Ctrl + G → Group layers
Ctrl + Shift + G → Ungroup
Ctrl + E → Merge down
Ctrl + Shift + E → Merge visible
Ctrl + Alt + Shift + E → Stamp visible (pro move)

### Visibility & Selection

Alt + Click eye → Solo layer
Ctrl + Click thumbnail → Load selection
Shift + Click layers → Multi-select

### Masks

Add mask → Click mask icon
Alt + Click mask → View mask
Shift + Click mask → Disable mask
Ctrl + I (on mask) → Invert mask

### Moving Layers

V → Move tool
Ctrl + ] → Move layer up
Ctrl + [ → Move layer down
Ctrl + Shift + ] → Bring to front
Ctrl + Shift + [ → Send to back

### Opacity Quick Control

1 → 10%
5 → 50%
0 → 100%

### 7. Professional Layer Discipline (Important)

#### Beginners:

- Leave names like Layer 1, Layer 2
- Directly erase pixels
- Flatten early

#### Professionals:

- Rename everything
- Use masks instead of eraser
- Use adjustment layers
- Group logically

Color-code layers

Keep file editable until final export


Final Mental Model

Layers Panel = Your project architecture.

If you don’t control it:
Your design becomes chaos.

If you structure it:
You work like an industry retoucher or designer.
# HAVEN — Intelligent Room Designer
### Metadome · 3-Day Solutions Engineer Assessment

> **Submission format:** Web prototype for the **Home Decor** track.

This submission focuses on assignment outcomes (interaction, visuals, AI-assisted recommendations) in a browser-based prototype. It is intentionally frontend-first for rapid 3-day delivery and demoability.

---

## Quick Start

1. Open `haven-room-designer.html` in any modern browser.
2. No build step. No npm install. No server required.
3. Type a style prompt and click **Generate AI Suggestions**.
4. Optional: enable **Use live Claude API** and provide a key in the top header.

---

## Evaluation Criteria Mapping

### 1) Game Mechanics
- Furniture placement, drag-to-move, rotate, duplicate, delete
- Snap-to-grid toggle for controlled placement
- Undo/redo history for interaction recovery
- Measure tool and right-click context actions
- One-click room templates + reset to empty room

### 2) Graphics
- Custom rendered environment (walls, floor materials, depth effects, architectural details)
- Procedural furniture visuals (no external model dependencies)
- Real-time wall/floor updates and visual feedback
- Clean panelized layout for controls + stage + AI output

### 3) Generative AI Integration
- Prompt input + style chips + preset buttons (Modern/Minimalist/Luxury)
- Fallback-first behavior (works without API key)
- Optional live Claude mode for dynamic suggestions
- Exactly 5 normalized suggestion cards always rendered
- One-click apply updates wall color, floor, and missing furniture placements

### 4) Documentation
- This README contains setup, features, criteria mapping, and demo flow
- Included video scripts:
  - `video-script-1-project-walkthrough.md`
  - `video-script-2-why-metadome.md`

### 5) Creativity
- Multi-style design recommendation system with curated fallback profiles
- Shareable design links via encoded room state
- Export-to-PNG output for portfolio/demo usage
- First-time helper overlay to improve onboarding

---

## Demo Screenshots / GIFs (8)

### 1. Full Prototype Overview
![Overview](assets/demo/01-overview.png)

### 2. Left Panel Controls
![Left Panel](assets/demo/02-left-panel.png)

### 3. Template + Reset Controls
![Templates and Reset](assets/demo/03-template-reset.png)

### 4. Color and Floor Controls
![Color and Floor](assets/demo/04-color-floor-controls.png)

### 5. Canvas Workspace
![Canvas Workspace](assets/demo/05-canvas-workspace.png)

### 6. Top Toolbar and Actions
![Toolbar and Actions](assets/demo/06-toolbar-and-actions.png)

### 7. AI Suggestion Panel
![AI Panel](assets/demo/07-ai-panel.png)

### 8. First-Time Helper Overlay
![Helper Overlay](assets/demo/08-helper-overlay.png)

---


## Known Constraint

- This submission is a **web prototype** (not a Unity/Unreal compiled build).
- The design choice was intentional for speed, clarity, and complete feature demonstration within the 3-day window.

---

## Author

**Arpan**

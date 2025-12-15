# Design Specifications & Agent Instructions

This document outlines the visual requirements and prompts for the Cyberpunk Portfolio. It is intended for the **Visuals Agent** (or User) to generate assets.

## 🎨 Art Direction
-   **Style**: Cyberpunk, High-Tech, Neon-Noir.
-   **Color Palette**:
    -   **Neon Green** (`#00ff41` / `#00C896`) - Success/Data
    -   **Electric Blue** (`#00f3ff`) - Structure/Systems
    -   **Hot Pink/Vermilion** (`#FF3B30` / `#ff0055`) - Alerts/Highlights
    -   **Void Black** (`#0B0F10`) - Background
-   **Vibe**: "Hacker Terminal meets Bladerunner cityscapes."

## 🤖 Content Generation Agents

### Agent 1: Visuals Agent (Image Generation)
**Role**: Generate visual assets using the prompts below.
**Tools**: Midjourney v6, DALL-E 3, or Stable Diffusion.

#### Task 1: Main Banner
*Rationale*: A striking hero image to greet visitors.
*File Name*: `assets/cyberpunk-banner.png`
*Prompt*:
> **Cinematic cyberpunk hacker workstation, ultra-wide view, multiple holographic screens displaying complex Python and Java code, dark room illuminated by neon jade and vermilion lights, futuristic city skyline visible through a rainy window in the background, 8k resolution, highly detailed, photorealistic, --ar 3:1 --v 6.0**

#### Task 2: Section Divider
*Rationale*: To separate content sections with style.
*File Name*: `assets/neon-divider.png`
*Prompt*:
> **Horizontal neon laser beam, glowing electric blue and hot pink energy core, glitch art effects, dark background, minimalist but intense, 8k resolution, --ar 16:1**

#### Task 3: Profile Badge/Avatar Background (Optional)
*Rationale*: To frame the user's avatar.
*File Name*: `assets/profile-frame.png`
*Prompt*:
> **Circular futuristic HUD interface frame, glowing data rings, cybernetic details, neon green elements, transparent center for profile picture, vector style graphic, high contrast, black background**

---

### Agent 2: Architect Agent (This Session)
**Role**: Structure the data and implement the Markdown.
**Status**: Ready to execute `README.md` refactoring upon approval.

### Agent 3: QA Agent
**Role**: Verify links and visual coherence.
**Instructions**: Check that all generated images are placed in `assets/` and properly referenced in the README. Verify contrast ratios for accessibility.

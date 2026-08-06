# Design System Document

## 1. Overview & Creative North Star: "Velocity Brutalism"
The Creative North Star for this design system is **Velocity Brutalism**. Unlike standard fitness apps that rely on soft gradients and rounded UI, this system embraces raw power, industrial precision, and high-octane energy. It is designed to feel like a high-end, underground performance lab—unapologetic, sharp, and intensely focused.

We break the "template" look by rejecting symmetry. We use massive typography scales to create a sense of scale and "Kinetic Overlap," where elements bleed into one another to suggest motion even in a static environment. This isn't just a business card website; it’s a digital manifesto of strength.

---

### 2. Colors: High-Contrast Tonalism
The palette is built on a foundation of absolute darkness, punctuated by "Heat Levels" of red. 

*   **The "No-Line" Rule:** Under no circumstances are 1px solid borders to be used for sectioning. Boundaries must be defined solely through background color shifts. For instance, a `surface_container_low` (#131313) section sitting on a `surface` (#0e0e0e) background creates a sophisticated "block" look without the clutter of lines.
*   **Surface Hierarchy:** Use the `surface_container` tiers to create depth. 
    *   **Level 0:** `surface_container_lowest` (#000000) for the deepest background.
    *   **Level 1:** `surface_container_low` (#131313) for secondary content blocks.
    *   **Level 2:** `surface_container_high` (#1f1f1f) for interactive cards.
*   **Signature Textures:** To move beyond flat color, apply a subtle linear gradient to main CTAs transitioning from `primary_dim` (#eb0000) to `primary` (#ff8e7d). This simulates the glow of a red neon light or a high-performance LED display.
*   **Glassmorphism:** For floating elements (like a sticky navigation bar), use `surface_container` at 80% opacity with a heavy `backdrop-blur` (20px+). This creates a "frosted obsidian" effect that feels premium and integrated.

---

### 3. Typography: The Impact Scale
We use typography as a structural element, not just for legibility.

*   **Display & Headlines (Space Grotesk):** This is our "Engine." Use `display-lg` (3.5rem) for hero statements. It should feel massive. Use tight letter-spacing (-0.02em) and consider all-caps for "Action Labels" to increase the aggressive, brutalist tone.
*   **Body & Titles (Inter):** This is our "Instruction." Inter provides a neutral, professional contrast to the aggression of Space Grotesk. Use `body-lg` for readability in trainer bios or service descriptions.
*   **Hierarchy as Tension:** Don't center everything. Align large `headline-lg` text to the far left and tuck `body-sm` metadata into the far right. This asymmetry creates visual "tension" that mirrors the physical tension of fitness.

---

### 4. Elevation & Depth: Tonal Layering
In Kinetic Brutalism, we do not use "depth" to be pretty; we use it to establish a hierarchy of power.

*   **The Layering Principle:** Stack `surface_container` tiers to create "lift." A `surface_container_highest` (#262626) card placed on top of a `surface_dim` (#0e0e0e) background creates a natural, sharp-edged elevation.
*   **Ambient Shadows:** If a floating element (like a modal) requires a shadow, it must be massive but nearly invisible. Use a 40px blur with 6% opacity using the `on_primary_fixed` (#000000) color. It should feel like a soft "vignette" around the object rather than a drop shadow.
*   **The Ghost Border Fallback:** If a container needs to be defined against a similar background, use the `outline_variant` (#484848) at 15% opacity. This "Ghost Border" provides a hint of structure without breaking the Brutalist aesthetic. 

---

### 5. Components: Sharp & Impactful
All components must adhere to the **0px Roundedness Scale**. Sharp edges are non-negotiable.

*   **Buttons:**
    *   **Primary:** Solid `primary_dim` (#eb0000) background with `on_primary_fixed` (#000000) text. 0px radius. On hover, transition to `primary` (#ff8e7d) with a slight "tilt" transform (1-2 degrees).
    *   **Tertiary:** Transparent background with `primary` text. No border. Use a heavy underline (2px) that appears on hover.
*   **Cards & Lists:** 
    *   **No Dividers:** Never use a horizontal line to separate list items. Use a background shift (alternating `surface_container_low` and `surface_container_high`) or simply utilize the Spacing Scale (24px - 32px gaps).
    *   **Impact Cards:** Use `surface_container_highest` for service cards. Images should be high-contrast, desaturated (black and white), and potentially use a `primary` color multiply filter.
*   **Input Fields:**
    *   Use a "Block" style. The input is a solid `surface_container_highest` rectangle with a 2px `primary` bottom border only. This keeps the look grounded and aggressive.
*   **Status Chips:** 
    *   Use `surface_variant` (#262626) for the background and `on_surface_variant` (#ababab) for text. Keep them small and rectangular to act as subtle labels for "High Intensity" or "Pro Level."

---

### 6. Do’s and Don’ts

#### Do:
*   **Embrace the Void:** Use plenty of `surface_container_lowest` (#000000) space. It makes the red accents feel more "dangerous" and high-energy.
*   **Intentional Asymmetry:** Offset your columns. Let an image bleed off the edge of the screen while the text stays boxed.
*   **Kinetic Hover States:** When a user hovers over a card, make it react. A slight scale-up (1.02x) or a color shift to `primary_dim` reinforces the "High Energy" vibe.

#### Don’t:
*   **No Rounding:** Never use a border-radius. Every corner in this system is a 90-degree angle. Roundness suggests "comfort," and this system is about "challenge."
*   **No Generic Grids:** Avoid the standard 3-column layout. Try a 2-column layout where one column is 70% width and the other is 30% for a more editorial, bespoke feel.
*   **No Low Contrast:** Avoid using grey text on black. Use `on_surface` (#ffffff) for maximum impact or `on_surface_variant` (#ababab) for secondary info. Nothing should feel "muddy."

---

### 7. Director's Final Note
This design system is a tool for precision. When building screens, ask yourself: *"Does this feel like it was built for an elite athlete or a generic gym-goer?"* If it feels too safe, break the grid. If it feels too cluttered, remove a line and use a tonal shift instead. Focus on the raw energy of the Red against the Black.
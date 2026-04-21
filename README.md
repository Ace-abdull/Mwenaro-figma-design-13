# 🎨 Figma Design 13 – HTML & CSS Implementation

A fast, pixel-accurate implementation of a Figma landing page design using **pure HTML and CSS only**.  
This project focuses on **speed, layout accuracy, and clean structure**, simulating real-world front-end test conditions.

---

## 🚀 Overview

This layout recreates a modern hero section with:

- Centered headline and call-to-action
- Floating decorative elements
- Asymmetrical image positioning
- Structured informational text blocks

The goal was to **match the visual design as closely as possible** while maintaining clean and maintainable code.

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3 (Vanilla)**
- ❌ No frameworks (Tailwind, Bootstrap, etc.)
- ❌ No preprocessors (SASS, LESS)

---

## 🎯 Key Features

### 1. Clean Layout Structure

- Logical grouping of sections:
  - Header (hero)
  - Text content
  - Floating elements
- Containers designed so elements move together naturally

---

### 2. Flexbox for Core Layout

- Used for centering and stacking:
  - Hero content (heading, paragraph, button)
- Ensures clean vertical alignment and spacing

---

### 3. Absolute Positioning for Design Elements

- Used for:
  - Decorative shapes (sparks, explosion, party)
  - Floating images
  - Side text blocks

This allows precise control to match the Figma layout.

---

### 4. Reusable Styling (No Repetition)

- Shared styles grouped for:
  - Paragraph containers
  - Text blocks
  - Typography
- Positioning handled separately from styling

---

### 5. Controlled Text Wrapping

- Used:
  ```css
  max-width
  text-wrap: balance;
---
### 6. Component-Based Thinking (Without Frameworks)

  ```

Each UI part behaves like a component:

- `header-section-wrapper` → Hero
- `text-content-container` → Info blocks
- `float-images-container` → Visual elements

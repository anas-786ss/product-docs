---
marp: true
title: Product Documentation Overview
author: Mohd Anas
paginate: true
theme: custom-theme
footer: "Product Documentation • 2025"
---

<!-- Custom Theme Definition -->
<style>
section {
  font-family: "Segoe UI", sans-serif;
}

h1 {
  color: #0a84ff;
}

.custom-box {
  border: 2px solid #0a84ff;
  padding: 20px;
  border-radius: 10px;
  background: #f0f8ff;
}

footer {
  font-size: 12px;
  color: #666;
}
</style>

<!-- Custom Theme Configuration -->
<!--
theme: custom-theme
class: lead
-->

# 📘 Product Documentation  
### *Technical Writer: Mohd Anas*  
**Email:** 23f3003127@ds.study.iitm.ac.in

---

# 📄 Why Marp for Documentation?

- Markdown-based → version control friendly  
- Export to **PDF**, **PPTX**, **HTML**  
- Automatic styling  
- Developer-friendly workflow  

---

<!-- A slide with background image -->
<!-- Use any URL or repo file path -->
![bg](https://images.unsplash.com/photo-1555066931-4365d14bab8c)

# 🖼️ Visual Slide  
### Background Image Example

This slide uses a full-background image.

---

# 🎨 Custom Styled Component

<div class="custom-box">
  This is a custom-styled callout box using Marp internal CSS.
  <br><br>
  Perfect for highlighting important documentation notes.
</div>

---

# 🔢 Algorithm Complexity Example

### Time Complexity Equation (LaTeX)

We analyze the algorithm using:

\[
T(n) = T(n-1) + O(n)
\]

Which solves to:

\[
T(n) = O(n^2)
\]

Good for documenting system performance, algorithms, or APIs.

---

# 📚 Exporting & Versioning

- Store this file as **`slides.md`** in GitHub  
- Convert using CLI:

```bash
marp slides.md --pdf
marp slides.md --html
marp slides.md --pptx

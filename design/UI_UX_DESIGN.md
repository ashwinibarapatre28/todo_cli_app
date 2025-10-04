## 🎨 UI/UX Designer Role

### Objective (as assigned by PM):

> “Create layout wireframes, color palette, typography, and design mockups for *Taskify*, ensuring a clean, responsive, and modern interface.”

---

## 🗂️ Suggested Folder & File Structure

Here’s how you should organize UI/UX-related files in your repository:

```
/docs/
│
├── PLAN.md
├── PRD_REPORT.md
├── README.md
└── UI_UX_DESIGN.md     ← 🆕 This file (today’s deliverable)
│
/design/
├── taskify_wireframe.png
├── taskify_color_palette.png
└── taskify_typography.png
```

---

## 📁 New File: `UI_UX_DESIGN.md`

Here’s the full content (ready to commit):

```markdown
# 🎨 UI/UX Design Document – Taskify

**Prepared By:** UI/UX Designer  
**Reviewed By:** Project Manager  
**Date:** October 2025  

---

## 1️⃣ Design Objectives

The design goal is to make **Taskify** clean, minimal, and distraction-free, allowing users to focus on managing their daily tasks quickly.  
The layout should adapt seamlessly across desktop and mobile screens.

**Key Focus Areas:**
- Simplicity and readability  
- Accessibility (contrast, color balance)  
- Responsiveness and fluidity  
- Consistency in visual hierarchy  

---

## 2️⃣ Color Palette

| Color | Purpose | Hex Code |
|--------|----------|-----------|
| **Primary Blue** | Buttons, Highlights | `#3B82F6` |
| **Light Gray** | Background | `#F9FAFB` |
| **Dark Gray** | Text | `#1F2937` |
| **White** | Cards / Panels | `#FFFFFF` |
| **Green** | Completed Tasks | `#10B981` |
| **Red** | High Priority | `#EF4444` |
| **Amber** | Medium Priority | `#F59E0B` |
| **Blue-Gray** | Low Priority | `#93C5FD` |

---

## 3️⃣ Typography

| Element | Font | Size | Weight |
|----------|------|------|--------|
| App Title | Poppins | 28px | 600 |
| Section Headings | Inter | 20px | 500 |
| Task Text | Inter | 16px | 400 |
| Buttons / Inputs | Inter | 14px | 500 |

**Font Source:** Google Fonts  
**Fallbacks:** sans-serif

---

## 4️⃣ Layout Wireframe Description

### Desktop Layout

```

┌────────────────────────────────────────────┐
│ TASKIFY                                    │  ← Header / Navbar
├────────────────────────────────────────────┤
│ + Add a new task... [Add Button]           │  ← Input Section
├────────────────────────────────────────────┤
│ [Filter: All | Pending | Completed]        │  ← Filter Tabs
├────────────────────────────────────────────┤
│ [ ] Task 1 - High Priority - Due: 10 Oct   │
│ [x] Task 2 - Completed                     │
│ [ ] Task 3 - Medium Priority - Due: 15 Oct │
│ ...                                        │  ← Task List
└────────────────────────────────────────────┘

```

### Mobile Layout

```

┌────────────────┐
│  TASKIFY ⊕     │
├────────────────┤
│ [Add Task Bar] │
│ [Filter Tabs]  │
│ [Task Cards ↓] │
└────────────────┘

```

---

## 5️⃣ Dark Mode Design

| Element | Light Mode | Dark Mode |
|----------|-------------|------------|
| Background | `#F9FAFB` | `#111827` |
| Text | `#1F2937` | `#F3F4F6` |
| Card | `#FFFFFF` | `#1F2937` |
| Buttons | `#3B82F6` | `#2563EB` |

---

## 6️⃣ Icons & Visuals

| Icon | Purpose | Library |
|-------|----------|----------|
| ✅ Checkmark | Task Complete | Lucide / Feather Icons |
| 🗑️ Trash | Delete Task | Lucide / Feather Icons |
| ✏️ Edit | Edit Task | Lucide / Feather Icons |
| ☀️🌙 | Theme Toggle | Custom SVG |

---

## 7️⃣ Deliverables

| File | Description |
|-------|--------------|
| `taskify_wireframe.png` | Visual wireframe layout |
| `taskify_color_palette.png` | Swatches of chosen colors |
| `taskify_typography.png` | Font and text style preview |
| `UI_UX_DESIGN.md` | Documentation summary (this file) |

---

## 8️⃣ Next Steps (for Frontend Developer)

- Create folder structure for HTML/CSS/JS  
- Implement responsive navbar, task list container, and buttons  
- Use defined colors, fonts, and layout spacing  
- Integrate dark/light theme toggle  
- Maintain consistent margins and paddings from mockups  

---

✅ **Status:** Design Phase Completed  
🔁 **Next Phase:** Frontend Development (`feature/frontend-tasks` branch)
```

---

## 🧾 PM’s Approval Notes (Simulated)

> ✅ *Reviewed by PM:* The design follows the minimal, professional aesthetic.
> Approved to move forward to **Frontend Development Phase**.
> PM requests developer to use provided font, colors, and responsive grid.

---

## 🪜 Next Steps for You (Developer Side)

1. **Create new branch:**

   ```bash
   git checkout -b feature/ui-ux-design
   ```

2. **Add the file and commit:**

   ```bash
   mkdir docs design
   git add docs/UI_UX_DESIGN.md
   git commit -m "docs(ui-ux): add design document and layout description"
   ```

3. **Push branch and create PR to `develop`:**

   ```bash
   git push -u origin feature/ui-ux-design
   ```

4. Go to GitHub → Open a **Pull Request**

   * Base branch: `develop`
   * Compare branch: `feature/ui-ux-design`
   * Title: `feat(ui-ux): add design documentation`
   * Description: “Added UI/UX design guidelines, color palette, and wireframes.”
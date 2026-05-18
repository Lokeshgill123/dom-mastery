# 🧠 DOM Mastery — JavaScript DOM Bible

> A complete, self-contained reference for JavaScript DOM manipulation — built as a single interactive HTML file. No frameworks. No dependencies. Just pure, deep knowledge.

![JavaScript](https://img.shields.io/badge/JavaScript-ES2024-F0DB4F?style=flat-square&logo=javascript&logoColor=black)
![HTML](https://img.shields.io/badge/HTML5-Single_File-E34F26?style=flat-square&logo=html5&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-00d4ff?style=flat-square)
![Status](https://img.shields.io/badge/Status-Complete-00ff88?style=flat-square)

---

## 📌 What's Inside

This is not another "top 10 DOM methods" article. This is a proper reference — the kind you actually keep open while building projects.

| # | Section | What it covers |
|---|---------|----------------|
| 1 | **Selecting Elements** | querySelector, querySelectorAll, getElementById, closest(), matches(), live vs static collections |
| 2 | **DOM Traversal** | parentNode, children, siblings, firstElementChild, walking the tree |
| 3 | **Create & Insert** | createElement, append/prepend, insertAdjacentHTML, DocumentFragment, cloneNode, remove |
| 4 | **Modify Content** | innerHTML vs textContent vs innerText — deep comparison with XSS context |
| 5 | **Attributes & Data** | getAttribute/setAttribute, attr vs property difference, dataset (data-*) patterns |
| 6 | **Classes & Styles** | Full classList API, inline styles, getComputedStyle, CSS variables via JS |
| 7 | **Events** | addEventListener options, bubbling/capturing, event delegation, all event types, CustomEvent |
| 8 | **Forms & Input** | FormData API, Constraint Validation API, focus management, input types |
| 9 | **Dimensions & Scroll** | getBoundingClientRect, offsetWidth/clientWidth, scrollTo, scrollIntoView |
| 10 | **Advanced DOM** | MutationObserver, IntersectionObserver, `<template>`, localStorage, ResizeObserver |

---

## 🎯 Interview Questions (10)

Expandable Q&A format — click each question to reveal a full answer with code examples.

Covers the questions that actually get asked:

- `innerHTML` vs `textContent` vs `innerText` — when to use each
- Event bubbling, capturing, and propagation — with `stopImmediatePropagation`
- Event delegation — why it exists and how to write it correctly
- `e.target` vs `e.currentTarget` — the difference that trips people up
- Live HTMLCollection vs static NodeList — with a live demonstration in code
- HTML attributes vs DOM properties — the `value` and `checked` gotcha
- Why DocumentFragment beats individual insertions — performance explanation
- MutationObserver — when events aren't enough
- `getBoundingClientRect()` — viewport geometry explained
- Building a pub/sub event bus with CustomEvents

---

## 💪 Arrays & Loops — 10 Practice Problems

Real problems that prepare you for both project work and LeetCode.

| # | Problem | Concepts | Difficulty |
|---|---------|----------|------------|
| P1 | Two Sum | Hash Map, O(n) | 🟢 Easy |
| P2 | Group By Category | reduce(), real grouping logic | 🟡 Medium |
| P3 | Flatten Nested Array | Recursion, Array.isArray | 🟡 Medium |
| P4 | Chunk Array | slice(), pagination logic | 🟢 Easy |
| P5 | Find Duplicates | Object as frequency map | 🟢 Easy |
| P6 | Maximum Subarray (Kadane's) | Dynamic programming | 🔴 Hard |
| P7 | Sort by Multiple Keys | Comparator chaining, localeCompare | 🟡 Medium |
| P8 | Deep Merge Objects | Recursion, typeof checks | 🟡 Medium |
| P9 | Debounce from Scratch | Closures, HOF, setTimeout | 🔴 Hard |
| P10 | Pipe / Compose | Functional programming, reduce | 🔴 Hard |

Every problem includes a working solution with inline comments explaining each step.

---

## 🏗️ DOM Mini Projects — 10 Builds

Projects ordered from beginner to advanced. Each comes with a problem statement, key patterns hint, and tagged concepts.

| # | Project | Skills | Level |
|---|---------|--------|-------|
| D1 | **Todo List (CRUD)** | createElement, delegation, localStorage | 🟢 Beginner |
| D2 | **Live Search / Filter** | input event, debounce, classList | 🟡 Medium |
| D3 | **Accordion / FAQ** | closest(), siblings, toggle | 🟢 Beginner |
| D4 | **Drag & Drop Kanban** | DnD API, DataTransfer, data-id | 🔴 Hard |
| D5 | **Infinite Scroll** | IntersectionObserver, async, Fragment | 🟡 Medium |
| D6 | **Custom Modal System** | Focus trap, keydown, overflow | 🟡 Medium |
| D7 | **Multi-Step Form** | Constraint Validation, classList | 🟡 Medium |
| D8 | **Scroll Animations** | IntersectionObserver, CSS transitions | 🟢 Beginner |
| D9 | **Auto-Resize Textarea** | scrollHeight, input event, counter | 🟢 Easy |
| D10 | **Virtual DOM / Diff** | Recursion, tree diffing, render | 🔴 Hard |

---

## 🚀 How to Use

**Clone and open:**
```bash
git clone https://github.com/your-username/dom-mastery.git
cd dom-mastery
open dom_mastery.html   # macOS
# or just double-click the file in your file explorer
```

**No build step. No npm install. No server required.**  
It's a single `.html` file. Open it and use it.

---

## 📂 Project Structure

```
dom-mastery/
├── dom_mastery.html    # The entire reference — cheatsheet + questions + projects
└── README.md           # This file
```

---

## 🧭 Who This Is For

- **Beginners** moving from basic JS tutorials to real DOM work
- **Intermediate devs** who want a fast reference while building
- **Anyone preparing for frontend interviews** — the Q&A section covers what actually gets asked
- **Self-taught developers** who want structured, project-grounded learning

---

## 💡 Design Philosophy

Most DOM resources either:
- Give you a shallow "10 methods you need to know" list, or  
- Drop you into MDN documentation with no context

This tries to sit in the middle — enough depth to actually understand *why* things work the way they do, with enough real-world framing to know *when* to reach for each tool.

The practice problems are written to serve two goals at once: they build DOM and array intuition that transfers directly to LeetCode-style problems, while also being the kind of thing you'll actually build in a real project.

---

## 🤝 Contributing

Found an error, a missing API, or have a better example? PRs are welcome.

1. Fork the repo
2. Make your changes in `dom_mastery.html`
3. Open a PR with a short description of what you improved

---

## 📄 License

MIT — use it, share it, build on it.

---

<p align="center">
  Built while learning full-stack development · JavaScript is the foundation everything else sits on
</p>

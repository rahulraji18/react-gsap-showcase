<div align="center">

# React GSAP Showcase

A collection of GSAP animation examples built with React and Vite.

Explore core GSAP concepts including To, From, FromTo, Timeline, Stagger, ScrollTrigger, and Text Animations.

</div>

---

## About

This project was developed as a frontend portfolio project to demonstrate:

- GSAP fundamentals
- React integration with GSAP
- Component-based animation architecture
- Scroll-based interactions
- Timeline sequencing
- Stagger animations
- Modern frontend development practices

---

## Features

✅ GSAP To Animations

✅ GSAP From Animations

✅ GSAP FromTo Animations

✅ GSAP Timeline

✅ GSAP Stagger Effects

✅ GSAP ScrollTrigger

✅ GSAP Text Animations

✅ Responsive Layout

✅ React Component Architecture

---

## Tech Stack

- React
- Vite
- GSAP
- JavaScript (ES6+)
- CSS3

---

## Official Resources

### GSAP

- https://gsap.com
- https://gsap.com/docs
- https://gsap.com/resources

### React

- https://react.dev

### Vite

- https://vitejs.dev

---

## Project Structure

```text
react-gsap-showcase/
│
├── public/
│   └── preview.png
│
├── src/
│   ├── pages/
│   │   ├── GsapTo.jsx
│   │   ├── GsapFrom.jsx
│   │   ├── GsapFromTo.jsx
│   │   ├── GsapTimeline.jsx
│   │   ├── GsapStagger.jsx
│   │   ├── GsapScrollTrigger.jsx
│   │   └── GsapText.jsx
│   │
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── package.json
├── vite.config.js
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/rahulraji18/react-gsap-showcase.git
```

Navigate to the project directory:

```bash
cd react-gsap-showcase
```

Install dependencies:

```bash
npm install
```

---

## Running the Application

Development Mode:

```bash
npm run dev
```

Open:

```text
http://localhost:5173
```

---

## GSAP Examples Included

### 1. GSAP To

Animate elements from their current state to a new state.

```javascript
gsap.to(".box", {
  x: 300,
  duration: 2,
});
```

---

### 2. GSAP From

Animate elements from a starting state to their current state.

```javascript
gsap.from(".box", {
  opacity: 0,
  y: 100,
  duration: 1,
});
```

---

### 3. GSAP FromTo

Define both start and end states.

```javascript
gsap.fromTo(
  ".box",
  { opacity: 0 },
  { opacity: 1, duration: 1 }
);
```

---

### 4. Timeline

Sequence multiple animations together.

```javascript
const tl = gsap.timeline();

tl.to(".box", { x: 200 })
  .to(".box", { rotation: 360 });
```

---

### 5. Stagger

Animate multiple elements with a delay.

```javascript
gsap.from(".item", {
  opacity: 0,
  stagger: 0.2,
});
```

---

### 6. ScrollTrigger

Trigger animations while scrolling.

```javascript
gsap.to(".box", {
  scrollTrigger: ".box",
  x: 300,
});
```

---

## Learning Outcomes

After completing this project, you will understand:

- GSAP Core API
- useGSAP Hook
- Timelines
- Stagger Animations
- ScrollTrigger
- Text Animations
- React + GSAP Integration
- Animation Performance Best Practices

---

## Future Improvements

- GSAP Flip Plugin
- MotionPath Plugin
- SVG Animations
- Loader Animations
- Advanced ScrollTrigger Examples
- Reusable Animation Hooks
- TypeScript Migration

---

## Live Demo

Add your deployment URL here:

```text
https://your-project.vercel.app
```

---

## Author

### Rahul Rajeevan

GitHub:
https://github.com/rahulraji18

LinkedIn:
https://www.linkedin.com/in/rahul-rajeevan/

Repository:
https://github.com/rahulraji18/react-gsap-showcase

---

## License

MIT License

Copyright (c) 2026 Rahul Rajeevan# react-gsap-showcase

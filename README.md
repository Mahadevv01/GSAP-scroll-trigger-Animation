
# T7 - GSAP ScrollTrigger Animation Theory

## Purpose
This document explains the concept of **GSAP ScrollTrigger**, a powerful plugin from the GreenSock Animation Platform (GSAP) that allows you to trigger animations based on the user's scroll position. This plugin is widely used for creating engaging, scroll-driven animations in web development.

---

## What is ScrollTrigger?

**ScrollTrigger** is a GSAP plugin that allows you to create animations that are tied to the scrolling of the webpage. It enables animations to start when a specific element enters the viewport, or when the page is scrolled to a particular position. This creates dynamic, interactive web experiences.

---

## Key Features of ScrollTrigger

- **Scroll-based Triggers:** ScrollTrigger allows you to start and control animations when elements are scrolled into view.
- **Animation Control:** You can control how elements animate as the user scrolls, including smooth transitions, scaling, opacity changes, etc.
- **Scrubbing:** ScrollTrigger can scrub through animations, meaning the animation will play in sync with the scroll, providing a smooth user experience.
- **Markers (Debugging):** You can add markers to visualize when triggers occur during the scroll, which helps in debugging.
- **Pinning Elements:** You can "pin" elements in place while scrolling, which makes them stay in view during the scroll.
  
---
## Basic Concept

When an element comes into view as the user scrolls, you can trigger an animation. Similarly, you can create animations that happen when the scroll reaches a certain point on the page.

### Common ScrollTrigger Options:

- **`trigger`:** The target element that will activate the animation when it enters or exits the viewport.
- **`start`:** Defines when the animation should start relative to the scroll position (e.g., `"top bottom"` means the animation starts when the top of the trigger element reaches the bottom of the viewport).
- **`end`:** Defines when the animation should end relative to the scroll position (e.g., `"bottom top"` means the animation ends when the bottom of the trigger element reaches the top of the viewport).
- **`scrub`:** If `true`, the animation will be tied directly to the scroll position, creating a smooth, scrubbed animation.
- **`pin`:** You can pin an element in place while the user scrolls.
- **`markers`:** Adds debug markers to the page so you can see where the triggers occur.

---

## Example of ScrollTrigger Animation

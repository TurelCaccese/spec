# \[README.md\] (English Version)

# SPEC Framework ◄ ▲ ◐ ◯ ◑ ▼ ►

### Sight | Perception | Exploration | Control

SPEC is a perception-driven interaction framework designed to evolve beyond the traditional "verb-based" interface of classic point-and-click or text adventures. Instead of selecting actions from a menu, interaction emerges through player attention and spatial awareness.\*

Philosophy: LOOK → FOCUS → UNLOCK → INTERACT\*

---

## 📖 The Concept

_In SPEC, the player doesn't simply "click" on objects. The player observes . Interaction is not instantaneous: it requires time (focusing) and spatial consciousness (exploration). If you don't look carefully, the world remains silent._

- S \- Sight: Directional gaze movement.\*
- P \- Perception: Dynamic sensory feedback based on the framed environment.\*
- E \- Exploration: The requirement to fully scan the environment to unlock advanced states.\*
- C \- Control: Symbolic interaction that appears only after the context is understood.\*

The SPEC Framework is designed for:

- Immersive navigation (Virtual tour, landscapes, details)
- Spatial storytelling (Interactive Novel and Fictions, Branding and Communication)
- Perception interface (A focused experience that can follow a message or an action)

---

## Features

- Perception-based interaction
- Focus-triggered actions
- Symbolic UI system
- Cinematic viewport navigation
- Twine SugarCube integration
- Native HTML/JS support
- WordPress-ready architecture for web browsers

---

## 🛠️ Project Architecture

_The framework is currently available in two implementations:_

### 1\. SPEC for Twine (SugarCube 2\)

_Built for deep interactive storytelling. It uses a Hub & Scene system to manage camera movement and player state within Twine passages._

- Viewport System: Simulates head movement via CSS `translate3d`.\*
- Blink Engine: Asynchronous "eyelid" system to enhance physical immersion.\*
- Symbolic UI: Replaces text links with directional icons and focus nodes.\*

### 2\. SPEC Web Widget (Native HTML/JS)

_A framework-agnostic version designed for integration into standard websites or WordPress instances._

- Lightweight: No external dependencies, just Vanilla JavaScript and CSS.\*
- Navigation Gate: Can be used as an interactive header to unlock page content only after the user has explored the scene.\*
- Responsive: Optimized for cinematic layouts (21:9 / 16:4).\*

---

## 🕹️ Input System

_SPEC abandons text commands in favor of a symbolic language:_

- ◄ ▲ ▼ ► : Gaze navigation (Sight).\*
- ◯ / ⬢ : Interaction node (appears only after Focus).\*
- ◐ ◑ : Peripheral attention indicators.\*

---

## 🚀 Getting Started

### For Twine Users:

1. _Download `SPEC_Prototype.twee` or copy the CSS/JS into your SugarCube story._
2. _Configure your viewport in the `StoryCaption` passage or a dedicated widget._
3. _Use the `checkAllVisited()` logic to handle narrative unlocks._

### For Web/WordPress/Blogspot Integration:

1. _Include the `spec-widget-container` div in your HTML._
2. _Customize the background image (panoramic scene)._
3. _Set up JS triggers to reveal the rest of your site upon scan completion._

---

## Screenshots

Images are available in the /docs folder of this repository

---

## License

SPEC Framework is licensed under
CC BY-NC 4.0.

Free for non-commercial use. Commercial use requires explicit permission from the author.\*

https://creativecommons.org/licenses/by-nc/4.0/

_© 2026 Andrea Turel Caccese._

---

## 🔗 Links

- Live Demo: (Coming soon) \[Insert your GitHub Pages link here\]\*
- Prototype: (Coming soon)\[Insert your Itch.io link here\]\*

---

## Status

> ⚠️ **STATUS: ALPHA (v0.3)**
> Core logical structures, input combinations, and spatial coordinate states are stable. 

### Current Features (Alpha v0.3)
* [x] Three-dimensional image depth mechanics using multi-axis ($X, Y, Z$) translation layers.
* [x] Refactored input engine with multi-input combination support.
* [x] Production-ready Konami Code engine and state logic.
* [x] Interactive multi-node camera system (Left, Up, Focus A, Focus B, Down, Right)
* [x] Smooth CSS-driven camera transitions & idle ambient movement.
* [To do] Adaptive Desktop / Mobile aspect ratio handling.
* [x] CRT channel-switching simulation.
* [x] Sequential scene navigation & spatial memory lock/unlock mechanics.

First public impementation on blogspot as html extension for the blog.

https://www.turelcaccese.com/

**Header Blogspot.html** available in **examples** folder

Current Features:
Interactive camera system
Multiple camera nodes (Left, Up, Focus A, Focus B, Down, Right)
Automatic Desktop / Mobile aspect ratio
Smooth camera transitions
CRT channel switching effects
Idle camera movement
Scene memory
Unlock system
Sequential scene navigation
Per-scene contextual text
Hidden Konami Code prototype
Roadmap
Scene-specific camera coordinates
Audio layer
Modular SPEC engine
External JSON scene loading
Save / Restore state
Branching exploration
Dynamic overlays
Public API
License

Prototype currently under active development.

© Andrea Turel Caccese

⚠️ STATUS: ALPHA

This project is under active development.
Features and APIs may change without notice.

---

## Known Issues

- Mobile support is experimental
- State management is still being refactored
- Focus / Rotation transitions require optimization
- Interface - Widget personalizations still in embryonic state

---

## Versions

Current Version: Pre-Alpha (May 2026)

### Roadmap

- [ ] Dynamic Soundscape implementation based on camera panning
- [ ] Image multi canvas / Passages
- [ ] Effects, rotation and interface
- [ ] 2 layers movements
- [ ] 3-4 layers movements
- [ ] Accelerometer support for gaze control (Mobile-ready)
- [ ] Official WordPress Plugin

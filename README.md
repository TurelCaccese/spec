#  \[README.md\] (English Version) 

#  SPEC Framework ◄ ▲ ◐ ◯ ◑ ▼ ►   

###  Sight | Perception | Exploration | Control 

 SPEC  is a perception-driven interaction framework designed to evolve beyond the traditional "verb-based" interface of classic point-and-click or text adventures. Instead of selecting actions from a menu, interaction emerges through player attention and spatial awareness.*

 Philosophy:  LOOK → FOCUS → UNLOCK → INTERACT*

---

##  📖 The Concept 

*In SPEC, the player doesn't simply "click" on objects. The player  observes . Interaction is not instantaneous: it requires time (focusing) and spatial consciousness (exploration). If you don't look carefully, the world remains silent.*

*  S \- Sight:  Directional gaze movement.*  
*  P \- Perception:  Dynamic sensory feedback based on the framed environment.*  
*  E \- Exploration:  The requirement to fully scan the environment to unlock advanced states.*  
*  C \- Control:  Symbolic interaction that appears only after the context is understood.*


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



##  🛠️ Project Architecture 

*The framework is currently available in two implementations:*

###  1\. SPEC for Twine (SugarCube 2\) 

*Built for deep interactive storytelling. It uses a  Hub & Scene  system to manage camera movement and player state within Twine passages.*

*  Viewport System:  Simulates head movement via CSS `translate3d`.*  
*  Blink Engine:  Asynchronous "eyelid" system to enhance physical immersion.*  
*  Symbolic UI:  Replaces text links with directional icons and focus nodes.*

###  2\. SPEC Web Widget (Native HTML/JS) 

*A framework-agnostic version designed for integration into standard websites or WordPress instances.*

*  Lightweight:  No external dependencies, just Vanilla JavaScript and CSS.*  
*  Navigation Gate:  Can be used as an interactive header to unlock page content only after the user has explored the scene.*  
*  Responsive:  Optimized for cinematic layouts (21:9 / 16:4).*

---

##  🕹️ Input System 

*SPEC abandons text commands in favor of a symbolic language:*

*  ◄ ▲ ▼ ►  : Gaze navigation (Sight).*  
*  ◯ / ⬢  : Interaction node (appears only after Focus).*  
*  ◐ ◑  : Peripheral attention indicators.*

---

##  🚀 Getting Started 

###  For Twine Users: 

1. *Download `SPEC_Prototype.twee` or copy the CSS/JS into your SugarCube story.*  
2. *Configure your viewport in the `StoryCaption` passage or a dedicated widget.*  
3. *Use the `checkAllVisited()` logic to handle narrative unlocks.*

###  For Web/WordPress Integration: 
1. *Include the `spec-widget-container` div in your HTML.*  
2. *Customize the background image (panoramic scene).*  
3. *Set up JS triggers to reveal the rest of your site upon scan completion.*

---

## Screenshots

Images are available in the /img folder of this repository

---

## License

SPEC Framework is licensed under
CC BY-NC 4.0.

 Free for non-commercial use.  Commercial use requires explicit permission from the author.*

*© 2026 Andrea Turel Caccese.*

---

##  🔗 Links 

*  Live Demo:  (Coming soon) \[Insert your GitHub Pages link here\]*  
*  Prototype:  (Coming soon)\[Insert your Itch.io link here\]*

---

## Status

SPEC is currently in active early development.

Features and architecture may change significantly between versions.

---

## Known Issues

- Mobile support is experimental
- State management is still being refactored
- Focus / Rotation transitions require optimization
- Interface - Widget personalizations still in embryonic state

---


## Versions

Current Version: Pre-Alpha (May 2026)

###  Roadmap 

- [ ] Dynamic Soundscape implementation based on camera panning
- [ ] Image multi canvas / Passages
- [ ] Effects, rotation and interface
- [ ] 2 layers movements
- [ ] 3-4 layers movements
- [ ] Accelerometer support for gaze control (Mobile-ready)
- [ ] Official WordPress Plugin


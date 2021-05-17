# NG Motion
| Next generation angular animation

## Motivation

The current solution for Angular is limited and not very ergonomic, thus often unused. Some solutions from other frameworks like [Framer Motion](https://www.framer.com/motion/), [React Spring](https://react-spring.io/), [Pop Motion](https://popmotion.io/), [Vue Gesture](https://gesture.vueuse.org/) and [Vue Motion](https://motion.vueuse.org/) have the ergonomics and simplicity of the AngularJS animations, with robustness of the Angular 2 animations while adding natural feeling to the animations.

The core principals of the animation library should be:
* **Natural** 🌳
* **Ergonomic** 🤸
* **Accessible** ♿
* **Testable** 🧪

### Natural

In the nature, movement is rarely clean and surgically linear. There is often a tension or friction to the movement, or a certain inertia applied both at a start and at the end of the movement. Additionally, objects' energies influence each other. The library needs to provide a way to easily generate natural movement by following the Newton's laws of motion and other laws of physics.

### Ergonomic

The API should be simple, clear and extendable.

### Accessible

All animations functionality should provide accessibility points, to easily switch them off or enhance for greater inclusion.

Resources: 
* [CSS-Tricks](https://css-tricks.com/accessible-web-animation-the-wcag-on-animation-explained/)
* [Tuts+](https://webdesign.tutsplus.com/tutorials/a-guide-to-creating-accessible-animations--cms-32038)
* [Smashing](https://www.smashingmagazine.com/2018/04/designing-accessibility-inclusion/)

### Testable

The animations, being the part of the functionality of the application should be fully testable. This implies:
- Exposing primitives for unit/integration testing
- Exposing mechanisms to slow down or otherwise enhance animation for easier visual debugging

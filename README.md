# Interactive 3D Bloch Sphere Simulator

An interactive single-qubit quantum state simulator built with pure HTML5 Vector Canvas. Explore quantum state parameterization, polar angle $\theta$, azimuthal relative phase $\phi$, computational basis poles, and equatorial superpositions in real time.

🔗 **Live Web App:** [https://myhlow.github.io/bloch-sphere-simulator/](https://myhlow.github.io/bloch-sphere-simulator/)  
📖 **Companion Article:** [Bloch Sphere Basis States: X vs Z Gates & Phase Rotations](https://malcolmlow.com/2026/09/03/bloch-sphere-basis-states-x-z-gates/) by Malcolm Low

## Features
- **Interactive 3D Manipulation:** Click-and-drag rotation, pitch/yaw orbit, and scroll-to-zoom.
- **Section 1 Basis State Presets:** One-click snapping to:
  - $|0\rangle$ (North Pole, $+z$)
  - $|1\rangle$ (South Pole, $-z$)
  - $|+\rangle$ (Hadamard real superposition, $+x$)
  - $|-\rangle$ (Phase-flipped superposition, $-x$)
  - $|+i\rangle$ (Circular phase superposition, $+y$)
  - $|-i\rangle$ (Circular phase superposition, $-y$)
- **Angle Parameterization Controls:**
  - Polar Angle $\theta \in [0^\circ, 180^\circ]$ ($0$ to $\pi$)
  - Azimuthal Phase $\phi \in [0^\circ, 360^\circ]$ ($0$ to $2\pi$)
- **Real-Time Quantum Calculations:**
  - Dynamic visual probability bars for $P(0) = \cos^2(\theta/2)$ and $P(1) = \sin^2(\theta/2)$
  - Mathematical state expansion: $|\psi\rangle = \cos(\theta/2)|0\rangle + e^{i\phi}\sin(\theta/2)|1\rangle$
  - Complex amplitudes $\alpha, \beta$ and 3D Bloch coordinates $(r_x, r_y, r_z)$
- **Auto-Sweep Animation:** Live phase precession around the equator.

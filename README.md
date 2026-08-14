# aerofoil-simulation
## Phase 1 — Potential Flow Foundations 20/05/2026

## 13/08/2026
- **Reynolds number derivation**: needed to work through why local Δv/Δy 
  gets replaced with characteristic U/L — it's an order-of-magnitude 
  scaling argument, not an exact substitution. Ties to non-dimensionalising 
  Navier-Stokes properly — revisit once that's covered.
- **Mach number derivation**: was really interesting, involvement of speed of sound was cool
- **Introduced to practical application of these quantities**
## 14/08/2026
- Compressible vs incompressible: not a fixed property of a fluid — it's an approximation. Air is technically always compressible, but at low Mach (<0.3) density changes are small enough to ignore, which is what simplifies the equations for low-speed aerofoil work. At higher Mach, density changes become significant and can't be ignored - had to realise that compressibility was just an estimation 
- Physical intuition anchor: squashing a bag/balloon = forcing the same mass into a smaller volume = rapid density increase = rapid pressure increase (the "pop"). Same physics as air being compressed in front of a fast-moving aerofoil at high speed — just a slower, gentler version. At high enough speed this compression becomes severe enough to form shockwaves.
- Conservation of momentum introduces navier-stokes equations 

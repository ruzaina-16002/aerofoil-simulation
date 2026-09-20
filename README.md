# aerofoil-simulation
## Phase 1 — Potential Flow Foundations 20/05/2026

## 13/08/2026
- **Mach number derivation**: was really interesting, involvement of speed of sound was cool
- **Introduced to practical application of these quantities**
## 14/08/2026
- Compressible vs incompressible: not a fixed property of a fluid — it's an approximation. Air is technically always compressible, but at low Mach (<0.3) density changes are small enough to ignore, which is what simplifies the equations for low-speed aerofoil work. At higher Mach, density changes become significant and can't be ignored - had to realise that compressibility was just an estimation 
- Physical intuition anchor: squashing a bag/balloon = forcing the same mass into a smaller volume = rapid density increase = rapid pressure increase (the "pop"). Same physics as air being compressed in front of a fast-moving aerofoil at high speed — just a slower, gentler version. At high enough speed this compression becomes severe enough to form shockwaves.
- Conservation of momentum introduces navier-stokes equations

## 25/08/2026
- **Stream functions**: nned to understand multivariable chain rule to derive general stream functions only to find they're rarely used in pactice

## 16/09/2026
- Used rotational flow to work out general stream functions, this led to working out vorticity and using stokes theorem on a closed loop integral to calculate full circulation
- used irrotational flow with zero vorticity condition to derive velocity potential functions
- went through situations for assuming zero viscosity, and clear derivation from navier to bernoulli
- understood the nabla terminology used in mutlivariable calc, stokes' theorem can be used to rewrite the closed loop integral using vorticity, ∇xV gives the vorticity
- apply nabla with a quantity (A): ∇xA gives the curl of A, it is an operation that can be applied to a vector field to work out the amount of spin, when applied to velocity, it gives vorticity

## 20/09/2026
- Learnt more about the nabla operation, the divergence and curl, as well thr laplace, and how certain comditions allow stream eqautions and veloctity potential to satisfy laplace. 

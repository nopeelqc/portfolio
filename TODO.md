# Fernhollow — Delivery Outcomes

## Outcome 1 — Full-screen interactive night valley
- The page renders a fixed, full-screen black canvas layer behind the interface.
- Thousands of glowing flower/leaf particles create a layered night valley with depth, bloom-like halos, haze, dust and a subtle vignette.
- Wheel, touch and idle drift move the camera/travel position through the valley.
- Pointer movement repels nearby particles in screen space and influences the camera tilt.
- Hovering the round arrow eases the flight to a stop and disperses the particles; leaving reverses the transition.

## Outcome 2 — Fernhollow interface and typography
- The title is `Fernhollow` with metadata title `Fernhollow` and description `A regenerative design studio. Wander through a night valley of flowers that grows as you move.`
- The header contains the Fernhollow wordmark, `Work`, `About`, `Journal`, and a cream `Let’s talk` pill.
- The hero centers `Grown, not built.` with the supporting copy `Rooted in nature. Built for what’s next.` and a circular right-arrow CTA.
- The lower-right control reads `Scroll to wander`, includes a divider, and exposes an ambient sound button with explicit muted/playing states.

## Outcome 3 — Loading, audio and responsive behavior
- A full-screen loader with a pulsing cream dot fades away when the interactive scene is ready.
- The interface reveals smoothly after scene initialization.
- The sound control starts muted and toggles a generated ambient soundscape with accessible `aria-pressed` state.
- At 820px and below, navigation links hide, the headline can wrap, the CTA/header scale down, and bottom controls center above the viewport edge.
- Keyboard focus states and reduced-motion behavior are supported.

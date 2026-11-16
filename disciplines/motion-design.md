# Motion Design

Classify motion as feedback, orientation, transition, revelation or expression.

For every significant animation specify: ID; purpose; trigger; initial/final state; animated properties; duration; easing/timing; sequencing; interruption/re-entry; reduced-motion behavior; mobile behavior; performance notes; acceptance test.

Use CSS for simple transitions, component animation tools for local state changes, timeline tools for coordinated sequences, SVG for vector paths, Canvas/WebGL for custom visual systems. Verify current APIs and compatibility.

Honor `prefers-reduced-motion`; avoid flashing, excessive parallax, scroll hijacking and vestibular triggers. Essential content must not depend on animation completion. Prefer transform/opacity where suitable; simplify offscreen/background motion; test mid-range mobile hardware.

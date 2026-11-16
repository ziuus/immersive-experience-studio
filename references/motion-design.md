# Motion Design Reference

Motion should communicate state, hierarchy, spatial relationships, narrative progression, or feedback.

For every motion effect, specify:
- Trigger (load, scroll, hover, click, state change).
- What moves or transforms.
- Why the motion helps.
- Timing and easing character.
- Behavior on touch devices.
- Reduced-motion alternative.
- Performance implications.

Prefer transform and opacity when appropriate. Avoid unnecessary layout thrashing, perpetual movement, scroll hijacking, delayed access to content, and motion that blocks interaction. Do not add sound by default; if used, make it opt-in with clear controls. Use GSAP, Motion, CSS, Three.js, or other tools only when justified by project needs and existing stack.

HALLOWEEN JELLY — THREE LITTLE ISLANDS

Open index.html in a WebGL 2 browser. All scripts, geometry, shaders, icons and embedded original music and synthesised effects are inside index.html; no network requests or CDN dependencies. Upload these files to your GitHub repository root and enable Pages. A subfolder Pages path is supported. No build step is needed by players.

Mobile: tap the island tabs to switch, drag open jelly to stir, drag a block side to tip, pick up a floating treat or beach pebble and fling it, pinch to zoom, drag empty stage space to orbit. Tap a building/ghost for a small reaction. Toss adds a floating pumpkin, eyeball candy or wrapped sweet. More opens firmness, damping, tide, sound, pause and reset-view controls. Music and effects start with your first touch. More provides independent Music / Effects toggles and volume sliders; saved mute choices are respected.

Desktop: the same pointer actions; wheel zoom; right-drag orbit; Space tosses a floater, Shift+Space a sinking pebble, P pauses, R resets.

Scenes: Witch's Cove (pumpkin cottage), Ghostlight Garden (glass conservatory and moonflowers), Candy Carnival (pumpkin ferris wheel and candy stall).

Compatibility: requires WebGL 2. WebGL was chosen instead of the supplied WebGPU-only spec to widen mobile support. Reduced motion is respected; no strobing. Touch controls respect safe areas. Actual physical-phone/Loopit runtime validation is still required; source and numerical checks are not real-device FPS evidence.

Implementation: finite-difference shallow-water grid, fixed 1/120s water and 1/240s spherical buoyancy/contact steps. Screen-space jelly refraction and Beer-Lambert absorption are artistic approximations; no volumetric path tracing. Decorative scene models are authored procedural geometry, not image backgrounds. Concept images are design references and are not packaged as fake gameplay.

Source: work/halloween-jelly in the original workspace. window.__ij exposes the requested read-only state/counts plus step/drop/reset/stir/tilt helpers for diagnostics.

Credits: Three.js r180 — Copyright 2010-2025 Three.js Authors, MIT; see THREE-LICENSE.txt. All miniature scenery, procedural shading, interaction code, UI icons and synthesised sound design authored for this project.

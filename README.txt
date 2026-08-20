INWARD CLARITY — LOCKED SCREENS 1–2 MERGE CANDIDATE

SOURCE OF TRUTH
- Screen 1 / Welcome: Inward_Clarity_Welcome_Screen1_Responsive_LOCK_CANDIDATE_v6
- Screen 2 / Life Doesn't Stand Still: Inward_Clarity_Screen1_Responsive_v11_LOCK_CANDIDATE

PROTOCOL CLASSIFICATION
LOCKED
- Welcome desktop composition
- Welcome mobile responsive composition
- Welcome portrait asset and all internal styling/content
- Screen 2 typography, wording, dividers, mountain/background artwork, CTA, internal spacing
- Screen 2 mobile responsive behavior

ALLOWED TO CHANGE
- Screen 2 integration/container/background behavior on desktop
- Welcome OUTER wrapper/breathing background only, to match Screen 2 exact ivory

DO NOT TOUCH
- Locked screen internals listed above

INTEGRATION CHANGES
1. Structurally merged into one HTML/CSS project; no iframes.
2. Shared OUTER ivory is #f6f0e8, taken directly from the v11 Screen 2 CSS.
3. Welcome's internal locked panel remains #fbf7ef. Only its outer breathing wrapper uses #f6f0e8.
4. Welcome's existing desktop 100vh composition and mobile 8svh breathing bands are retained; no new inter-screen pixel spacing was invented.
5. Screen 2 desktop remains the exact 900×1350 internal composition and is allowed to occupy its full natural height; no viewport-height clipping wrapper was added.
6. Screen 2 outer section continues #f6f0e8 across the full browser width, eliminating a differently colored side canvas.
7. Screen 2 v11 mobile CSS values and behavior are preserved under a scoped selector.

MERGE CANDIDATE v2 INTEGRATION FIX:
- Outer shared ivory is #fffcef, derived from the actual v11 screen1-clean-bg.jpg edge pixels (median RGB 255,252,239), not guessed.
- Locked Screen 1 and Screen 2 internal composition/assets remain unchanged.

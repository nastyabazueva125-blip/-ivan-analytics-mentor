# Hero Design V4 - Current State

## What's Working:
- Subtitle and intro text are now visible on first screen
- Two-column grid layout: left text, right photo + trust card
- Glassmorphism trust card with proper styling
- Button structure matches redstone (pill + separate circle arrow)
- Header with glassmorphism on scroll
- Glitch effects: noise overlay, scan lines, text glitch on headline
- Text scramble animation on subtitle
- Scanline on photo
- Badges with dot prefix

## Layout:
- Left column: headline → subtitle → intro → badges → CTA
- Right column: photo → trust card
- Everything fits within viewport (only 72px overflow)
- Scroll indicator at bottom

## Lottie Animations:
- Background Lottie (abstract data pattern) - placeholder URL needs real one
- Photo accent Lottie - placeholder URL
- Trust card icon Lottie - placeholder URL
- These are loading from placeholder URLs, need real ones

## Visual Effects:
- Noise overlay (SVG turbulence filter)
- Glitch scan lines (3 animated lines)
- Random screen flash every 3-8 seconds
- Text scramble on subtitle
- Photo scanline effect
- Headline glitch (::before/::after with clip-path)

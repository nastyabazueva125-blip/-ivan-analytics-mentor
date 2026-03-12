# Redstone.software — Second Section Design Notes

## Layout:
- After hero: full-width portfolio showcase (large images/videos)
- Then a section with dark background (#0F0F0F or similar, slightly lighter than hero #020202)
- Two-column layout: left side has large text/heading, right side has cards/list items
- Cards have dark background with subtle borders, icons (geometric/abstract SVG icons)
- Each card has: icon + title (bold uppercase) + description text

## Visual Style:
- Background changes from pure black to slightly lighter dark (#0F0F0F or #111)
- Cards have rounded corners, subtle borders
- Icons are minimalist, geometric, white outline style
- Text hierarchy: large heading left, smaller card content right
- Plenty of whitespace between elements

## Animations (observed):
- Scroll-triggered fade-in animations
- Elements appear as you scroll into view
- Smooth transitions on cards
- Parallax-like effects on some elements

## Key takeaway for "About Me" block:
- Use slightly different dark background to create visual separation
- Large heading on one side
- Content/markers on the other side with card-like elements
- Scroll-triggered animations (IntersectionObserver)
- Keep the same typography and button system

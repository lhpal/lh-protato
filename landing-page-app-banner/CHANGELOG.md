# App download banner – experiment changelog

Experiment built on the landing page base (`landing-page-base-v1`). The banner only appears in the mobile view (under 900px).

Use `?v=a`, `?v=b` or `?v=c` to open a position directly, and add `&switcher=off` to hide the A/B/C switch for testers.

## 2026-11-16
- Banner content updated from Figma (213:2246): title "World's leading laundry app", new close icon, smaller light blue logo tile, 4.7 rating with a half star, 400k+ happy customers, Install. Banner height is now 64px.
- Title shortened to "World's leading laundry app". Banner side padding is 16px, matching the page, and the close icon is smaller (12px).

## 2026-11-13
- A: the banner now slides down from the top edge after 1 second, over the header, so it reads as a layer on top. Closing slides it back up.
- App icon reduced to 44px.

## 2026-11-12
- First version. Banner: close cross, Laundryheap app icon (Figma 205:2584), "It's just better on the app", ★★★★★ 4.7 rating, 400k+ happy customers, Install button.
- A: banner sits at the top in place of the header.
- B: banner is fixed to the bottom of the screen.
- C: banner sits above the header, and both stay stacked at the top while you scroll.
- The banner comes back on reload or when you switch position.

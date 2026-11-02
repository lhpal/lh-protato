# Changelog: Laundryheap mobile app prototype

Live at https://lhpal.github.io/lh-protato/customer-app/

Prices and service copy come from laundryheap.com/en-gb/pricing/<service>/pricelist. Layouts come from the Figma file "[EXT] For Claude".

## 2 Nov 2026: Book buttons linked

**New**
- **Book first order** on Home opens the Select a service screen.
- **Book now** at the bottom of Prices & services opens it too.
- Back returns to the screen you came from.

## 2 Nov 2026: Book now flow

**New**
- **Book now** in the bottom bar opens a new **Select a service** screen (Figma 184:1566) with five service cards. Back returns to Home.
- **Prices & more** on each card opens a details sheet that covers about 75% of the screen (Figma 184:1907). Close it with ✕, a tap outside, Escape, or by dragging the header down.
- The sheet has two tabs:
  - **Prices:**
    - Wash & Fold shows Mixed (£19.50 / 6kg) and Separate (£39.00 / 12kg), plus £3.75 per extra kg (Figma 184:2340).
    - The other four services show their full website price lists, with category tabs.
  - **About:** website tags and copy as bullet points (Figma 184:2149, 184:2365).
    - Wash & Fold follows the bullet grouping in Figma.
    - The other services use one bullet per sentence.
- The sheet always reopens on Prices, scrolled to the top.

**Fixed**
- The dashboard background behind the promotion cards is now white, as in Figma. It was light grey.

**Notes**
- Radio buttons on the service cards don't do anything yet, because there's no design for the selected state.
- "Book first order" on Home is still not linked.
- Two prices are deliberate:
  - Figma shows £2.95 per extra kg; the website price, £3.75, is used.
  - Wash & Iron "Jumper / Cardigan - Delicate" is £7.50, copied as the website shows it.

## 28 Oct 2026
- The dashboard header now stays fixed on phones; only the content below it scrolls.

## 27 Oct 2026: First test build (Prices flow)
- Home dashboard from Figma 127:1150.
- **Prices & services** screen: the Prices tab goes straight here, with no services list in between (this is what the test checks).
  - Five swipeable services, with website prices.
  - Always opens on Wash & Fold.
- "See what 6kg looks like" bottom sheet with 4 slides ("Big armful of clothes" left out on purpose).
- **Learn more** service details screens with website copy.
- Tab title "UX Proto: Laundryheap Mobile App", and a heart favicon with a play mark.

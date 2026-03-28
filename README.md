# Wedding Vendor Tracker

A beautiful, single-file wedding vendor comparison tool. No build step, no dependencies, no server -- just open `index.html` in any browser.

**Live site:** [https://timothyryanwalker.github.io/wedding-vendor-tracker/](https://timothyryanwalker.github.io/wedding-vendor-tracker/)

## Features

- **Category tabs** -- Filter by Photography, Videography, or Cake & Bakeries
- **Vendor cards** -- See packages, pricing, and notes at a glance
- **Status tracking** -- Mark vendors as Researching > Contacted > Booked > Passed (saved to localStorage)
- **Personal notes** -- Add your own notes to each vendor (saved to localStorage)
- **Comparison mode** -- Select 2+ vendors and compare them side-by-side
- **Export** -- Download as CSV or print to PDF
- **Dashboard** -- Summary stats with vendor counts, bookings, and price range

## Quick Start

1. Visit the GitHub Pages URL above, or open `index.html` locally
2. Browse vendors, update statuses, add notes
3. Use checkboxes + "Compare Selected" for side-by-side comparison

## Updating Vendor Data

Edit the `vendors` array at the top of the `<script>` section in `index.html`. Each vendor follows this shape:

```javascript
{
  id: "v1",
  category: "photo",  // "photo" | "video" | "cake"
  name: "Studio Name",
  email: "email@example.com",
  packages: [
    { name: "Package Name", price: "$X,XXX", details: "What's included" }
  ],
  notes: "Extra info from vendor emails"
}
```

## Design

Refined luxury wedding aesthetic -- cream/ivory backgrounds, dusty rose & sage accents, gold details, Cormorant Garamond display font paired with Jost body font. Fully responsive and mobile-friendly.

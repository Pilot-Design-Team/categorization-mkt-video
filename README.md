# Meridian — marketing video assets

Video, chart and product assets for Meridian marketing, one collection per
feature. `index.html` is the homepage linking to each collection's page, where
everything previews with download buttons.

| page | collection |
|---|---|
| `custom-checklists/index.html` | **Custom Checklists** — files in `custom-checklists/video/` |
| `categorization/index.html` | **Categorization** — files in `video/`, `charts/` and `screens/` at the root |

`posters/` holds the cover image for each collection on the homepage.

## Custom Checklists

| file | length | what it shows |
|---|---|---|
| `custom-checklists-01-create.mp4` | 31.1s | Building a checklist in the checklist editor |
| `custom-checklists-02-assign-and-customize.mp4` | 31.4s | Assigning a checklist to a client and customizing it |
| `custom-checklists-03-client-level-steps.mp4` | 24.1s | Steps that belong to one client only |
| `custom-checklists-04-checklists-and-meridian-ai.mp4` | 14.1s | Using a client's checklist with Meridian AI |

All four are H.264, 1920&times;1080.

## Categorization

| folder | contents |
|---|---|
| `video/` | Animated builds — `.mp4`, H.264, 1920&times;1080, 30fps |
| `charts/` | The same diagrams as standalone `.svg`, for stills or re-animation |
| `screens/` | Screenshots of the real product UI, PNG at 2&times; |

### Categorization videos

| file | length | what it shows |
|---|---|---|
| `categorization-inter-entity-transfer.mp4` | 12.8s | Money moving between two entities the same owner controls is booked to the balance sheet, not as an expense |
| `categorization-manual-corrections.mp4` | 12.0s | Share of categorizations a human had to correct, before and after the agent |
| `categorization-auto-rate.mp4` | 14.0s | Share of transactions the agent categorizes on its own |
| `categorization-context-and-outcomes.mp4` | 17.5s | What the agent reads, and where a transaction can land |
| `categorization-prepaid-amortization.mp4` | 19.6s | An annual software renewal booked as a prepaid and released monthly |
| `vendor-categorization-flow.mp4` | 10.0s | Setting how a vendor's transactions get categorized |

### Categorization screens

`screens/*-panel.png` are the side panel on its own, with the page background
removed — useful if you want to composite it over something else. On the preview
page each of those sits behind a **Panel only** tab next to the full-page shot.

## Notes for editing

- Everything is landscape 1920&times;1080 at 30fps, on white. There are no
  transparent-background versions in this repo; ask if you need them and they
  can be exported as ProRes 4444 `.mov`.
- Durations vary by content rather than being cut to a fixed length.
- The headline type is **Euclid Circular B**, which is a commercial licence and
  so is not included here. It is already rendered into the videos and stills, so
  they display correctly everywhere. Only the preview page falls back to another
  face on machines without it — that affects the page chrome, not the assets.

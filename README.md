# Fisher Construction — homepage concept

A redesigned homepage for [Fisher Construction, Inc. (Fisher Built)](https://fisherbuilt.com/), a high-end custom home builder in Dana Point, CA, prepared by OakSpin AI as a pitch concept.

**Live preview:** https://oakspin-ai.github.io/fisher-construction-homepage/

## What changed from the current site

- **Readable on a phone.** The current site scales a fixed desktop page down to tiny menus and copy. This one is fully responsive, with a sticky "Call Scott" / "Start a project" bar.
- **Recommendations on the homepage.** The named recommendations (Michael Crawford, Glenn Bianchi and Dana Point building official Tom Findley) were on an inner page. Each one now sits next to the home it describes.
- **Case studies, not just galleries.** Each project shows its size, style and location alongside its photos. Homes Scott built while co-owner of another company are labelled that way, as on the current site.
- **The process is the selling point.** Daily and weekly reports, three bids per trade, bi-weekly billing spreadsheets and the closeout binder are shown as a clear five-step sequence under "No surprises", in the client's own words.
- **A way to get in touch.** The site had no inquiry form. The new one asks for project type, location, plan status and timing, then opens a pre-filled email to Scott.
- **Brand kept, used better.** The original logo stays. Its three blue blocks are set at the base of the hero photo like a cornerstone, and the navy and harbor blue are used as accents on calm whites and coastal greys.
- **Benchmarked against the best in the segment.** The layout is calibrated against leading luxury builders: Patterson Custom Homes and Winkle Custom Homes in Newport Beach, Dowbuilt, and Marmol Radziner. From them it takes a single full-width hero photograph, projects named by place and scope, and matted photo frames that let smaller archive photos look curated.

## Stack

A single static `index.html` with inline CSS and a little vanilla JS. Fonts: Libre Caslon Display/Text (headings and quotes) and Hanken Grotesk (body and UI) from Google Fonts. Images come from Fisher Built's own site and are optimized WebP with JPEG fallbacks in `assets/img/`.

Run locally:

```bash
python3 -m http.server 8743
```

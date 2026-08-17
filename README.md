# eDNAtlas

A living map of environmental DNA (eDNA): machine-readable for the scientists who generate it, and human-readable for everyone who lives with the results.

Built at the Decode the Ocean hackathon, sponsored by Lovable and the United Nations, where it won first place.

**Live app: https://adrianerlikhman.is-a.dev/eDNAtlas**

## The problem

You can sample a whole marine community from a single litre of seawater. eDNA reads the shed cells of everything that passed through, so the collection problem is already solved. The results, though, usually ship as raw sequence tables that a harbour commissioner, a fisher, a city council, or a science teacher cannot act on.

## What eDNAtlas does

It puts eDNA on a map. Click a site and you get one number and one plain-language sentence about what it means. Go a click deeper for the evidence: an Ecosystem Health Index with its components, the taxa detected, and downloadable FASTQ / ASV tables in Darwin Core.

One artifact serves two audiences. Underneath is a standards-compliant, queryable index. On top is a page you can read without a biology degree.

The app has four parts:

- **Map** with clickable sample sites and a live detail panel (glance, plain-language meaning, and the raw evidence, plus generated sample downloads).
- **Rankings**, a habitat-matched leaderboard so a site is only compared against like-for-like habitat.
- **Discoveries**, a dashboard of novel and non-native detections and per-site diversity.
- **Method**, the FAIR pipeline and the scoring-component breakdown.

## Standards

Darwin Core plus the DNA-derived data extension, in and out, so records can publish onward to GBIF and OBIS instead of forming another silo.

## Running it

`index.html` is the app, fully self-contained. Open it in a browser or serve the folder statically. No build step.

`deck.html` is the original pitch deck from the hackathon (arrow keys move between slides, F for fullscreen).

Site-level figures are illustrative sample data for Southern California. The interaction, the scoring model, and the layout are the deliverable.

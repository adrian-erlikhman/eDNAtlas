# eDNAtlas

A living map of environmental DNA (eDNA): machine-readable for the scientists who generate it, and human-readable for everyone who lives with the results.

Built at the Decode the Ocean hackathon, sponsored by Lovable and the United Nations, where it won first place.

Live demo: https://adrianerlikhman.is-a.dev/eDNAtlas

## The problem

You can sample a whole marine community from a single litre of seawater. eDNA reads the shed cells of everything that passed through, so the collection problem is already solved. The results, though, usually ship as raw sequence tables that a harbour commissioner, a fisher, a city council, or a science teacher cannot act on.

## What eDNAtlas does

It puts eDNA on a map. Click a site and you get one number and one plain-language sentence about what it means. Go a click deeper for the evidence: an Ecosystem Health Index with its components, the taxa detected, and downloadable FASTQ / ASV tables in Darwin Core.

One artifact serves two audiences. Underneath is a standards-compliant, queryable index. On top is a page you can read without a biology degree.

## Standards

Darwin Core plus the DNA-derived data extension, in and out, so records can publish onward to GBIF and OBIS instead of forming another silo.

## Running it

`index.html` is a self-contained interactive pitch deck. Open it in a browser. Arrow keys move between slides, F toggles fullscreen, and the map on slide 5 is clickable.

Site-level figures in the deck are illustrative sample data for Southern California. The interaction, the scoring model, and the layout are the deliverable.

## Built at the hackathon

Interactive map with clickable sample sites, the Ecosystem Health Index and its scoring components, plain-language site readouts, habitat-matched comparison and a leaderboard, a discovery dashboard for novel and non-native detections, and the Darwin Core ingest schema.

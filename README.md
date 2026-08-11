# Adviser Nexus

A geographical visualization of recruiters and the advisers they have brought in, mapping revenue, tenure, and recruitment channels across the UK. This project adapts the "nexus" concept originally explored in change ringing to the problem of recruiter impact.

**https://nihilisticiconoclast.github.io/adviser-nexus/**

## The Recruiter Nexus

The visualization portrays recruiters as stars and their recruited advisers as orbiting bodies. 
It encodes multiple dimensions of data:
- **Turf**: Positioned at the centroid of the territory
- **Revenue introduced**: Star radius (√-scaled)
- **Recruiter tenure**: Luminosity (corona width and diffraction spikes)
- **Adviser tenure**: Orbital radius
- **Adviser revenue**: Body radius
- **Joiner channel**: Categorical or spectral hue
- **Departures**: Recruiters who leave collapse into black holes, while departing advisers slip their orbit on a fading tail

## Status
- [x] Initial conceptualization and design
- [x] Geographic plotting against real UK coastline
- [x] Canvas-based visualization of stars and orbits
- [x] Interactive filtering (e.g., clicking a class to isolate)
- [x] Mobile and desktop responsive layouts

## Repository layout

```
index.html              -- The self-contained visualization plate
claude-chat.txt         -- Original design session log outlining the data encodings
adviser-nexus still.jpg -- A static snapshot of the visualization
```
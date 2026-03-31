# Introduction

## What is WoRMS?

The **World Register of Marine Species (WoRMS)** is the authoritative global checklist of all
known marine species. It is maintained by a network of taxonomic experts and provides:

- Validated, accepted scientific names with full synonymy
- Taxonomic classification (kingdom → species)
- Trait / attribute data (functional groups, IUCN status, habitat)
- Geographic distribution records
- Cross-links to external databases (GBIF, BOLD, …)

**Website:** <https://www.marinespecies.org/>

## What is `worrms`?

`worrms` is the official R client for the WoRMS REST API, developed by
[rOpenSci](https://ropensci.org/). It wraps every public API endpoint into
tidy, tibble-returning R functions.

**Key design principles:**

- Every function name begins with `wm_` (WoRMS marker)
- Functions ending in `_` accept **vectorised** inputs (multiple IDs / names in one call)
- All results are returned as `tibble's` or lists of `tibble's`

## Tutorial content

1. Install and load `worrms`
2. Walk through **every** function family with Antarctic examples
3. Demonstrate a full biodiversity use-case combining `worrms` with the **GBIF** occurrence data
   (via `rgbif`)

## Github Pages:
- https://thesnakeguy.github.io/worrms_tutorial/worrms_antarctic_slides.html
- https://thesnakeguy.github.io/worrms_tutorial/worrms_antarctic_tutorial.html

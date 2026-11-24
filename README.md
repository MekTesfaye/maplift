# MapLift

A one-page static site for MapLift, a Blacklight Marketing service that helps Gold Coast trades get more calls from Google Maps.

Live site: https://mektesfaye.github.io/maplift/

The GitHub account that publishes this site is [MekTesfaye](https://github.com/MekTesfaye) (the former login Crimson-sky07 was renamed).

## Local preview

The site is plain HTML and CSS. No build step, no JavaScript framework, no form backend, and no tracking.

```bash
python3 -m http.server 8080 --directory .
```

Then open http://localhost:8080/

## Content notes

- Copy is Gold Coast only.
- Prices are marked as “from” and labelled indicative.
- The main call to action is a `mailto:` link to mekdimtesfaye07@gmail.com, with a pre-filled subject for the free Maps visibility check.
- The ABN is intentionally omitted.
- The hero photograph is a generated image of a homeowner on a suburban lawn, looking at a phone. The screen is unreadable, with no maps or brand interface. See CREDITS.md.

## Fonts

Source Sans 3 and Source Serif 4 are self-hosted under the SIL Open Font License. Licence files are in `fonts/`.

## Pages setup

GitHub Pages is served from the `main` branch, site root (`/`). A `.nojekyll` file is included so GitHub does not process the files with Jekyll.

# Shapely Widgets landing page

Static landing page for the Shapely Widgets Android app (`com.shapely.widgets`), served by GitHub Pages:
**https://ahaariyan.github.io/shapely/** (repo `AHAariyan/shapely`).

- `index.html`, `styles.css`: the whole page. No build step, no frameworks, no web fonts, no trackers.
- `assets/`: real widget renders (ShapeWidgets `docs/store/phone/`, caption cropped, as WebP), icons, `og.png`.
- Google Play buttons carry `data-play`: the page copies any `utm_*` tags from its own URL into Play's
  `referrer`, so Play Console credits the post that sent the visit.
- Copy follows the Play listing (`ShapeWidgets/docs/PLAY_LISTING.md`): no third-party names.
  The MET Norway credit in the footer is required by the weather data licence (CC BY 4.0).
- Privacy policy lives in its own repo: https://ahaariyan.github.io/shapely_widget_privacy/

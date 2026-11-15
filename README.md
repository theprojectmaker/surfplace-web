# SurfPlace (web preview)

A browser version of the SurfPlace iPhone app: same code, same screens, built with `npx expo export --platform web`
from [theprojectmaker/surfplace-ios](https://github.com/theprojectmaker/surfplace-ios) (`scripts/build-web.mjs`).

Open it on a phone for the best view. Forecasts come from Open-Meteo and tides from NOAA. NOAA's live buoy feed
cannot be read from a web page, so live buoy readings (and the forecast check against them) are iPhone-app only.

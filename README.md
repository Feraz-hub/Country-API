# Country Explorer

A browser-based country explorer built with HTML, CSS and vanilla JavaScript. This frontend practice project works with country data, search, region filtering and a light/dark theme.

**[Developer portfolio](https://feraz-hub.github.io/)** · **[Browse source](./script.js)**

## What the code covers

- Fetching country data from the REST Countries API.
- Rendering country flags, population, region and capital.
- Searching country names and filtering by region.
- Displaying a selected country's details and border countries.
- Switching between light and dark themes.

## Stack

HTML · CSS · JavaScript · Fetch API · REST Countries

## Run locally

No package installation or build step is required. With Python 3 installed:

```bash
git clone https://github.com/Feraz-hub/Country-API.git
cd Country-API
python -m http.server 8000
```

Open [localhost:8000](http://localhost:8000). On Windows, use `py -m http.server 8000` if `python` is not available.

## Project map

| File | Purpose |
| --- | --- |
| `index.html` | Main interface and country detail view |
| `script.js` | API request, filtering, theme and detail rendering |
| `style.css` | Layout and theme styles |
| `design/` | Design reference assets |

## Status and next steps

An early frontend learning project. The implementation uses the legacy `https://restcountries.com/v2/all` endpoint and its v2 response shape; confirm API compatibility before using it as a live demo. API error/loading states, country-detail edge cases and keyboard accessibility are areas for further work.

## Attribution

Based on the [Frontend Mentor REST Countries challenge](https://www.frontendmentor.io/challenges/rest-countries-api-with-color-theme-switcher-5cacc469fec04111f7b848ca). Design brief and supplied assets belong to their respective owners.

## Author

[Feranmi Adenaya](https://feraz-hub.github.io/) · [GitHub](https://github.com/Feraz-hub)

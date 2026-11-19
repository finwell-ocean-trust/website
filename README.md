# Finwell Ocean Trust — Website

**Live site:** https://finwell-ocean-trust.github.io/website/

Finwell Ocean Trust is an independent, science-led nonprofit working to end shark finning, reform destructive fishing practices and protect the marine ecosystems that more than three billion people rely on for food and livelihoods. Since our founding in Monterey, California in 2011, we have tagged and tracked sharks across the Eastern Pacific, campaigned for enforceable fin-trade bans and marine protected areas, and funded early-career ocean researchers in coastal nations through the Finwell Fellowship. We work alongside fishing communities in Mexico, Ecuador and Fiji, because sharks will only be protected when the people who share the water with them have a reason, and the means, to protect them.

## About this repository

This repository holds the source for our public website: the homepage, the About page and the shared stylesheet. It's a small static site of plain HTML and CSS, with no build step and no backend, published with GitHub Pages from the `main` branch.

| File          | What it is                                             |
| ------------- | ------------------------------------------------------ |
| `index.html`  | Homepage: mission, impact figures, programs, partners  |
| `about.html`  | Our story, milestones and leadership team              |
| `styles.css`  | Shared styles: brand colors, typography and layout     |
| `favicon.svg` | Site icon                                              |

Impact figures on the homepage are cumulative and are updated each year when our annual impact report is published.

## Running the site locally

The simplest option is to open `index.html` directly in a web browser.

To preview the site the way it's served online, with working links between pages, run a local server from the repository folder:

```sh
npx serve .
```

or, if you have Python installed:

```sh
python -m http.server 8000
```

Then open the address shown in your terminal (for example http://localhost:8000).

Changes merged into `main` are published automatically and usually go live within a few minutes.

## Contributing and contact

The site is maintained by the Finwell communications team. To report a broken link, a typo or outdated information, open an issue in this repository or email us at hello@finwelloceantrust.org.

For press, partnership or donation enquiries, please contact info@finwelloceantrust.org.

## License

The website code is available under the MIT License. Written content, photography and the Finwell Ocean Trust name and logo are © 2011–2026 Finwell Ocean Trust and may not be reused without permission.

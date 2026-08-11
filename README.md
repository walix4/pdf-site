# Pakistan Diaspora Fund

Marketing site for **Pakistan Diaspora Fund** — a public registry where overseas
Pakistanis record conditional investment commitments to Pakistan.

**Live:** https://walix4.github.io/pdf-site/

> No funds are collected, transferred, or owed. The registry records commitments
> that activate only if seven governance conditions hold.

## Pages

| File | Purpose |
|---|---|
| `index.html` | Homepage — hero, commitment types, investment categories, seven principles, registry, pledge form |
| `mission.html` | Why the platform exists — diaspora-finance precedents, Pakistan's ingredients, the confidence problem, phased rollout |
| `model.html` | Ten funding mechanisms and the illustrative path to $20B |
| `network.html` | Pakistan Global Knowledge & Skills Network — brain circulation, eight programmes |

## Stack

Static HTML. No build step, no framework, no dependencies to install — open a file
or serve the folder.

```bash
python3 -m http.server 8000
```

External resources are CDN-loaded: Google Fonts (Inter, Inter Tight),
Font Awesome 6.5.2, flag-icons 7.2.3.

## Assets

`assets/` holds five licensed photographs (Hunza Valley, Islamabad from the
Margalla Hills, Minar-e-Pakistan, Badshahi Mosque, and a diverse professional
team), optimised for web.

## Data status

**All figures on this site are placeholder or client-supplied and are not
independently verified.** Registry entries, pledge totals, country breakdowns and
testimonials are illustrative sample data for design purposes. Dollar targets in
`model.html` are stated potentials, not commitments or forecasts. Replace with
live records and verify all sourced statistics before launch.

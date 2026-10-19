# Iverium Software

Wij bouwen websites, webapplicaties en apps voor ondernemers in Groningen en Drenthe, en zorgen dat ze gevonden worden in Google.

[www.iverium.nl](https://www.iverium.nl) · [Portfolio](https://www.iverium.nl/portfolio) · [Contact](https://www.iverium.nl/contact)

## Open source

De gratis tools op onze website zijn open source. Ze gebruiken alleen de Python-standaardbibliotheek en vallen onder de MIT-licentie.

| Repository | Wat het doet | Probeer het online |
| --- | --- | --- |
| [website-check](https://github.com/Iverium/website-check) | Scoort een pagina op vindbaarheid: Google, lokaal, mobiel, snelheid en beveiliging | [Website-check](https://www.iverium.nl/website-check) |
| [toegankelijkheid-check](https://github.com/Iverium/toegankelijkheid-check) | Controleert automatisch de toetsbare onderdelen van WCAG 2.1/2.2 | [Toegankelijkheidscheck](https://www.iverium.nl/toegankelijkheid-check) |
| [cookie-check](https://github.com/Iverium/cookie-check) | Bekijkt welke cookies en trackers laden voordat een bezoeker toestemming geeft | [Cookiecheck](https://www.iverium.nl/cookie-check) |
| [google-reviewlink](https://github.com/Iverium/google-reviewlink) | Maakt van elke Google Maps-link een directe reviewlink, zonder API-sleutel | [Reviewlink maken](https://www.iverium.nl/google-reviewlink-maken) |
| [tinyqr](https://github.com/Iverium/tinyqr) | QR-codes als SVG of PNG in pure Python, zonder afhankelijkheden | |

De drie checks halen pagina's veilig op: alleen openbare adressen, met bescherming tegen SSRF. Daardoor kunt u ze ook zelf in een webdienst aanbieden. Met `--min-score` kunt u ze in een CI-pipeline gebruiken.

## Onderzoek

Hoe vindbaar zijn ondernemers in het noorden? Met dezelfde website-check hebben we de websites van lokale bedrijven per gemeente onderzocht. Lees [ons onderzoek](https://www.iverium.nl/onderzoek).

## English

Iverium Software is a web and app development studio in the north of the Netherlands. The free tools on our website are open source and listed above:
- a local-SEO website check
- an automatic WCAG accessibility check
- a cookie and consent check
- a Google review link generator
- a dependency-free QR encoder

They use only the standard library and are MIT licensed. The reports are in Dutch.

# 99stype

A personal reference wiki for the Jaguar S-Type (X200, 1999&ndash;2008). Built with
plain HTML and CSS — no frameworks or build tools.

## Pages

| Page | Content |
|------|---------|
| `index.html` | Wiki home / hub |
| `overview.html` | Model history, timeline, and variants |
| `specs.html` | Dimensions, weights, capacities, performance |
| `engines.html` | Full engine lineup (AJ-V6, AJ-V8, supercharged, diesel) |
| `mechanical.html` | Transmissions, drivetrain, suspension, brakes, steering |
| `body.html` | Panels, paint colours, wheels and tyres |
| `interior.html` | Trim, wood/leather options, electronics |
| `maintenance.html` | Service intervals, fluids, torque, common faults, log |
| `gallery.html` | Categorized photo archive |
| `resources.html` | Manuals, links, part numbers |

Shared styles live in `css/styles.css`. Photo folders are under `images/`.

## Viewing

Open `index.html` directly in a browser, or serve locally:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Adding content

Bracketed values `[ ... ]` are placeholders — fill them in as data is verified.

- **Photos:** drop images into `images/<category>/` (exterior, interior, engine,
  detail, events) and swap the placeholder blocks in `gallery.html` for `<img>` tags.
- **Technical data:** edit the tables in `specs.html`, `engines.html`,
  `mechanical.html`, `body.html`, and `maintenance.html`. Verify figures against the
  factory workshop manual.
- **Story:** rewrite the placeholder paragraphs in `overview.html` and `index.html`.
- **Logs:** add rows to the maintenance log and part-number tables as you work on
  the car.

## Notes

Technical figures on this wiki are a reference starting point. Always confirm against
the factory workshop manual and the owner&rsquo;s handbook before relying on them for
repairs.
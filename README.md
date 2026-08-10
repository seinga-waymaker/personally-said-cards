# Personally Said - Card Templates

Static, per-design landing pages for Personally Said keepsake cards.

Each design lives in its own folder (e.g. `card-03/`) and is deployed as-is —
one page per design, not per order. At load time, a small loader script reads
`?order=CODE` from the URL and fetches `card-03/data/CODE.json` to populate
the message text and audio source.

Deployed via GitHub Pages at cards.personallysaid.co.

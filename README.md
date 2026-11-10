# Kindle & Cloth

Static site for https://kindleandcloth.github.io/ (GitHub Pages user site, plain HTML/CSS, no trackers).

## Affiliate placeholders
Every affiliate link is `<a href="#" class="aff-link" data-aff="PROGRAM:BRAND" rel="sponsored nofollow">`.
Find them with: `grep -rn 'data-aff=' --include=*.html .` and replace `href="#"` with the real tracking link.
Programs used: `awin:` (rent-my-wedding, rizz-invites, dogwood-hill, capucinne, ring-bear) and `amazon:` (everyday items).

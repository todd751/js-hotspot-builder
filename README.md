# js-hotspot-builder

Client-side JavaScript for the internal **Hotspot Builder** tool
(Shoppable Image → Shopify Metaobject) used on AURA Modern Home and BathGems.

The file `hotspot-builder.js` is loaded by the Shopify page template
`templates/page.hotspot-builder.liquid` via jsDelivr:

https://cdn.jsdelivr.net/gh/todd751/js-hotspot-builder@main/hotspot-builder.js

Hosting the script here (instead of inline in the theme) prevents Shopify's
page processing from truncating the large inline script. Internal tool —
not linked in navigation, noindex.

# AgriKoła

Experimental, small project, as aggregation of surnames in a form of grid, grouped by surname specific of root and endings.

# Naming

Just a words play... but:

- [agricola](https://glosbe.com/la/en/agricola) - latin word, which means "farmer" or "peasant" or "agrarian". In genealogical communities, especially beginners do not know this meaning (when they translate Latin-Polish texts to Ukrainian), so I wanted to spread it out.
- Main purpose of project is to aggregate data from other services and files.
- [Koła](https://en.wikipedia.org/wiki/Ko%C5%82a) is a noble surname in 1470-1480 years in East Galicia (Ukraine), whom I'm trying to research more, because someone from them might be related to history of village where I born. _Koła_ is a polish version, and latin form of surname is _Cola_.

# Description
Based on list of "root" part of possible surnames, JavaScript code concatenate with "ending" with possible surnames, and combine in one word. Then hyperlink created referring to well known service [Ridni.Org](https://ridni.org/karta/).

# TODO
- Tooltip with project description.
- Integrate with `ridni.org` via API calls for map preview. Maybe via `iframe`???
- Ask if `https://ridni.org/kartafiles/php/ridni_get_legend_data.php?surname=%D0%BB%D1%83%D0%BD%D0%B4%D1%8F%D0%BA&isNames=true&isRegion=true` can return image (snapshot, pre-rendered).
- Download PNG API call exists? `https://ridni.org/kartafiles/js/ridni_raster.js`


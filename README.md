# Haynes Pool Service: sample site

A one-page sample site I put together for Haynes Pool Service (Southlake, TX). It's a concept, not their official website, and it says so at the top of the page and in the footer.

Live preview: https://preview-haynes-pool.vercel.app

The request form doesn't send anything to a server. It just opens your own email app with a message addressed to govnor@gmail.com, and the phone buttons dial (682) 306-9899. There's no tracking or analytics, and the fonts are self-hosted.

## What's on the page

Only details from Haynes Pool Service's own website (as archived) and public listings: business name, Southlake address, phone, email, and service areas from haynespoolservice.com. Services mentioned (weekly year-round care with no contract, plus equipment, plumbing and electrical repairs) are taken from that same page. Anything I couldn't confirm, including hours, reviews, ratings, prices, years in business or team photos, is left out. There is no owner portrait.

## Photos

Stock photos from Pexels, used under the Pexels License (https://www.pexels.com/license/). They're there for mood. None of them shows Haynes Pool Service, its people or its work.

- `pool-handrails.jpg`: "Handrails in a Corner of a Swimming Pool" by Mihman Duğanlı on Pexels (https://www.pexels.com/photo/handrails-in-a-corner-of-a-swimming-pool-19281006/)
- `turf-ladder.jpg`: "Inviting Poolside Scene in Chefchaouen, Morocco" by A. on Pexels (https://www.pexels.com/photo/inviting-poolside-scene-in-chefchaouen-morocco-38987604/)
- `goggles.jpg`: "Photo of Slippers Beside Goggles" by Atlantic Ambience on Pexels (https://www.pexels.com/photo/photo-of-slippers-beside-goggles-12932253/)

Fonts: Fredoka, Nunito (Google Fonts, SIL Open Font License). Full details are in `assets/provenance.json`.

## Indexing

The page has `noindex, nofollow` in a meta tag and in the `X-Robots-Tag` header (`vercel.json`), and `robots.txt` disallows everything, so it shouldn't turn up in search.

Eustace Crentsil

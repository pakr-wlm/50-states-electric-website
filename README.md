# 50 States Electric: homepage

Free homepage rebuild for 50 States Electric, LLC (Atlanta, GA). Ship `index.html`: one self-contained file (CSS and images inlined). Edit `index.src.html` and `styles.css`, then run `python build.py`.

## Real data
- **Google rating:** 4.7 across 36 reviews, read from their Google Business Profile (Sept 2026). Also in the JSON-LD.
- **Reviews:** 6 verbatim Google reviews (Margaret Dalbey, Krish Chopra, Kathleen Williams, alfred marshall, Jennifer Morrow, Thomas Madden). Their old site's /reviews page also has 5 reviews, but they date from 2014 to 2017, so they are not used.
- **From their own site:** phone (404) 416-1470, email 50stateselectric@gmail.com (used by the quote form), address 2020 Howell Mill Rd NW Suite D350, Mon-Fri 8am-6pm, the 26-item service list (grouped into 9 cards), the town list, lifetime warranty terms, "licensed by the State of Georgia", 24/7, and the $49.95 written-quote policy.
- **Logo and colors:** logo from their site, cropped. Navy and red sampled from its pixels.

## Placeholders / to confirm
- Hero, About and all 4 Recent Work photos are Pexels stock (credited in `index.src.html`). Replace the Recent Work tiles first. Their /pictures page has one real photo (burnt and melted breakers) that could be used in a before/after.
- No owner photo or founding story on their site. About copy restates their own wording. Reviewers all name "Gerald"; BBB lists Gerald Palma as owner. Confirm before naming him on the page.
- No license number or years-in-business figure found (a directory says 2016, unconfirmed).
- The $49.95 quote fee and warranty terms come from their About page. Confirm they are still current.
- Individual star ratings on the reviews are left out of the JSON-LD (the Google listing text does not show them).
- No "free estimate" claim is made; button says "Request a Quote".
- Nav links are inert (homepage-only teaser).

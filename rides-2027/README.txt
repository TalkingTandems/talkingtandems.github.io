TALKING TANDEMS — RIDES & EVENTS 2027

Files:
- index.html: responsive, accessible programme page
- rides2027.json: editable ride data

PUBLISH
1. Create a folder named 'rides-2027' in the TalkingTandems/talkingtandems.github.io repository.
2. Upload index.html and rides2027.json into that folder.
3. Open https://talkingtandems.github.io/rides-2027/ to check the page.
4. In Wix, open Rides & Events, Add Elements > Embed Code > Embed a Site.
5. Enter https://talkingtandems.github.io/rides-2027/ and set the embed to full content width, with a generous height (e.g. 1100–1600px, adjust after adding rides).
6. Publish the Wix site. If Wix restricts the embed or scrolling is awkward, use a clear link from the Wix Rides & Events page to the hosted programme instead.

ADD A RIDE
Edit rides2027.json. Add objects in the 'rides' array, for example:
{
  "date": "2027-04-10",
  "title": "Example ride — replace before publishing",
  "start": "Dalgety Bay Sailing Club",
  "time": "10:00",
  "distance_miles": 26,
  "description": "Ride details to be confirmed.",
  "refreshments": "To be confirmed",
  "status": "planned",
  "route_url": "https://talkingtandems.github.io/",
  "event_url": ""
}
Separate multiple rides with commas. Use date format YYYY-MM-DD.
Status may be planned, cancelled, postponed or completed. Only real, confirmed ride dates should be added.

The Next Ride card automatically shows the first future non-cancelled ride. The full programme remains in date order, including cancelled and completed rides.

Accessibility: semantic headings, keyboard-focus indicators, descriptive links, no colour-only status, mobile responsive. Distances in miles.

Important: The file uses fetch() for JSON. Open via GitHub Pages or another web server; opening index.html directly from your computer may block JSON loading.

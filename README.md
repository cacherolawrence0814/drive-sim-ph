# Drive Sim PH

A browser-based 3D driving game that teaches Philippine road rules while you drive. Pick a Toyota Vios, Toyota Hilux, Honda Civic Type R or Suzuki Jimny, tackle hills, mud, a flooded road and a river ford, and get scored like a real driving test.

**Play:** `https://<your-username>.github.io/<repo-name>/` (after enabling GitHub Pages) or just open `index.html` in a browser.

## Features
- Four cars with different top speed, acceleration, handling and off-road grip
- Terrain: steep hill, two mud pits, a flooded road, a river crossing
- Rule scoring each lap (starts at 100):
  - Stop at red lights (-20 for running a red)
  - Speed limits: 80 km/h open road, 30 km/h city zone, 20 km/h school zone
  - Give way to the pedestrian on the crossing (-15)
  - Give way to the vehicle on your right at the unmarked intersection (-15)
  - Pull over to the right for the ambulance (-15)
  - Leaving the road (-3), entering mud or water too fast (-5)
- Driver rating: 85+ Professional driver, 76 to 84 Non-professional driver, 75 or below Passenger only
- Theory course: lessons and a 10-question test based on the LTO Theoretical Driving Course topics and RA 4136
- Practice mode with no scoring

## Controls
Arrow keys or WASD. On phones, use the on-screen buttons.

## Run locally
No build step and no dependencies except three.js, which loads from a CDN. Open `index.html`, or run `python3 -m http.server` in this folder.

## Content disclaimer
The lessons use public information about the LTO Theoretical Driving Course and RA 4136. They are **not official**. For the real course and exams, use an LTO-accredited school and the official LTO Driver's Manual. Rules and fines change, so check lto.gov.ph. The "Theory passed" badge is a practice badge, not a certificate.

## Credits and legal
- Unofficial fan project. Not affiliated with or endorsed by Toyota, Honda, Suzuki or the LTO. All names and trademarks belong to their owners.
- **Car photos:** the images in `assets/` are placeholders. Replace them with photos you own or that have a license allowing reuse (for example from Wikimedia Commons). The game still works if a photo is missing.
- Built with [three.js](https://threejs.org/) (MIT).

## License
MIT for the code (see `LICENSE`). Photos and brand names are not covered by this license.
